## 🚀 CI/CD Fundamentals with GitHub Actions & Jenkins

> Automate everything from testing to deployment. Learn how to deliver software faster, safer, and smoother using Continuous Integration & Delivery tools.

---

### ✅ What You Need to Know (to be "Done" with CI/CD):

- What is CI/CD?
  - CI = Continuous Integration
  - CD = Continuous Delivery / Deployment
- Why CI/CD is crucial in DevOps
- Common CI/CD Stages: Test, Build, Deploy
- Key Concepts:
  - Pipelines
  - Triggers (push, pull request)
  - Runners (self-hosted vs. cloud)
  - Artifacts
  - Secrets & environment variables
- GitHub Actions:
  - What is a workflow (`.github/workflows/*.yml`)
  - Common actions: `checkout`, `setup-node`, `run`, etc.
- Jenkins:
  - What is Jenkins?
  - How to install and use it (locally or via Docker)
  - Freestyle projects vs. Pipeline (`Jenkinsfile`)
- Security best practices: Don’t leak secrets in logs!

---

### 🔧 Tools You’ll Use

- GitHub Actions (native to GitHub)
- Jenkins (install locally or via Docker)
- Git & GitHub (for SCM and triggers)
- Docker (to build/test containers)
- `curl`, `npm`, `bash` (for pipeline scripting)

---

### 📚 How to Learn

| Type        | Resource                                                                 |
|-------------|--------------------------------------------------------------------------|
| 📺 Video     | [GitHub Actions Full Course (freeCodeCamp)](https://youtu.be/R8_veQiYBjI) |
| 📘 Docs      | [GitHub Actions Docs](https://docs.github.com/en/actions)               |
| 📺 Jenkins   | [Jenkins for Beginners (TechWorld with Nana)](https://youtu.be/FVjK_uZVHRU) |
| 🧪 Playground | [GitHub Actions Playground](https://github.dev)                         |
| 🧑‍💻 Lab      | Install Jenkins locally or use Play with Jenkins [https://play.jenkins.io] |

---

### 🧪 Projects / Mini Tasks

- [ ] Set up your first GitHub Actions workflow to run on push
  - Run a test script
  - Build a simple Docker container
- [ ] Add build + linting steps in your workflow
- [ ] Create a multistage pipeline:
  - Build → Test → Deploy (echo/deploy to S3)
- [ ] Install Jenkins on your machine using Docker
- [ ] Create a Jenkins pipeline using a `Jenkinsfile`
- [ ] Trigger jobs on GitHub commits
- [ ] Use GitHub Secrets to store AWS keys
- [ ] Store build artifacts (optional)

---

### 🧩 Checkpoints

- [ ] Can you describe the CI/CD lifecycle?
- [ ] Can you explain the difference between GitHub Actions and Jenkins?
- [ ] Can you write a `.yml` file for GitHub Actions to deploy a static site?
- [ ] Can you create a Jenkins pipeline that builds a Docker image?
- [ ] Can you explain the risks of hardcoded secrets?

---

### 🎯 Pro Tips

- Use GitHub Actions for simple to moderate workflows. it’s fast & integrated
- Use Jenkins for enterprise-grade customization and plugins
- Keep pipelines modular: test, build, deploy should be separate steps
- Store secrets securely in GitHub or Jenkins credentials
- Always include rollback strategies if you're deploying to production!

---

### 🧠 Completion = You Can...

> Build, test, and deploy your applications automatically with pipelines. You’ll confidently set up workflows in GitHub Actions and Jenkins core skills in any DevOps job.
