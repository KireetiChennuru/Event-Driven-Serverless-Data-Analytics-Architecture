# Event-Driven-Serverless-Data-Analytics-Architecture


## Project Name: Real-Time Clickstream Analytics for Restaurant Insights

### Project Synopsis:

This project is designed to provide real-time analytics for a restaurant's menu items based on clickstream data. The goal is to derive actionable insights for a restaurant owner by architecting a data analytics solution using managed services on AWS. The architecture leverages serverless and event-driven components, ensuring scalability, cost efficiency, and real-time processing of data.

## Concepts Covered

### Create IAM Policies and Roles:
- Follow best practices for working securely in the AWS Cloud by defining appropriate IAM policies and roles.

### Create an S3 Bucket:
- Set up an Amazon S3 bucket to store incoming clickstream data.

### Create a Lambda Function:
- Develop a Lambda function that transforms incoming data for Amazon Kinesis Data Firehose.

### Create a Kinesis Data Firehose Delivery Stream:
- Establish a delivery stream to ingest real-time streaming data and deliver it to the Amazon S3 bucket.

### Create a REST API:
- Utilize Amazon API Gateway to create a REST API for inserting data into the system.

### Create an Amazon Athena Table:
- Set up an Athena table to query and view the obtained data stored in S3.

### Create Amazon QuickSight Dashboards:
- Build dashboards in Amazon QuickSight to visualize the analyzed data.

## Services Used

- **AWS Identity and Access Management (IAM):**
  - Policies and roles for secure access control.
  
- **Amazon Simple Storage Service (Amazon S3):**
  - Object storage to store the clickstream data.
  
- **AWS Lambda:**
  - Serverless compute for data transformation.
  
- **Amazon Kinesis Data Firehose:**
  - Real-time data streaming and delivery service.
  
- **Amazon API Gateway:**
  - Managed service to create and manage REST APIs.
  
- **Amazon Athena:**
  - Serverless query service to analyze data in S3.
  
- **Amazon QuickSight:**
  - Business intelligence service to visualize data.

## Project Goals

The primary goal of this project is to design an architecture that ingests, stores, and visualizes clickstream data in real time. The customer, a restaurant owner, aims to gain insights into the performance of menu items ordered in their establishment. Due to limited staff and resources, the architecture utilizes AWS managed services, ensuring minimal maintenance and operational overhead.

## Project Structure

### Task 1: Setup
- Create IAM policies and roles to ensure secure and best-practice configurations.

### Task 2: Creating an S3 Bucket
- Set up an S3 bucket to store incoming clickstream data.

### Task 3: Creating a Lambda Function
- Develop a Lambda function to transform incoming data from the Kinesis Data Firehose delivery stream.

### Task 4: Creating a Kinesis Data Firehose Delivery Stream
- Establish a Firehose delivery stream to handle the real-time ingestion and delivery of data to S3.

### Task 5: Adding the Firehose Delivery Stream ARN to the S3 Bucket
- Update S3 bucket permissions to accept data from the Firehose delivery stream.

### Task 6: Creating an API in API Gateway
- Design and deploy a REST API for data insertion.

### Task 7: Creating an Athena Table
- Set up an Athena table to query the data stored in S3.

### Task 8: Visualizing Data with QuickSight
- Create QuickSight dashboards to provide visual insights into the restaurant's menu item performance.

### Task 9: Deleting All Resources
- Clean up by removing all AWS resources created during the project to avoid unnecessary charges.

## Architecture Diagram

![Architecture Diagram](./Cloud%20Architecture.jpeg)

## Additional Information

For more details on the services and concepts covered in this project, please refer to the following AWS documentation:

- [AWS Identity and Access Management (IAM)](https://aws.amazon.com/iam/)
- [Amazon S3 Documentation](https://aws.amazon.com/s3/)
- [AWS Lambda Documentation](https://aws.amazon.com/lambda/)
- [Amazon Kinesis Data Firehose Documentation](https://aws.amazon.com/kinesis/data-firehose/)
- [Amazon API Gateway Documentation](https://aws.amazon.com/api-gateway/)
- [Amazon Athena Documentation](https://aws.amazon.com/athena/)
- [Amazon QuickSight Documentation](https://aws.amazon/quicksight/)
