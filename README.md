## What this repo do
- Create 1 vpc
- 4 subnet (2 public and 2 private)
- 2 route table
- 1 nat gateway and attache it to private route table
- 1 iGW

## Prerequisites

- AWS CLI installed and configured
- Terraform installed
- Appropriate IAM access

## Setup Instructions

### Step 1: AWS CLI Configuration
- `[Install AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)`
   
### Step 2: Install Terraform
- `terraform -v`

## Terraform Commands
**Initialize Terraform:**
- `terraform init`

**Plan Terraform deployment:**
- `terraform plan`

**Apply Terraform deployment:**
- `terraform apply`

**Destroy Terraform deployment:**
- `terraform destroy`
