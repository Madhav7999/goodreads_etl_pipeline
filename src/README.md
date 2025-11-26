# AWS Data Processing Pipeline

This repository contains tools for managing data ingestion and processing workflows within AWS environments. The system is designed to handle structured data across multiple staging zones to ensure data integrity and scalability.

## Configuration

The project requires a configuration file to manage AWS credentials and bucket locations. The config.cfg file in the src folder contains:

```ini
[AWS]  
KEY=<AWS-KEY>
SECRET=<AWS-SECRET-KEY>
  
[BUCKET]  
LANDING_ZONE=<Landing zone bucket name>
WORKING_ZONE=<working zone bucket name>  
PROCESSED_ZONE=<processed zone bucket name>  
  
[FILES]  
NAME=author.csv,book.csv,reviews.csv,user.csv
```

### Setup Instructions

1. Ensure you have the necessary AWS IAM permissions for S3 access.
2. Update the [AWS] section with your access key and secret key.
3. Define the bucket names for the Landing, Working, and Processed zones.
4. List the target files in the [FILES] section as comma-separated values.

## Maintainer

This project is maintained by Madhav Meesala. 

Madhav is a Software Engineer with over 4 years of experience building scalable full-stack and distributed systems across financial services and digital payments. His expertise includes Java, C++, Python, and AWS, with a focus on cloud-native development, microservices, and high-performance data solutions.

### Contact and Professional Profiles

- Email: madhavmeesala@gmail.com
- GitHub: https://github.com/
- LinkedIn: https://www.linkedin.com/in/