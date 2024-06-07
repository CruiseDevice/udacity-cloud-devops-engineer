# Static Website Deployment

This guide outlines the steps to manually deploy a static website into an AWS S3 bucket with HTTP hosting and CloudFront.

Bucket website endpoint: http://my-5257-2224-9866-bucket.s3-website-us-west-1.amazonaws.com/
Distribution domain name: https://dqjjhxz7981sx.cloudfront.net

## Overview

1. Creating an S3 bucket
2. Configuring the bucket for website hosting
3. Securing it using IAM policies
4. Uploading the website files to your bucket
5. Speeding up content delivery using AWS's content distribution network service, CloudFront
6. Accessing your website in a browser using the unique S3 endpoint

## Files Included

- `bucket-created.png`: Screenshot showing the S3 bucket creation.
- `bucket-policy.png`:  Screenshot showing the IAM bucket policy making the bucket publicly accessible.
- `cloud_front.png`: Screenshot showing CloudFront configured to retrieve and distribute website files.
- `cloud-front-website.png`: Screenshot showing site hosted on CloudFront link.
- `s3-files-uploaded.png`: Screenshot showing all website files uploaded to the S3 bucket.
- `s3-website.png`: Screenshot showing site hosted on S3 link.
- `static-website-hosting.png`: Screenshot showing the S3 bucket configured for static website hosting.