# Active Jobs Data Pipeline 

An automated data collection script that fetches real-time job listings from the Active Jobs DB API, structures the raw JSON into a cleaned Pandas DataFrame, and exports it for analysis.

##  Features
* **Live API Fetching:** Hits the RapidAPI `active-jobs-db` endpoint.
* **Data Structuring:** Converts nested JSON elements (like skills and locations) into structured tabular data using Pandas.
* **Kaggle Integration:** The processed dataset from this pipeline is hosted publicly on Kaggle.

##  Repository Structure
* `FetchAPI.ipynb`: The core Jupyter notebook handling authentication, request limits, and data transformation.
* `active_jobs_data.csv`: The exported dataset containing active job listings (Data Engineering, Cloud ETL, etc.).

##  Tech Stack
* Python
* Pandas
* Requests
