To ensure reproducibility and ease of use, our codebase is organized and documented for straight-
forward execution.
•⁠  ⁠Repository: Clone the project from [YourGitHubRepoURL].
•⁠  ⁠Setup: Follow the instructions in the README ([READMEURL]) to set up your environment.
This includes installing dependencies and configuring Spark and HDFS.
•⁠  ⁠Data Ingestion: Upload the provided CSV dataset to HDFS using the included scripts.
•⁠  ⁠Data Processing: Launch Jupyter Notebook and run the PySpark notebooks to perform
data cleaning, transformation, and exploratory analysis.
2
•⁠  ⁠Model Building: Execute the machine learning notebooks to train and evaluate models for
purchase prediction.
•⁠  ⁠Visualization: Generate plots and summary reports directly within the notebooks.
High-Level Logic
1.⁠ ⁠Data Ingestion: Raw CSV data is loaded into HDFS for distributed processing.
2.⁠ ⁠Data Cleaning & Transformation: PySpark jobs clean and structure the data, handling
missing values and formatting timestamps.
3.⁠ ⁠Exploratory Analysis: Key metrics such as product popularity, user activity, and cart
abandonment rates are computed.
4.⁠ ⁠Model Training: Tree-based machine learning models are trained to predict purchase like-
lihood.
5.⁠ ⁠Reporting: Results are visualized and summarized for business interpretation.
