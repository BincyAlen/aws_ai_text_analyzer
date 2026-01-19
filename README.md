# AI Text Analyzer (AWS Serverless Project)

## Overview
AI Text Analyzer is a serverless web application built using AWS services to analyze customer reviews or application feedback. The application performs sentiment analysis and extracts key phrases using Amazon Comprehend.

This project was built to gain hands-on experience with cloud-native architecture and managed AI services.
---

## Architecture
The application follows a fully serverless architecture:

- **Frontend**: Static HTML hosted on Amazon S3
- **API Layer**: Amazon API Gateway (HTTP API)
- **Backend**: AWS Lambda (Python)
- **AI Service**: Amazon Comprehend

User flow:
1. User enters text in the web UI
2. Frontend sends a POST request to API Gateway
3. API Gateway triggers a Lambda function
4. Lambda calls Amazon Comprehend for analysis
5. Results are returned and displayed in the browser
---

## Technologies Used
- AWS Lambda (Python)
- Amazon API Gateway (HTTP API)
- Amazon Comprehend
- Amazon S3
- IAM (Roles & Policies)
- HTML, JavaScript (Frontend)
---

## Features
- Sentiment analysis (Positive / Neutral / Negative / Mixed)
- Key phrase extraction
- Real-time analysis
- Serverless and cost-effective design

---

## Sample Input
- app crashes during payment processing
---

## Sample Output
- sentiment: NEGATIVE
- key_phrases: crashes
  
---
## Deployment Notes
- CORS configured via API Gateway
- IAM role configured with least privilege access
- Auto-deployment enabled for API Gateway stage
- Designed for low-cost usage and scalability

---

## Demo 
🌐 Live demo link: http://bincy-ai-text-analyzer-ui.s3-website-us-east-1.amazonaws.com

---

## Disclaimer
This project focuses on cloud architecture, service integration, and system design. Frontend and backend code was implemented with assistance from AI tools, with full understanding and validation of the logic and workflows.
