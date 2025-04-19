iac-repo/
├── main.tf          # Core infrastructure (ECS, VPC, IAM)
├── ecr.tf           # ECR repositories for both services
├── s3-sqs.tf        # S3 bucket and SQS queue
├── ecs.tf           # ECS task definitions and services
├── variables.tf     # Variables (e.g., AWS region)
└── outputs.tf       # Outputs (e.g., ECR repo URLs)


# step 1
run https://github.com/KeenGWatanabe/tf-backend.git

# step 2
$ terraform init
$ terraform plan
$ terraform apply