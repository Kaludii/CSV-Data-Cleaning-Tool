# CSV Data Cleaning Tool

This is a Streamlit app that helps users preprocess and clean CSV files quickly and stress-free. Users can upload one or multiple CSV files, and the app provides several options to merge, filter, and display the cleaned data.

# Web App
Click [Here](https://huggingface.co/spaces/Kaludi/CSV-Data-Cleaning-Tool_App "Here") To View This App Online!

![image](https://user-images.githubusercontent.com/63890666/225223559-e5d58da7-10b3-4252-b963-7bc5885a7d08.png)

## Features

-   Upload one or multiple CSV files.
-   Merge uploaded CSV files.
-   Keep only the header of the first file.
-   Remove duplicate rows.
-   Remove empty rows.
-   Choose end-line characters.
-   Preview DataFrames before downloading.
-   Download cleaned data as separate CSV files.

## Usage

After running the app, you will see a title and description explaining the app's purpose. You can then upload one or multiple CSV files using the file uploader. The app provides options for merging and cleaning the uploaded data.

### Merging and Cleaning Options

-   **Merge uploaded CSV files**: If you upload multiple files, you can merge them into a single DataFrame.
-   **Keep only the header (first row) of the first file**: When merging files, you can choose to keep only the header of the first file and match columns from the other files.
-   **Remove duplicate rows**: Remove any duplicate rows in the merged DataFrame.
-   **Remove empty rows**: Remove any empty rows in the merged DataFrame.
-   **End line**: Choose the end-line characters for your CSV files.

### Preview and Download

-   **Show DataFrames**: Preview the cleaned DataFrames before downloading.
-   **Download cleaned data**: Download the cleaned data as separate CSV files or one big file.

## Requirements

-   Python 3.6 or higher
-   Streamlit
-   Pandas

## Installation

1.  Clone the repository:

`git clone https://github.com/Kaludii/CSV-Data-Cleaning-Tool.git`

2.  Install the required packages: To run this app, you will need to install the following dependencies or type `pip install -r requirements.txt` to automatically download:

-   `streamlit`
-   `pandas`

You can install them using pip:

`pip install streamlit pandas`

3.  Run the app:

`streamlit run app.py`
