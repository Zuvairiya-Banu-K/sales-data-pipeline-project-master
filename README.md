# Google Cloud Data Analytics Project

This repository contains code and configuration files for Google Cloud Data Analytics Project.This project demonstrates the integration of several GCP services to create an efficient and automated data pipeline for sales data. We'll show you how to:

![image](https://github.com/user-attachments/assets/fb39776c-fae5-4d04-8943-6595cf711ccf)


## Overview

1. **Web Portal**: Built with Python Flask to allow users to upload sales data files.
2. **Storage**: Uploaded files are stored in a GCS bucket.
3. **Cloud Function**: Automatically triggered when a file is uploaded to the GCS bucket, extracts data from the file, and loads it into BigQuery.
4. **ETL Process**: Extract, Transform, Load process implemented to handle data from raw upload to processed state.
5. **Reporting**: Summary views and dashboards in Looker Studio for key metrics, with filtering and drill-down capabilities.

![image](https://github.com/user-attachments/assets/8e6ecbb6-ab2a-43d9-93bb-e09159c25896)

## Architecture

![image](https://github.com/user-attachments/assets/9ecad4f3-ab55-4f15-8e78-73602dd7ead9)
