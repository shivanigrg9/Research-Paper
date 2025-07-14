# AWS Based Resume Analyzer

A serverless application that extracts, indexes, and searches resume data using AWS services.

## ☁️ Technologies Used
- AWS Lambda
- Amazon Textract
- Amazon OpenSearch
- Amazon S3
- API Gateway
- Python

## ⚙ Features
- Upload PDF resumes
- Extracts text using Textract
- Indexes into OpenSearch for searching by skill/keyword
- Search API to find best-fit resumes

## 🔄 Workflow
1. Resume uploaded to S3.
2. Lambda triggers Textract.
3. Parsed data is pushed to OpenSearch.
4. Frontend/API enables search.


