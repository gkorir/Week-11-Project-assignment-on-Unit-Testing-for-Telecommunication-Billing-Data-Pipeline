# Week-11-Project-assignment-on-Unit-Testing-for-Telecommunication-Billing-Data-Pipeline

Google colab  link:https://colab.research.google.com/drive/1HiVGNieETLrmJcRweGYkvso-IkQEGZRh

This project focuses on developing robust unit tests for a Telecommunication Billing Data Pipeline. The data pipeline is responsible for extracting data from a CSV file, performing transformations using pandas, and storing the transformed data in another CSV file. The unit tests will ensure that the data pipeline functions correctly and handles various scenarios and edge cases.

## Background Information

The Telecommunication Billing Data Pipeline project aims to process telecommunication billing data. The provided data pipeline consists of three main functions:

data_extraction:

This function extracts data from a CSV file.

data_transformation:

This function performs transformations on the extracted data.

data_loading:

This function loads the transformed data into another CSV file.

Guidelines for Unit Testing

To effectively test the Telecommunication Billing Data Pipeline, the following guidelines should be followed:

The unittest framework will be used to create the test cases.

Each function in the data pipeline (data_extraction, data_transformation, and data_loading) should have at least three test cases.

Test cases should cover different scenarios and edge cases.
Tests should be independent and not rely on each other.
Descriptive names should be used for test methods to indicate the scenario being tested.
Assertions should be used to validate the expected behavior of each function.
Informative error messages should be provided when assertions fail to aid in debugging.

Sample Input Dataset

A sample CSV file named billing_data.csv has been provided. It contains telecommunication billing data with the following columns: 

'customer_id', 'billing_amount', and 'tax_amount'. This file will serve as the input for the unit tests.
