# Reddit Streamline Analytics
https://github.com/AbhijitChallapalli/Kafka/assets/83178772/2f0cf1ff-21fa-45f4-9682-bd59431d0906
## Overview
Reddit Streamline Analytics is a real-time streaming project designed to analyze and process data using Apache Kafka and AWS services. This project demonstrates the implementation of a scalable and robust architecture capable of handling high-throughput data streams effectively.

## Technologies Used
- **Apache Kafka**: For building real-time data pipelines and streaming apps.
- **AWS EC2**: Hosts the Kafka instances for stream processing.
- **AWS S3**: Stores the streamed data for further analysis.
- **AWS Glue**: Crawls the data to prepare for querying.
- **AWS Athena**: Queries the data to extract actionable insights.

## Setup and Installation

### Prerequisites
- AWS Account
- Kafka Installation
- JDK Installation

### Configuration Steps
1. **Create and configure AWS EC2 instances**:
    - SSH into your instance and install Kafka and JDK.
    - Configure memory settings and server properties to allow public access.

2. **Start Zookeeper and Kafka Server**:
    - Use provided scripts to start both services, ensuring proper shutdown and cleanup of previous instances.

3. **Security Configuration**:
    - Adjust EC2 security group settings to allow traffic.

4. **Kafka Topics, Producers, and Consumers Setup**:
    - Create necessary Kafka topics.
    - Setup producers and consumers to simulate real-time data flow.

5. **Python Integration**:
    - Use Python scripts to automate data production and consumption.

6. **AWS S3 and IAM Configuration**:
    - Setup S3 buckets and configure IAM roles for access management.

7. **AWS Glue and Athena Integration**:
    - Utilize Glue for data schema detection and Athena for querying.

## Usage
The system is designed to take input from producers, process it through Kafka, and store outputs in S3, making it available for querying via Athena. Adjust configurations as necessary based on your AWS setup.

## Contributing
Contributions to enhance the functionality or efficiency of this project are welcome. Please fork the repository and submit a pull request with your updates.

## License
This project is open-sourced under the MIT license.
