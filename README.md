Welcome to the Formula1 Analytics Project!

This PySpark-based project focuses on ingesting, transforming, and analyzing Formula1 race data from 8 sources like circuits,races,constructors,results,pitstops,lap_times and qualifyings employing various file formats, such as CSV, JSON, and multiline JSON in folders, as well as CSV folders.I have applied a range of transformations, including joins, filters, and aggregations, to derive meaningful insights from the Formula1 datasets.

Key Features:

Data Ingestion: Supports ingestion of diverse data formats, including CSV, JSON, multiline JSON folders, and CSV folders.
Transformations: Employs PySpark transformations such as joins, filters, and aggregations to enhance data quality and structure.
SQL Usage: Utilizes PySpark SQL for efficient data manipulation and transformation, streamlining the process of preparing data for both presentation and in-depth analysis.
Analysis and Presentation: The project extracts valuable insights from the Formula1 dataset.
Dominant Driver and Team Extraction: Through meticulous analysis, the project identifies the dominant driver and team based on predefined criteria, providing a clear overview of Formula1 performance.

Project Structure:

src/: Contains Formula1 datasets.

notebooks/:Includes PySpark databricks scripts for data ingestion, transformation, and analysis. 
Databricks notebooks for detailed walkthroughs and visualizations.

How to Use:

Clone the repository: git clone [https://github.com/shivashankarkammari/Formula1db1_project.git]
Navigate to the project directory: cd Formula1db1_project
Run PySpark scripts: spark-submit notebooks/ingestion
Feel free to explore the Azure Databricks notebooks in the notebooks/ directory for a step-by-step guide on the data analysis process.

Contributing:
Contributions, bug reports, and feature requests are welcome! Feel free to fork the repository, make your changes, and submit a pull request.

Enjoy exploring the fascinating world of Formula1 through data analytics! 🏎️📊
