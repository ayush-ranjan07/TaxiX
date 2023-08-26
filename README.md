# TaxiX


Welcome to the TaxiX repository! This project demonstrates a comprehensive Taxi data analysis solution built using cloud technologies. By following these steps, you can replicate the process and gain valuable insights from the Uber dataset.

Dashboard - https://lookerstudio.google.com/reporting/3aaa5b83-6fde-449b-90ef-14719863d839

## Technology Used

Programming Language - 
Python

Google Cloud Platform

Google Storage

Compute Instance

BigQuery

Looker Studio


## Dataset

Dataset Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Dataset Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Steps to Create TaxiX:

1. **Data Storage:**
   Store the dataset securely in Google Cloud Storage. This ensures scalability and reliability for your analysis.

2. **Data Transformation:**
   Utilize Python and the "Maze" data pipeline tool to transform the data effectively. This step prepares the dataset for meaningful analysis.

3. **Data Loading:**
   Load the transformed data into Google Cloud Platform's fully managed data warehouse, BigQuery. This facilitates efficient querying and analysis.

4. **Dimensional Modeling:**
   Leverage draw.io to convert raw data into structured fact and dimension tables. This organization enhances your analytical capabilities.

5. **Joining Tables and Extracting Information:**
   Merge relevant columns from different tables to create a comprehensive fact table. This step sets the foundation for in-depth time-based analysis.

6. **Setting up Access to VM and UI:**
   Create a secure UI connection by configuring a firewall rule. This ensures access is limited to specific IP addresses, prioritizing security.

7. **Connecting to BigQuery:**
   Establish a connection to BigQuery by creating a dedicated service account and obtaining the necessary credentials. This enables seamless data access.

8. **Data Analysis:**
   Perform data analysis to extract valuable insights. For instance, explore average tips based on payment types, providing a deeper understanding of user behavior.

9. **Dashboard Creation:**
   Utilize Local Studio to design an interactive dashboard. Customize it with the Uber logo and incorporate a filter for rate codes to enhance user experience.

## Get Started:

To replicate TaxiX :

1. Clone this repository to your local machine.
2. Follow the steps outlined above in sequence.
3. Refer to the code and configurations provided in the repository for guidance.
4. Explore the results of your analysis and dashboard creation.

Unlock the power of data analysis using cloud technologies with the TaxiX Data Analysis Tool. Make informed decisions and gain insights that can drive strategic advancements.
