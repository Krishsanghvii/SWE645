Project Title: SWE645 Class Homepage
Author Information
Name: Krish Pranav Sanghvi
Date: 02/06/2025
Course: SWE645
Project Description
This project involves the deployment of a class homepage and a student survey form using AWS S3 for static web hosting. The purpose of this project is to get accustomed to Amazon Web Services.

Repository Contents
index.html - Main homepage file.
error.html - Custom error page.
classroom.jpg - Image used in the homepage.
styles.css - CSS file for the survey form styling.
Screenshots - Documentation of AWS configurations.

Bucket Creation:

Name: krishassignment1.com
Region: us-east-1
Creation Date: February 4, 2025
Bucket Policy and Permissions:

Public Access: Enabled for web hosting.
Policy: Public read access for static website hosting.

{
  "Version":"2012-10-17",
  "Statement":[{
    "Sid":"PublicReadGetObject",
    "Effect":"Allow",
    "Principal": "*",
    "Action":["s3:GetObject"],
    "Resource":["arn:aws:s3:::krishassignment1.com/*"]
  }]
}

Files Hosted:

index.html
error.html
classroom.jpg
Static Website Hosting Configuration:

Index Document: index.html
Error Document: error.html
URLs:

Website Endpoint: http://krishassignment1.com.s3-website-us-east-1.amazonaws.com
