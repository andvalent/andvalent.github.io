# Andrea Valente, PhD | AWS Cloud & Solutions Architect | Senior Data Scientist

<!-- 
Instructions:
1. Create an 'assets' folder in your repository.
2. Upload your CV pdf file (e.g., 'Andrea_Valente_CV.pdf') into that folder.
3. The link below should work automatically.
-->
<table>
  <tr>
    <td style="border: 0;">
      <img src="assets/profile.jpg" alt="Profile picture of Andrea Valente" style="width: 150px; border-radius: 50%;">
    </td>
    <td style="border: 0; vertical-align: middle;">
      <h1>Andrea Valente</h1>
      <p><strong>AWS Cloud & Solutions Architect | Senior Data Scientist</strong></p>
      <p>
        <a href="https://www.linkedin.com/in/andrea-valente-phd-74493b21/">LinkedIn</a> • 
        <a href="https://github.com/andvalent">GitHub</a> • 
        <a href="assets/Andrea_Valente_CV.pdf">Download my CV</a>
      </p>
    </td>
  </tr>
</table>

---

---

I am an **AWS Certified Solutions Architect** with a deep background in data science. My passion is helping startups and businesses build intelligent, scalable, and cost-effective cloud solutions. I bridge the gap between robust infrastructure and data-driven insights, ensuring your platform is not only secure and resilient but also optimized for performance and cost from day one.

My unique value comes from combining infrastructure-as-code best practices with a strategic understanding of data pipelines, machine learning workloads, and analytics.

## What I Can Do For You

*   **Cloud Cost Optimization & Strategy:** I design and review AWS architectures with a primary focus on cost-effectiveness. I help you forecast expenses, implement budget alerts, and right-size resources to ensure you only pay for what you need.
*   **Serverless & Event-Driven Solutions:** I build highly scalable, low-maintenance applications using AWS Lambda, API Gateway, DynamoDB, and other serverless technologies, perfect for APIs, data processing, and backend services.
*   **Infrastructure as Code (IaC):** I automate the deployment and management of your entire cloud environment using **Terraform** and **Amazon CDK**, ensuring consistency, repeatability, and eliminating manual errors.
*   **Data & Analytics Solutions on AWS:** Leveraging my data science background, I architect data pipelines using services like **AWS Glue**, **S3**, and **Athena** and design infrastructure to support **Machine Learning** workloads.
*   **CI/CD Automation:** I implement automated build, test, and deployment pipelines using **GitHub Actions** to accelerate your development cycle and improve release quality.

---

## Portfolio Projects

Here are a few examples of solutions I can build.

<!-- 
Instruction: 
For each project, update the link to point to your actual GitHub repository.
For example: [View Code on GitHub](https://github.com/andvalent/serverless-api-project)
-->

### Project 1: Serverless Data & AI Pipeline

An automated pipeline that ingests data from Reddit, enriches it with AI-generated summaries using Amazon Bedrock, and makes it available for analysis with SQL.

*   **The Challenge:** Businesses need to analyze public community discussions for market research, but manual methods are slow and unscalable.
*   **My Solution:** I designed an end-to-end, event-driven pipeline on AWS. It uses Lambda for ingestion, **Amazon Bedrock (AI)** for summarization, and Glue/Athena for analysis. The entire infrastructure is provisioned with **Terraform**.
*   **Technologies Used:** Terraform, AWS Lambda, Amazon Bedrock, S3, Glue, Athena.
*   **[View Project on GitHub](https://github.com/andvalent/AWS-Serverless-Reddit-Data-Analysis-Pipeline)**

### Project 2: Automated ECS Deployment for a Containerized API

A practical demonstration of deploying a containerized Python application on AWS ECS, with the entire infrastructure provisioned as code using the AWS CDK.

*   **The Challenge:** A common requirement is to deploy a containerized backend service to the cloud in a repeatable and automated fashion.
*   **My Solution:** I containerized a FastAPI application using **Docker** and wrote an **AWS CDK** script to automate the entire infrastructure deployment. The script provisions a VPC, an **ECS Cluster** (EC2 launch type), and a service to run the application container. The web UI is hosted on S3, demonstrating a decoupled architecture.
*   **Technologies Used:** Docker, AWS ECS, AWS CDK, FastAPI, S3.
*   **[View Project on GitHub](https://github.com/andvalent/garmin-rundata-ecs-app)**

### Project 3: Live Serverless Web App for Civic Reporting

A live, full-stack web application that allows citizens in Cyprus to report illegal waste dumping. The platform features user authentication, GPS-tagged photo uploads, and an interactive map showing all reports.

*   **The Challenge:** Create a highly scalable, secure, and extremely low-cost platform for a public-facing, civic-tech initiative.
*   **My Solution:** I designed and built a 100% serverless application on AWS. It uses **Amazon Cognito** for user authentication (including Google federated login), an API built with **API Gateway and Lambda**, and **DynamoDB** as the database. Images are securely uploaded using **S3 presigned URLs** and validated with **Amazon Rekognition**. The entire CI/CD process is automated with **AWS Amplify**.
*   **Technologies Used:** AWS Amplify, CloudFront, Cognito, API Gateway, Lambda, DynamoDB, Rekognition, S3.
*   **[View Live Application](https://www.cypruswastemap.com/)**
*   *(Note: This is a production application. The source code is private but can be discussed upon request.)*