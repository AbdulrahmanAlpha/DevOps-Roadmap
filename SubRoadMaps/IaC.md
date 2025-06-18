## 🛠️ Infrastructure as Code with Terraform

> Learn to define and provision cloud infrastructure using code. With Terraform, you automate the boring stuff. repeatably, reliably, and at scale.

---

### ✅ What You Need to Know (to be "Done" with Terraform):

- What is Infrastructure as Code (IaC)?
- Why use Terraform (vs AWS CloudFormation or Ansible)?
- Terraform Basics:
  - Providers
  - Resources
  - Variables
  - Outputs
  - State files
- Terraform Core Commands:
  - `init`, `plan`, `apply`, `destroy`
- File Structure: `main.tf`, `variables.tf`, `outputs.tf`
- How Terraform interacts with AWS using IAM credentials
- Managing multiple environments (dev, prod) using workspaces or modules
- Understand the risks of changing the infrastructure live

---

### 🔧 Tools You’ll Use

- Terraform CLI (install from [terraform.io](https://www.terraform.io/downloads))
- AWS Free Tier (you’ll use it to test)
- VS Code + Terraform Extension
- GitHub (for version control)

---

### 📚 How to Learn

| Type        | Resource                                                                 |
|-------------|--------------------------------------------------------------------------|
| 📺 Video     | [Terraform Full Course (FreeCodeCamp)](https://youtu.be/SLB_c_ayRMo)     |
| 📘 Docs      | [Official Terraform Docs](https://developer.hashicorp.com/terraform)     |
| 💻 Lab       | [Katacoda Terraform Scenarios](https://www.katacoda.com/courses/terraform) |
| 🎓 Cert      | [HashiCorp Certified: Terraform Associate](https://developer.hashicorp.com/certification/terraform-associate) |

---

### 🧪 Projects / Mini Tasks

- [ ] Install Terraform and configure it with your AWS credentials
- [ ] Write a simple config to:
  - Create an EC2 instance
  - Launch a security group
  - Provision an S3 bucket
- [ ] Output instance IP after deployment
- [ ] Use variables for region, instance type, and AMI
- [ ] Separate your code into modules
- [ ] Store remote state in S3 (Bonus)
- [ ] Destroy your resources with `terraform destroy`

---

### 🧩 Checkpoints

- [ ] Can you explain what `terraform plan` vs `terraform apply` does?
- [ ] Can you provision a basic AWS setup using just code?
- [ ] Can you use variables and outputs to make your code reusable?
- [ ] Can you read and understand the Terraform state?
- [ ] Can you safely destroy resources and avoid disasters?

---

### 🎯 Pro Tips

- Always run `terraform plan` before `apply`
- Use `.tfvars` files to keep your variables clean
- Use version control (GitHub) to track IaC changes
- Don’t store secrets in plain `.tf` files, use environment variables or secret managers

---

### 🧠 Completion = You Can...

> Provision cloud resources like EC2, VPCs, and S3 buckets using code, confidently manage changes, and build reusable infrastructure for real-world DevOps workflows.
