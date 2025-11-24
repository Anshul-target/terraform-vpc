# Project Structure

```
.
├── .gitignore
├── main.tf
├── provider.tf
├── variables.tf
├── userdata.sh
├── userdata1.sh
└── README.md
```

---

# Features

- Deploys AWS infrastructure using Terraform
- Supports VPC, subnets, EC2, and security groups (based on your main.tf)
- Centralized variable handling using variables.tf
- AWS provider setup in provider.tf
- EC2 initialization via userdata.sh and userdata1.sh
- Clean and extensible Terraform project layout

---

# Prerequisites

- Terraform installed (v1.0+ recommended)
- AWS CLI installed and configured:
  aws configure
- AWS account with permissions for:
  - EC2
  - VPC
  - IAM (read access)
  - Networking components

---

# Usage

1. Initialize Terraform: `terraform init`
2. Validate configuration: `terraform validate`
3. Preview changes: `terraform plan`
4. Deploy infrastructure: `terraform apply`
5. Destroy infrastructure: `terraform destroy`

---

# How to Contribute

1. Fork the repository
2. Create a new branch for your feature/fix
3. Make your changes
4. Commit with a descriptive message
5. Push your branch
6. Open a pull request
