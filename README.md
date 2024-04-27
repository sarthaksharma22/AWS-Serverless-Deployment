In this project, we will deploy a serverless web application on AWS, leveraging the power of various AWS services. We'll walk through each step, from setting up an S3 bucket to hosting your static web content
configuring API Gateway to trigger Lambda functions for handling GET and POST requests to interact with a DynamoDB database, and finally, securing your application using CloudFront.

Here's a breakdown of project:

1. Setting up an S3 Bucket**: We'll create an S3 bucket to host our static web content, including HTML, CSS, and JavaScript files.
2. Configuring API Gateways: configure API Gateway endpoints to trigger Lambda functions. We'll cover both GET and POST methods to interact with our DynamoDB database.
3. Creating Lambda Functions: We'll write Lambda functions in Python to handle the API Gateway requests. For example, we'll create functions to retrieve data from DynamoDB and insert new data into it.
4. Working with DynamoDB: set up a DynamoDB table to store our data.Define the table schema and perform CRUD operations using Lambda functions.
5. Implementing Secure Connections with CloudFront: To ensure secure access to our web application, we'll deploy CloudFront as a content delivery network (CDN).
6. We'll configure CloudFront to serve our S3 content securely over HTTPS,providing encryption in transit and improving the performance of our application.
By the end of this, we have a fully functional serverless web application deployed on AWS, capable of securely handling user requests, storing data in DynamoDB, and delivering content efficiently using CloudFront.
