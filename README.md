This project aims to guide you through building a real-world DevOps automation project using Python, AWS Lambda, and Terraform. 
Whether you’re interested in learning or creating innovative DevOps projects, this tutorial is for you.

Implementation:
In this project, Terraform will be used to provision an AWS Lambda function, with Python as the Lambda runtime. 
The Python script will monitor a specified path within an S3 bucket, automatically moving newly uploaded files into organized folders based on year, month, and date. 
An S3 event notification will trigger the Lambda function whenever new files are uploaded to the designated path.