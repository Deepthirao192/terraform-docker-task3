# DevOps Internship Task 3: Terraform and Docker

## Objective
Provision a Docker container using Terraform.

## Tools Used
- Terraform
- Docker
- Nginx
- AWS EC2
- Git and GitHub

## Project Description
This project demonstrates Infrastructure as Code (IaC) using Terraform to create and manage a Docker container.

## Steps Performed
1. Installed and verified Terraform and Docker.
2. Created the `main.tf` Terraform configuration.
3. Configured the Docker provider.
4. Downloaded the Nginx Docker image.
5. Created a Docker container named `terraform-nginx-task3`.
6. Mapped port 80 inside the container to port 8080 on the EC2 server.
7. Ran `terraform init`, `terraform validate`, and `terraform plan`.
8. Used `terraform apply` to create the resources.
9. Verified the Nginx website in a browser.
10. Checked Terraform state.
11. Ran `terraform destroy` successfully.

## Verification
Terraform reported that two resources were destroyed. The Terraform state list was empty after destruction.

## Project Files
- `main.tf` — Terraform configuration.
- `plan.log` — Terraform plan output.
- `state.log` — Terraform state output.
- `.terraform.lock.hcl` — Provider dependency lock file.
- `screenshots/` — Screenshots of task execution.

## Conclusion
Successfully completed the Terraform workflow to provision, verify, and destroy Docker infrastructure.
