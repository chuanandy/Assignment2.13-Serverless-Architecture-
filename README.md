# Assignment2.13-Serverless-Architecture-

Make a comparison between Serverless Framework and Terraform as tools for IaC by answering:

1. What type of infrastructure and application deployments are each tool best suited for?
   >> Serverless Framework:
   - Best for serverless apps like AWS Lambda functions, APIs, and event-driven microservices; 
   - Handles deployment of functions, APIs (API Gateway), and related resources (S3 buckets, DynamoDB tables);
   - focuses on app-specific, ephemeral resources.

   >> Terraform:
   - Best suited for full-stack infrastructure provisioning across multiple providers (AWS, Azure, GCP, Kubernetes, on-prem).
   - Ideal for creating complex, multi-service environments—VPCs, networking, databases, compute clusters, CI/CD infra.
   - suitable to use for consistent, large-scale, multi-cloud deployments
  
2. How do their primary objectives differ?
   >> Serverless Framework:
   - Simplifies serverless app development and deployment, tying infrastructure to code for quick iterations.
   - Provides plugins/templates to speed up function and API delivery.

   >> Terraform:
   - Provides declarative IaC for consistent, reproducible management of broad infrastructure across providers.
   - Provider-agnostic, meant to cover the full infra lifecycle, not just app deployment.
  
3. How do they differ in terms of learning curve and ease of use for developers or DevOps teams?
   >> Serverless Framework:
   - Lower learning curve;
   - Easy for developers with simple YAML configs and built-in serverless patterns;
   - Limited flexibility outside serverless workloads.

   >> Terraform:
   - Steeper curve due to more complex HashiCorp Configuration Language (HCL), extensive provider ecosystem, and need to understand concepts like modules, variables, and
     state management;
   - Better for DevOps handling large-scale ops;
   - Requires careful planning for modules, state handling, and best practices.
