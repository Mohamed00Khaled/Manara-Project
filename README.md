# Serverless Image Processing with AWS Lambda & S3

This project automatically processes uploaded images to an S3 bucket using AWS Lambda.

## Features
- Trigger Lambda on S3 image upload
- Resize and re-upload processed images
- Written in Python using Pillow and Boto3
- Managed with Serverless Framework

## Setup

### Prerequisites
- AWS CLI configured
- Node.js & Python installed
- Serverless Framework: `npm install -g serverless`

### Deploy

```bash
sls deploy
