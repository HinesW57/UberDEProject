# End to End Data Engineering Project based off ride share data

### Languages Used
- Python

### Tools Used
- Jupyter Notebook
- Google Cloud Storage
- Google Compute Engine
- Mage Data Tool
- Google BigQuery
- Google Looker Studio

# Process

## The project uses Jupyter Notebook to mock up the data exploration and data modeling.

## We then create a bucket to store the data in Google Cloud Storage.

## Next we create a virtual machine in Google Compute Engine to host our data pipeline we build with Mage.

## We SSH into our VM to install python and mage. We then launch Mage and create our data loader, transformer, and exporter for the full ETL process.

## The data is then sent from the Mage Exporter to be housed in a Google BigQuery database.

## Finally we load the Google Big Query table in Google Looker Studio and provide an example of how a Data Analyst or Data Scientist may begin to analyze the data.

### This project was inspired by Darshil Parmar and his project on Uber.