# climactic-food - data definition

## Create python virtual environment and install dependencies

1. Create ```venv_data_definition```:

On the root folder of your project, run:

```
python -m venv venv_data_definition
```

2. Activate the virtual environment:

```
source venv_data_definition/bin/activate
```

3. Install dependencies:

```
pip install -r requirements_venv_data_definition.txt
```

## weather dataset

- 2020.csv: Global weather data from NOAA

## food production dataset

## References:

- How to open large .csv or text files with python: https://pythoninoffice.com/how-to-open-large-csv-or-text-files/

--- 

- How to read the files directly from Google Drive: https://medium.com/datadriveninvestor/google-drive-data-directly-to-your-jupyter-otebook-without-authenticating-5a95e271bc89 (Does not work very well with big files --> "Google Drive can't scan this file for viruses." what stops the automatic file download)

- How to skip google drive virus scan warning about large files: https://www.marstranslation.com/blog/how-to-skip-google-drive-virus-scan-warning-about-large-files

- How to download your google drive data to your jupyter notebook
https://medium.com/@umdfirecoml/a-step-by-step-guide-on-how-to-download-your-google-drive-data-to-your-jupyter-notebook-using-the-52f4ce63c66c


- OneDrive SDK for Python: https://github.com/OneDrive/onedrive-sdk-python (I think is demised)