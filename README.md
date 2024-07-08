# End-to-End Data Engineering Project

![Architecture](https://github.com/c2-tlhah/youtube-data-engineering/blob/main/youtube-data-engineering-architecture.jpeg)

## Overview
This repository contains the code and resources for an end-to-end data engineering project using the Kaggle YouTube Trending Dataset. The project leverages various AWS services to build a scalable and efficient data processing pipeline.

## Architecture
The architecture includes the following components:
- **Data Ingestion**: Source data ingested using S3 API into the S3 Landing Area.
- **Data Lake**: Organized into Landing Area, Cleansed/Enriched Area, and Analytics/Reporting Area.
- **Data Processing**: AWS Glue and AWS Lambda for ETL processes.
- **Data Cataloging**: AWS Glue Data Catalog for data classification.
- **Data Access and Analytics**: AWS Athena and Redshift for querying and analysis, with visualization tools like QuickSight and Power BI.

## Features
- Create and manage an AWS S3 data lake.
- Use AWS Glue to build crawlers and catalog data.
- Perform ETL operations with AWS Lambda.
- Query data using AWS Athena.
- Visualize data using QuickSight and Power BI.

## Getting Started
### Prerequisites
- AWS account
- AWS CLI installed
- Basic knowledge of Python, SQL, Spark, and AWS services

### Setup
1. **Create an AWS account** and set up the necessary IAM roles.
2. **Install the AWS CLI** on your local machine.
3. **Create an S3 bucket** and upload the Kaggle YouTube Trending Dataset.
4. **Build AWS Glue crawlers** to catalog the data.
5. **Use AWS Lambda** for ETL jobs to clean and transform data.
6. **Query data with AWS Athena** and visualize results using QuickSight or Power BI.

## Resources
- [AWS Account Setup](https://aws.amazon.com/premiumsupport/)
- [Download AWS CLI](https://aws.amazon.com/cli/)
- [Kaggle YouTube Trending Dataset](https://www.kaggle.com/datasnaek/youtube-new)


## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

Feel free to contribute, raise issues, or suggest improvements!
