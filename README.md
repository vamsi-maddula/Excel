# Excel
A fully automated Excel reporting solution that transforms raw data into clean datasets, dashboards, KPI reports, and data quality insights using Power Query with one-click refresh functionality.



This project follows a structured end-to-end workflow to transform raw data into meaningful and automated business insights using Excel and Power Query.
The process begins with importing raw data from an external Excel source into Power Query, where all data preparation activities are performed. The dataset undergoes a series of transformation steps including header promotion, data type standardization, removal of blank rows, and text cleaning to ensure consistency across all fields. Data quality issues such as missing values, negative entries, and duplicate records are systematically handled during this stage to ensure that only valid and reliable data is retained for analysis. At the same time, all exceptions are identified and separated into a dedicated exception log to maintain transparency.
Following the cleaning phase, additional calculated fields such as profit, month, and year are created to enhance analytical capabilities and support time-based reporting. The final transformed dataset is then loaded into Excel as a structured table, forming the foundation for all downstream reporting components.
Once the clean dataset is available, it is used to build pivot-based summaries, key performance indicators, and a dashboard that provides a clear overview of business performance. A reconciliation layer is implemented to validate the accuracy of the transformation process by comparing raw and processed data totals, ensuring that no discrepancies remain unexplained. In parallel, a data quality summary is generated to highlight the overall health of the dataset and quantify data issues.
The entire workflow is fully automated through Power Query. When the source data is updated, the user can simply refresh the workbook to re-execute all transformation steps and update every connected component including clean data, reports, dashboards, and logs. This design ensures a scalable, efficient, and reliable reporting solution with minimal manual intervention.


