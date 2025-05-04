# 🌍 Glowberry Global Tax Structure Simulator — Koyeb CI/CD Deployment Series

This repository documents **nine fully built deployments** of the Glowberry Global Tax Structure Simulator application across various combinations of CI/CD tools, Infrastructure as Code (IaC) frameworks, and Koyeb as the deployment platform.

The goal is to **demonstrate a variety of modern DevOps stacks** in production-grade deployment pipelines using `Docker Compose`, `CI/CD`, and `IaC` — showing how different tools can be integrated to deploy the same application across the same target environment.

---

## 📌 Overview of All Projects

| CI/CD Tool    | IaC Tool     | Repository                                                                                   |
|---------------|--------------|----------------------------------------------------------------------------------------------|
| GitHub Actions| Docker Compose only | [Repo](https://github.com/EphraimX/glowberry-global-tax-structure-simulator-gha-docker-compose-koyeb) |
| GitHub Actions| Terraform     | [Repo](https://github.com/EphraimX/glowberry-global-tax-structure-simulator-gha-docker-compose-terraform-koyeb) |
| GitHub Actions| Pulumi        | [Repo](https://github.com/EphraimX/glowberry-global-tax-structure-simulator-gha-docker-compose-pulumi-koyeb) |
| GitLab CI/CD  | Terraform     | [Repo – GitLab Link Coming Soon] |
| GitLab CI/CD  | Pulumi        | [Repo – GitLab Link Coming Soon] |
| Jenkins       | Docker Compose only | [Repo](https://github.com/EphraimX/glowberry-global-tax-structure-simulator-jenkins-docker-compose-koyeb) |
| Jenkins       | Terraform     | [Repo](https://github.com/EphraimX/glowberry-global-tax-structure-simulator-jenkins-docker-compose-terraform-koyeb) |
| Jenkins       | Pulumi        | [Repo](https://github.com/EphraimX/glowberry-global-tax-structure-simulator-jenkins-docker-compose-pulumi-koyeb) |
| CircleCI      | Docker Compose only | [Repo](https://github.com/EphraimX/glowberry-global-tax-structure-simulator-circleci-docker-compose-koyeb) |
| CircleCI      | Terraform     | [Repo](https://github.com/EphraimX/glowberry-global-tax-structure-simulator-circleci-docker-compose-terraform-koyeb) |
| CircleCI      | Pulumi        | [Repo](https://github.com/EphraimX/glowberry-global-tax-structure-simulator-circleci-docker-compose-pulumi-koyeb) |

> **ℹ️ Note:** Links to GitLab repos will be added as soon as available.

---

## 🛠️ Technologies Used

- **CI/CD Tools:** GitHub Actions, GitLab CI/CD, Jenkins, CircleCI
- **IaC Tools:** Terraform, Pulumi
- **Containerization:** Docker, Docker Compose
- **Cloud Platform:** [Koyeb](https://www.koyeb.com/)
- **Language/Runtime:** TypeScript (Node.js)

---

## 🚀 Purpose

This series is built to help engineers:

- Understand how different CI/CD pipelines can be configured for the same workload
- See IaC integrations that work with container-based deployments
- Compare Pulumi vs Terraform in a real-world context
- Learn how to containerize and deploy microservices to a modern PaaS

---

## 📦 Project Structure (Typical)

```
.
├── .github/workflows/ # Or .gitlab-ci.yml, Jenkinsfile, .circleci/config.yml
├── docker-compose.yml
├── Dockerfile / Dockerfile.koyeb
├── infra/ # Pulumi or Terraform configs
├── src/ # Application source code
├── README.md
└── ...
```


---

## 🧭 How to Navigate This Series

1. Choose your preferred CI/CD tool.
2. Pick the corresponding repo with Docker Compose only, or add an IaC layer with Terraform or Pulumi.
3. Follow each repo’s README to deploy it independently.

---

## ✍️ Author

Built and maintained by [EphraimX](https://github.com/EphraimX)

If this series helps you or inspires your own pipeline design, consider leaving a ⭐️ or sharing with your team.

---

## 📩 Contributing

Interested in adding support for another CI/CD or IaC tool (like ArgoCD, AWS CDK, etc.)? PRs and ideas are always welcome.

---

## 📄 License

MIT License – see individual repos for details.

---
