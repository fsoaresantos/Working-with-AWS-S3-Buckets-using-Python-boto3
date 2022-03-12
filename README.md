# Working-with-AWS-S3-Buckets-using-Python-boto3

AWS S3 stands for AWS Simple Storage Service and is one of the core services offered by Amazon Web Service (AWS). It's a storage location to images, videos, and data in general; and it's designed to offer industry-leading scalability, security, availability, and performance.

A storage location in S3 is called bucket and stored files are called objects. S3 buckets can be managed in three ways: through AWS CLI, AWS management Console, or language-specific APIs (or SDKs).

Boto3 is the Python SDK for managing AWS resources. Boto3 allows to create, delete, or update AWS resources right from the python script in a Jupter notebook.

In this project I use boto3 to create and delete bucket, to upload to and download files from a bucket, to define bucket policy (to allow or deny a given set of "actions" to "principal" elements, i.e. services or users, to a given S3 bucket) and set bucket CORS configuration (e.g. to allow a web application to access a S3 bucket), and to grant user temporary access to a given S3 bucket through presigned URL.

This project is my development of the guided project "Working with AWS S3 Buckets using Python & boto3" by Coursera.

Notes:
- To run this project you will need an AWS account. You can open one at aws.amazon.com
- To programmatically access S3 bucket you will need to provide the credentials (access key ID and secret access key) of your AWS account user. Only users who have ben granted programmatic access have AWS credentials. These users also need to have permission to access an S3 object (granted trough policy) to be able to manage S3 resorces.
- This notebook run in JupyterLab on Amazon SageMaker Studio.

References:
[1] Amazon S3. https://aws.amazon.com/s3/
[2] Working with AWS S3 Buckets using Python & boto3. Guided Project. Coursera.
[3] AWS SDKs and Tools. https://aws.amazon.com/tools/
