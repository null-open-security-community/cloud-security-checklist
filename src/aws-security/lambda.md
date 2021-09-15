# Lambda

1. Preventive
    * Code Signing
    * Block public access to S3 bucket
    * S3 Bucket encryption at rest
    * Allows only signed container from AWS ECR (for containerized lambda)
    * Configure Security Groups to allow only required traffic from the VPC
    * Avoid associating all subnets with VPC endpoint associate only subnets that need access to required endpoint resources 
2. Detctive
    * Enable Cloudtrail
    * Enable AWS Config
3. Logging and monitoring
    * Enable Cloudtrail
    * Enable AWS Xray
4. Identity and Access Management
    * Triggers
        - API : Authentication - IAM (REST API) JWT (HTTP)
        - Share only required API endpoint Lamda functions through the API gateway 
              : API Key not prefered
        - Services : IAM
    * IAM 
        - Grant least privilege policy
        - Generate Policy based on
CloudTrail Activity
        - Avoid sharing the same IAM role between Lamda functions (setup a dedicated IAM role per Lamda function)

