# 🚀 DevOps Internship - Task 3: Infrastructure as Code (IaC) with Terraform

## 📌 Objective

To provision a **local Docker container** using **Terraform**, implementing Infrastructure as Code (IaC) principles.

---

## 🧰 Tools Used

- [Terraform](https://www.terraform.io/)
- [Docker](https://www.docker.com/)

---

## 📁 Files Included

- `main.tf` – Terraform configuration to provision an Nginx container.
- `README.md` – Documentation for the task.
- `screenshots/` – Folder containing screenshots of execution.

---

## 🛠️ Steps to Run the Project

### 1. ✅ Prerequisites
Make sure the following are installed and running:
- Terraform
- Docker

### 2. 🧪 Initialize Terraform
```bash
terraform init
3. 🔍 View the Execution Plan
bash
terraform plan
4. 🚀 Apply the Configuration
bash
terraform apply


5. 🔎 Verify Docker Container
Run:
docker ps
Expected Output:
nginx
Copy code
CONTAINER ID   IMAGE          COMMAND                  CREATED         STATUS         PORTS                  NAMES
<some_id>      nginx:latest   "/docker-entrypoint.…"   few seconds ago Up X seconds   0.0.0.0:8000->80/tcp   first
Visit: http://localhost:8000

6. 🧹 Destroy the Infrastructure
terraform destroy
