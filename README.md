# 🚀 DevOps Mini Project: Dockerized Node.js App with Terraform Simulation

This project simulates deploying a Node.js backend service using Docker, Docker Compose, and Infrastructure as Code with Terraform (mocked for local use). It mirrors real-world DevOps workflows used in cloud environments like AWS.

---

## 🧠 What This Project Demonstrates

| Layer             | Technology         | Purpose                                  |
|------------------|--------------------|------------------------------------------|
| Application       | Node.js + Express | Simple backend for testing deployment    |
| Containerization  | Docker            | Package app for portability              |
| Orchestration     | Docker Compose    | Run containers easily                    |
| Infra-as-Code     | Terraform (local) | Simulate provisioning without AWS        |
| Version Control   | Git + GitHub      | Source code and project hosting          |

---

## 📁 Folder Structure


---

## 🛠️ Technologies Used

- Node.js
- Express.js
- Docker
- Docker Compose
- Terraform (`null_resource`)
- Git & GitHub

---

## 🧪 How to Run

### 1. Clone this repo:
```bash
git clone https://github.com/sree125/devops-ecommerce-project.git
cd devops-ecommerce-project

## 🧰 Terraform Mock Setup

This simulates provisioning an EC2 instance using a local `null_resource` block.

### Run:
```bash
cd terraform
terraform init
terraform apply

Then save: `Ctrl + O`, `Enter`, `Ctrl + X`

---

## ✅ Step 3: Commit & Push the README Update

```bash
git add README.md
git commit -m "Update README with Terraform simulation instructions"
git push

## 📎 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).  
You're free to use, modify, and distribute it — just give credit!
