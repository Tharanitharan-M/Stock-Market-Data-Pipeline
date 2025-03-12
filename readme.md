# Stock Market Data Pipeline

## Overview
The **Stock Market Data Pipeline** is designed to process and analyze real-time financial transactions using **Apache Kafka** and **AWS services**. The pipeline ensures efficient data ingestion, storage, and querying, facilitating real-time analytics for stock market data.

## Architecture Diagram
![Architecture Diagram](Architecture.jpg)

## Features
- **Real-Time Data Processing:** Utilizes Apache Kafka for streaming stock market data.
- **Scalable Data Storage:** AWS S3 for storing raw and processed data.
- **Automated Schema Detection:** AWS Glue Crawler to automate schema discovery.
- **Efficient Data Querying:** AWS Athena for querying and analyzing data stored in S3.
- **Automated Data Pipelines:** Orchestrated processes using AWS Lambda for seamless data flow.

## Technologies Used
- **Programming Language:** Python, SQL
- **Streaming Platform:** Apache Kafka
- **Cloud Services:**
  - AWS S3 for data storage
  - AWS Lambda for serverless computing
  - AWS Glue for ETL and schema management
  - AWS Athena for querying

## Setup Instructions
1. **Prerequisites:**
   - AWS account with access to S3, Lambda, Glue, and Athena.
   - Apache Kafka setup for streaming data.
   - Python 3.x installed.

2. **Clone the Repository:**
```bash
 git clone https://github.com/Tharanitharan-M/Stock-Market-Data-Pipeline
 cd stock-market-data-pipeline
```

3. **Set Up Kafka:**
- Start Kafka services and configure necessary topics for stock data ingestion.

4. **Configure AWS Resources:**
- Create S3 buckets for raw and processed data.
- Set up AWS Glue Crawlers for schema detection.
- Create Lambda functions for processing incoming data.
- Set up Athena databases and tables for querying.

5. **Run the Pipeline:**
- Execute the Python scripts to initiate data streaming and processing.

6. **Query Data Using Athena:**
- Use SQL queries in AWS Athena to analyze processed data.

## Contribution
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is open-source and available under the [MIT License](LICENSE).

---

For any questions or support, feel free to contact me at [muthuthirumaran.t@northeastern.edu](mailto:muthuthirumaran.t@northeastern.edu).

