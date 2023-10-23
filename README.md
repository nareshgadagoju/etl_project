# Twitter Data Pipeline Project

## Overview
This project is an End-To-End Data Engineering project that utilizes Python, Apache Airflow, and AWS S3 to extract, transform, and load data from the Twitter API. The goal is to create a scalable and automated data pipeline for collecting and storing Twitter data in an AWS S3 bucket.

## Architecture
!(https://github.com/nareshgadagoju/etl_project/blob/main/aws.jpg)

## Project Components
The project consists of the following components:
1. **Task 1: Extract Data from API**
   - Use the Twitter API to retrieve data from Twitter.
   - Implement a Python script for data extraction.

2. **Task 2: Transform Data**
   - Apply data transformation and cleaning to the extracted data.
   - Use Python for data manipulation and transformation.

3. **Task 3: Load Data/Store Data**
   - Load the transformed data into an AWS S3 bucket.
   - Ensure data is appropriately organized and stored for future analysis.

## Technologies Used
- **Twitter API**: Used to fetch data from Twitter.
- **Python**: Utilized for data extraction, transformation, and other scripting tasks.
- **Apache Airflow**: Used to automate and schedule the ETL pipeline tasks.
- **AWS S3**: The destination for storing the final data.

## Project Structure
The project is organized as follows:
# Airflow Project Directory Structure

- `Airflow Project/`
  - `scripts/`
    - `twitter_etl.py`
    - `twitter_dag.py`
    - `requirements.txt`


- `airflow project/`: Contains Apache Airflow-related files and directories.
- `twitter_etl.py/`: Extract, Transform, Load (ETL) script designed to retrieve and process tweets from a Twitter user's timeline (in this case, the SpaceX Twitter account) and then store the extracted data in a CSV file located in an Amazon S3 bucket.
- `twitter_dag.py/`: Airflow DAG file that defines the ETL pipeline.
- `requirements.txt`: Required packages and libraries to be installed.


## Prerequisites
Before running the project, you'll need to:
- Set up your Twitter API credentials with https://developer.twitter.com/en/docs/twitter-api/getting-started/about-twitter-api.
- Install required Python libraries specified in `requirements.txt`.

## Usage
1. Clone this repository to your local machine.
2. Set up your Twitter API as mentioned in the "Prerequisites" section.
3. Install the necessary Python libraries by running:

                        `p install -r requirements.txt`

4. Start the Apache Airflow scheduler and web interface.

5. Navigate to the Airflow web interface in Chrome browser with (Ec2 public ipv4 dns with 8080).






