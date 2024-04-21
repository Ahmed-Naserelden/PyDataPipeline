## ETL (Extract, Transform, and Load) Operations with Python

## Introduction
This project focuses on implementing Extract, Transform, and Load (ETL) operations using Python. ETL is a crucial aspect of data engineering, involving the extraction of data from various sources, transformation of the data into a suitable format, and loading it into a database for further analysis.

In this project, we demonstrate the ETL process by extracting data from CSV, JSON, and XML file formats, transforming it into the required format (e.g., converting units), and loading the transformed data into a CSV file.

## Objectives
After completing this project, you will be able to:

- Read data from CSV, JSON, and XML file formats.
- Extract the required data from different sources.
- Transform the data into the desired format (e.g., unit conversion).
- Save the transformed data into a CSV file for further processing or database loading.

## Project Structure
The project consists of the following components:

1. `etl.py`: Python script containing functions for ETL operations.
2. `data/`
    * `*.csv`: Samples of CSV files for data extraction.
    * `*.json`: Samples of JSON files for data extraction.
    * `*.xml`: Samples of XML files for data extraction.
3. `output/`
    * `transformed_file.csv`: Output CSV file containing transformed data.
    * `log_file.text`: Output text file to stores all the logs.

## Usage
1. Clone the repository to your local machine:

    ```
    git clone https://github.com/Ahmed-Naserelden/PyDataPipeline.git
    ```

2. Navigate to the project directory:

    ```
    cd 'ETL Workflow'
    ```

3. Run the `etl.py` script:
    
    windows:
        ```
        python etl.py
        ```

    linux:
        ```
        python3 etl.py
        ```

4. The script will extract data from the provided CSV, JSON, and XML files, perform transformation (unit conversion), and save the transformed data to `output/transformed_data.csv`.

## Dependencies
- Python 3.10
- `os` module (built-in)
- `json` module (built-in)
- `pandas` module  `pip install pandas`
- `xml.etree.ElementTree` module (built-in)
