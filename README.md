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



Sure! Here's a breakdown of **Docker** in a simple, no-fluff way:

---

### 🐳 What Is Docker?

**Docker** is a platform that lets you **package, distribute, and run applications in containers**. Think of containers as lightweight, portable virtual machines—but way faster and more efficient.

---

### ⚙️ Why Use Docker?

- **Consistency**: Works the same on your laptop, in testing, and in production.
- **Isolation**: Each app runs in its own environment, with its own dependencies.
- **Portability**: Containers can run anywhere Docker is installed.
- **Speed**: Containers start up quickly compared to VMs.
- **Efficiency**: Uses fewer system resources.

---

### 🔍 Key Concepts

| Concept        | What It Is                                                  |
|----------------|-------------------------------------------------------------|
| **Image**      | A snapshot of your app and its environment. Read-only.      |
| **Container**  | A running instance of an image. Think: process in a box.    |
| **Dockerfile** | A text file with instructions to build a Docker image.      |
| **Docker Hub** | Public registry where images are stored and shared.         |
| **Volume**     | Persistent storage for containers (data that doesn’t vanish).|
| **Network**    | Communication between containers or with the outside world. |

---

### 🧱 Typical Workflow

1. **Write a Dockerfile** – defines your app’s environment
2. **Build an image** – `docker build -t my-app .`
3. **Run a container** – `docker run -p 8080:80 my-app`
4. **Push to Docker Hub** (optional) – `docker push username/my-app`

---

### 🔥 Simple Example

**Dockerfile:**
```Dockerfile
FROM node:18
WORKDIR /app
COPY . .
RUN npm install
CMD ["npm", "start"]
```

Then:
```bash
docker build -t my-node-app .
docker run -p 3000:3000 my-node-app
```

---


MAIN.TF: The main.tf file is a primary configuration file used in Terraform to define infrastructure resources. While Terraform doesn't require the file to be named main.tf, it's a common naming convention to keep the code organized, especially in larger projects. You can break up the configuration into multiple .tf files, and Terraform will read them all in the same directory.


![Screenshot (77)](https://github.com/user-attachments/assets/ed59b2f6-7e53-493b-95f9-602e8a0bc801)


![Screenshot (78)](https://github.com/user-attachments/assets/57887c48-b1af-4f1c-80d3-817b4ca88429)



![Screenshot (80)](https://github.com/user-attachments/assets/995eca6e-e0ab-48e0-828d-f4d4b555c7c1)

![Screenshot (81)](https://github.com/user-attachments/assets/df65af37-01ce-43ea-9c80-b3e95051f99a)


![Screenshot (82)](https://github.com/user-attachments/assets/0db4ab48-7f0b-45e6-bcb5-0fca9cc5fb44)


![Screenshot (84)](https://github.com/user-attachments/assets/ae2d49f3-6d74-41af-beef-d0f05c5844f1)

![Screenshot (85)](https://github.com/user-attachments/assets/2f21dc89-e823-4f3b-8013-d3a7ab68bb42)



![Screenshot (86)](https://github.com/user-attachments/assets/a3dd3c66-23f3-40cd-8339-2eab1a3d27e3)

![Screenshot (87)](https://github.com/user-attachments/assets/d4bb67ac-9136-43f0-a7a9-0c618dec9f6b)


![Screenshot (88)](https://github.com/user-attachments/assets/664c840e-1ca8-4b7f-bde0-a6d076960e9e)


![Screenshot (91)](https://github.com/user-attachments/assets/21ae59bf-ffc6-46da-9dac-cdf07c0b8978)
