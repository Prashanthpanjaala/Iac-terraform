# Iac-terraform

**Terraform** is an open-source Infrastructure as Code (IaC) tool created by **HashiCorp**. It allows you to define and provision infrastructure using a high-level configuration language called **HashiCorp Configuration Language (HCL)** or optionally JSON.

### 🔧 What Terraform Does
Terraform helps manage infrastructure across multiple cloud providers (like AWS, Azure, Google Cloud), as well as services like Kubernetes, GitHub, or even on-premises setups. It can:
- Create and manage virtual machines
- Set up networking
- Manage DNS, firewalls, databases, etc.
- Automate deployment of cloud resources

### 🧱 How It Works (Key Concepts)
- **Providers**: Plugins that let Terraform interact with APIs (e.g., AWS, Azure, GCP).
- **Resources**: The building blocks (like `aws_instance`, `google_storage_bucket`).
- **Modules**: Reusable configurations, kind of like functions in programming.
- **State**: Terraform keeps track of what's deployed using a state file (local or remote).
- **Plan & Apply**: You run `terraform plan` to preview changes and `terraform apply` to execute them.

### ✅ Benefits
- **Repeatability**: Infrastructure setup is consistent and reproducible.
- **Version control**: Configs are just text files—easy to store in Git.
- **Automation-friendly**: Works well with CI/CD pipelines.
- **Multi-cloud**: Manage multiple platforms with a single tool.

### 🔁 A Typical Workflow
1. Write configuration files (`.tf`)
2. Initialize with `terraform init`
3. Preview changes with `terraform plan`
4. Apply changes with `terraform apply`
5. Destroy infrastructure with `terraform destroy` (when needed)

Let me know if you want an example config or a walkthrough of how to use it!

