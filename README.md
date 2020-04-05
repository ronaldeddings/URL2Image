# URL2Image

This project enables a user or organization to leverage an AWS Lambda function to browse to a URL an retrieve a screenshot. This project is extremely lightweight and leverages **Serverless Framework** There are several use cases for this project:

- Web Crawling
- Malicious/Suspicious URL Enrichment
- Example for getting started with Serverless

## Prerequisites

- **AWS Account**
- **Generate AWS Credentials** (https://www.youtube.com/watch?v=KngM5bfpttA)
- **Node.js** 
    - https://nodejs.org/en/download/
- **Serverless Framework** 
    - `curl -o- -L https://slss.io/install | zsh`
- **Configure credentials**
    - `serverless config credentials --provider aws --secret <secret> --key <key>`
- `git clone https://github.com/ronaldeddings/URL2Image`
- **Install Python Requirements** 
    - `serverless plugin install -n serverless-python-requirements`
- **Unzip Headless Chrome**
    - `cd url2image`
    - `unzip headless-chromium.zip`

## One Command Deployment
- `serverless deploy`
