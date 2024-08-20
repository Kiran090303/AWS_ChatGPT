# AWS_ChatGPT

An advanced implementation of a ChatGPT model using AWS cloud services, including Bedrock, IAM roles, Lambda, API Gateway, and Postman API. This project demonstrates the integration and deployment of a conversational AI model within a robust, scalable, and secure AWS environment.

## Table of Contents
- 📐 Setup Amazon Bedrock
- 🔨 Create IAM Role
- 🛠️ Creating Lambda Function
- 🔩 API Gateway
- 🧪 Postman
- 💭 Conclusion

## 📐 Setup Amazon Bedrock

AWS Bedrock provides easy access to advanced generative AI models through a unified API. By following a simple setup process, you can deploy private instances of these models to enhance your projects.

### Key Steps:

1. **Sign Up for an AWS Account**

   Ensure you have an AWS account with programmatic access enabled. If you don't already have an account, visit [aws.amazon.com](https://aws.amazon.com) to create a free account.

2. **Request Access to Models in the AWS Bedrock Console**

   Once signed in, use the search bar to navigate to the Bedrock console. Click on “Request model access” and submit your use case for the models you wish to use. Note that certain models may be available only in specific regions like US East and US West.

3. **Get Approved Instantly**

   After submitting your request, AWS typically grants access immediately. You'll receive an email notification from AWS once access is granted.

---

[![AWS ChatGPT Architecture](https://github.com/user-attachments/assets/1a9fe8cb-f661-411a-ac4e-1dc9a12a946d)](https://github.com/user-attachments/assets/1a9fe8cb-f661-411a-ac4e-1dc9a12a946d)

## 🔨 Create IAM Role

<img width="956" alt="IAM role" src="https://github.com/user-attachments/assets/beeb01a6-2ca8-4320-bc1d-1590b9491181">

Attach the `AmazonBedrockFullAccess` policy and `CloudWatchLogsFullAccess` to the role.

---

## 🛠️ Creating Lambda Function

- **Select** **Python 3.12** as the runtime.
- **Use** the IAM role that was created earlier.

<img width="947" alt="lambda1" src="https://github.com/user-attachments/assets/31d5badd-408b-436a-a63d-30e061b3b84b">

- **Paste** the code from the `lambda.py` file into the Lambda function code editor.

## 🔩 Connect API Gateway to Lambda

<img width="955" alt="lambda2" src="https://github.com/user-attachments/assets/e9df0563-36d5-4d11-acf9-82a0cb78dee6">

## 🧪 Postman

[![Postman Guide](https://github.com/user-attachments/assets/74ef42af-03fd-43c2-bf15-7e935328f327)](https://github.com/user-attachments/assets/74ef42af-03fd-43c2-bf15-7e935328f327)

## 💭 Conclusion

This guide has provided a detailed, step-by-step approach for implementing ChatGPT on AWS. We have explained the capabilities of ChatGPT and how it can be integrated. Additionally, we have provided an example use case for ChatGPT on AWS.

By following this guide, you should now have a solid understanding of how to securely implement ChatGPT on AWS and leverage its powerful capabilities to enhance your business processes.

![image](https://github.com/user-attachments/assets/df3d3c78-d2ca-47b0-90e3-0e5a33e7255e)
