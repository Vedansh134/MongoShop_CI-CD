# MongoShop CI/CD 🚀📦

**Streamlining My Node.js App Deployment with CI/CD Automation**

---

## 🌟 About This Project

In this project, I built a complete **CI/CD pipeline** for my Node.js application using **Jenkins**. I followed tutorials and YouTube videos to learn and implement each step, which helped me understand the entire pipeline process from code commit to deployment.

---

## 🛠️ What I Learned and Achieved

Throughout this project, I gained hands-on experience with:

- **Jenkins** — the automation server for building pipelines
- **Master-Slave architecture** — understanding how Jenkins manages multiple agents
- **Declarative Pipelines** — writing pipelines in a simple, clear syntax
- **Plugins & Credentials** — integrating DockerHub with Jenkins securely
- **Groovy scripting** — scripting dynamic and powerful pipeline stages
- **Stage management** — organizing my pipeline into logical phases

---

## 🔥 Pipeline Workflow

My pipeline automates the following stages:

### 📌 Different stages of my pipeline:
**Code** → **Build** → **Test** → **Push to DockerHub** → **Deploy**

### 📝 Details:

- **Code**:  
  Developers commit code to GitHub.  
  *Trigger:* Webhooks automatically initiate the pipeline on new commits.

- **Build**:  
  Jenkins compiles the code, resolves dependencies, and prepares the app for testing.

- **Test**:  
  Runs multiple tests:
  - Unit tests for individual components
  - Integration tests for module interactions
  - Code quality checks with tools like SonarQube

- **Push & Deploy**:  
  Jenkins pushes the Docker image to DockerHub and deploys the app to production servers or cloud platforms.

---

## 🚀 How I Managed My Pipeline

1. **Node.js App**:  
   Created and prepared for deployment.

2. **Jenkins Setup**:  
   - Installed Jenkins  
   - Configured agents for distributed builds

3. **Pipeline Creation**:  
   - Wrote a **Declarative Pipeline** in Groovy  
   - Defined stages: Greet, Code, Build, Test, Push, Deploy

4. **Automation & Integrations**:  
   - Integrated GitHub webhooks for automatic triggers  
   - Added DockerHub plugin with credentials for secure image management

---

## 🎯 Final Thoughts

This project not only improved my DevOps skills but also taught me how to automate a smooth and reliable software deployment process. I now understand how such pipelines contribute to **faster**, **consistent**, and **trustworthy** releases.
