# Dataset Processing Pipeline

## Description
This project contains a **Python wrapper** for automatically processing various datasets.  
The main notebook (`10. Wrapper to Process all Data Sets.ipynb`) is used to read, clean, and store datasets in a more structured format for easy use in data analysis or data engineering pipelines.

## Project Structure
```
dataset-processing-pipeline/
│── data/                  # Sample datasets (optional, or link to dataset source)
│── notebooks/             # Main notebook
│   └── 10. Wrapper to Process all Data Sets.ipynb
│── scripts/               # (optional) Python script version
│── requirements.txt       # List of required libraries
│── README.md              # Project documentation
```

## Features
- Reads multiple datasets at once.
- Parsing schema from JSON files.
- Using Pandas for data transformation.
- Reusable wrapper for other datasets.
- Supports saving results to a more structured format.

## Installation
Clone this repository and enter the project folder:
```bash
git clone https://github.com/username/dataset-processing-pipeline.git
cd dataset-processing-pipeline
```

Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate   # Linux / MacOS
venv\Scripts\activate      # Windows
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Use
1. Open the notebook:
```bash
   jupyter notebook notebooks/10. Wrapper to Process all Data Sets.ipynb
   ```
2. Run the notebook sequentially.
3. The dataset will be processed according to the schema and saved in the output folder.

## Example Output
- Cleaned CSV/Parquet files.
- Process log on the console.
- (Optional) Result table after data transformation.

## Technologies Used
- Python 3.x
- Pandas
- Glob
- JSON
- Regex
- OS & Sys utilities

##  Notes
- The dataset is not included in this repository due to file size, but it can be used with the `retail_db` dataset or other datasets by adjusting the schema.
- This project was created as a **data engineering** exercise for processing data with Python.

## 👨‍💻 Contributor
- Rio Febriyan

