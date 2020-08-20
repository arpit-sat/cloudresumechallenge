# cloudresumechallenge
The below technologies were utilized to create the serverless website
– Amazon S3 : Host the contents of website designed/styled in HTML, CSS and JavaScript

– Amazon CloudFront : CDN to cache static assets and serve HTTPS requests

– AWS Certificate Manager : Provision and Manage custom SSL ceritificates

– Amazon API Gateway : “Front Door” for the site to interact with backend services such as AWS Lambda

– AWS Lambda : FaaS written in Python to log/get the visitor count information from database

– Amazon DynamoDB : Database to store the visitor count information

– Amazon Route 53: DNS service to map custom domain name to Amazon CloudFront

– GitHub : Source control for code changes and GitHub Actions for CI/CD workflow

– Project Link : https://s3.arpitsatnalika.in/

Taking the challenge: https://forrestbrazeal.com/2020/04/23/the-cloud-resume-challenge/
