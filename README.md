# Simple-Python-Pipeline

This script is designed to extract and process multiple Excel files and extract relevant information from each file. The processed data is then combined into a master file for further analysis.

## Prerequisites

- Python 3.x
- pandas library

## Getting Started

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/your-repository.git
   ```

2. Install the required dependencies:
	```shell
	pip install pandas
	```
3. Place the Excel files you want to process in the designated folder (/To Add Primary TIN) within the cloned repository.

4. Update the file paths in the script (process_excel_files.py) to match your local environment:
	```shell
	folder = "Add path of files to be processed"
	processed = "Add path to folder to store processed files"
	error = "Add path to folder to store failed files"
	```
5. Run the script	

6. The script will process each Excel file in the designated folder. Relevant information will be extracted, and the data will be combined into a master file.

7. Check the PROCESSED and ERROR folders to find the processed files and any files that encountered errors, respectively.

