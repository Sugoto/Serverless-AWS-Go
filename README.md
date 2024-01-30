# 🚀 Serverless CRUD Microservice using Go

Welcome to the showcase of this Serverless CRUD microservice written in Go, powered by AWS Lambda, DynamoDB, and API Gateway. This README highlights the key aspects and features of the project.

## 📋 Project Overview

This project demonstrates a Serverless CRUD (Create, Read, Update, Delete) microservice architecture built with the following components:

- **AWS Lambda**: Serverless compute service to run the Go code.
- **DynamoDB**: A NoSQL database for storing data.
- **API Gateway**: Exposes HTTP endpoints to interact with the microservice.

## 🌐 Architecture

The Serverless CRUD microservice follows this simple architecture:

- **Create**: Accepts POST requests to add new records.
- **Read**: Supports GET requests to fetch records by ID.
- **Update**: Handles PUT requests to modify existing records.
- **Delete**: Accepts DELETE requests to remove records by ID.

## 🚀 Key Features

- **Serverless**: Leverages AWS Lambda for automatic scaling and cost efficiency.
- **Scalable**: DynamoDB handles the data scaling automatically.
- **Easy Deployment**: Streamlined deployment process for rapid development.
- **Customizable**: Easily tailor the service to the specific needs.

## 📊 Cost Comparison: Serverless vs. Serverful AWS Services

### Assumptions
- **Requests per Month**: 1 million
- **AWS Lambda**:
  - Execution Time per Request: 500ms
  - Memory Allocated: 128MB
- **Amazon DynamoDB**:
  - Item Size: 1KB
  - Storage: 10GB
- **Amazon API Gateway**:
  - API Calls per Month: 1 million
- **EC2/EBS/ELB (Serverful)**:
  - Instance Type: t3.medium
  - Storage: 20GB EBS
  - Load Balancer: Application Load Balancer

## Costs (per month)
- **Serverless (AWS Lambda, DynamoDB, API Gateway)**: `$6.76`
- **Serverful (EC2, EBS, ELB)**: `$48.15`

## Savings
- **Percent Savings by Using Serverless**: Approximately `86%`

*Note: Calculations are based on standard AWS pricing and specific assumptions. Actual costs may vary.*
