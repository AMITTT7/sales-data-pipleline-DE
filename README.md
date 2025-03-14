# Google Cloud Data Analytics Project

This repository contains code and configuration files for Google Cloud Data Analytics Project.This project demonstrates the integration of several GCP services to create an efficient and automated data pipeline for sales data which has 100k+ rows



## Overview

1. **Web Portal**: Built with Python Flask to allow users to upload sales data files.
2. **Storage**: Uploaded files are stored in a GCS bucket.
3. **Cloud Function**: Automatically triggered when a file is uploaded to the GCS bucket, extracts data from the file, and loads it into BigQuery.
4. **ETL Process**: Extract, Transform, Load process implemented to handle data from raw upload to processed state.
5. **Reporting**: Summary views and dashboards in Looker Studio for key metrics, with filtering and drill-down capabilities.



![image](https://github.com/vishal-bulbule/sales-data-pipeline-project/assets/143475073/613ef050-9538-4a87-98f5-95694e87455e)

## Architecture

![image](https://github.com/vishal-bulbule/sales-data-pipeline-project/assets/143475073/7ec3e2ec-f981-4fe4-9b3e-2c48dcbcdf0a)
