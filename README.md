# Serverless Microservice Tuned with Lambda Power Tuning, Postman load testing results

This repository demonstrates a serverless microservice architecture using AWS Lambda, API Gateway, and DynamoDB. The architecture is designed to be scalable, cost-effective, and easy to maintain.

I used Lambda Auto Power Tuner to optimize the performance of the Lambda functions in this architecture. The Auto Power Tuner automatically adjusts the memory and CPU allocation for each function based on its usage patterns, which helps to reduce costs and improve performance.

I also used postman to perform load testing on the API Gateway endpoints to ensure that the architecture can handle high traffic and provide a good user experience. And to demonstrate that the performance increase after changing the memory allocation, I used AWS CloudWatch to monitor the performance metrics of the Lambda functions before and after the optimization.

<img width="2661" height="1404" alt="Lambda Auto Power Tuner (3)" src="images/DraftDiagramforGithub.drawio.png" />

What This Delivers

- A serverless microservice architecture using AWS Lambda, API Gateway, and DynamoDB.
- Optimized Lambda functions using Lambda Auto Power Tuner.
- Load testing steps and screenshot of the API Gateway endpoints using Postman.
- Performance monitoring of the Lambda functions using AWS CloudWatch before and after optimization.
- Github to AWS auth via OIDC ( so no need to store AWS credentials in Github secrets, which is more secure and easier to manage).
- Proves that more memory allocation for Lambda functions can improve performance and reduce costs.

Most teams configure Lambda memory once and forget about it. But Lambda Auto Power Tuner can help you optimize your functions for better performance and cost savings. By using this tool, you can ensure that your serverless microservice architecture is running at its best.
