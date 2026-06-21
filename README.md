# Serverless Microservice Tuned with Lambda Power Tuning

This repository showcases a production-ready serverless microservice built on AWS Lambda, API Gateway, and DynamoDB. The architecture emphasizes scalability, cost-efficiency, and maintainability—ideal for modern cloud-native applications.

<br/>

<img width="2661" height="1404" alt="Lambda Auto Power Tuner (3)" src="images/DraftDiagramforGithub.drawio.png" />

# Key Highlights

- Automated Lambda Optimization – Integrated Lambda Power Tuning to dynamically adjust memory and CPU allocations based on real-time usage patterns. This data-driven approach balances performance and cost without manual intervention.

- Performance Validation – Conducted load testing via Postman to validate API Gateway endpoint resilience under high traffic. Performance gains from memory adjustments were measured and visualized using AWS CloudWatch metrics, clearly demonstrating the impact of optimization.

- Secure CI/CD – Implemented GitHub OIDC for AWS authentication, eliminating the need to store long-lived credentials in GitHub Secrets. This enhances security and simplifies access management.

# What This Proves

Most teams configure Lambda memory once and forget it. This project proves that right-sizing memory allocation can significantly improve function performance while reducing overall cost—and that continuous optimization should be a standard practice, not an afterthought.
