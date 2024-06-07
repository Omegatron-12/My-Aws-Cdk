# My-Aws-Cdk
Assignment of AWS CDK TYPESCRIPT

• Create a VPC with 2 public and 2 private subnets, having a single NAT gateway.
• Create an ECS cluster with a service having 2 tasks with 0.25 vCPU and 0.5 GB Memory each, in the private subnet.
• Deploy a sample ECR image (amazon/amazon-ecs-sample) into the task.
• Set up an ALB in front of the ECS service, allowing traffic to port 8080 of the ECS tasks.
• Share the ALB endpoint and code.

Bonus points for the following:
• Configure deployment controller for ECS service to CodeDeploy.
• Set up a CodePipeline for the ECS deployment with a source GitHub repository having a sample Dockerfile (nginx).
