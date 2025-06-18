## 🔐 DevSecOps & Monitoring/Logging (Prometheus + Grafana)

> Secure your pipelines, monitor your systems, and understand what’s going on in your infrastructure in real-time.

---

### ✅ What You Need to Know (to be "Done" with DevSecOps & Monitoring):

#### 🔐 DevSecOps:

- What is DevSecOps? (Shift left + security as code)
- Security in the pipeline:
  - Static code analysis (SAST)
  - Dependency scanning (e.g., `trivy`, `grype`)
  - Secret scanning
- Secure your Docker images and containers
- Using tools like:
  - `trivy`, `grype` (vulnerability scanning)
  - `gitleaks`, `talisman` (secret scanning)
  - OWASP Top 10 (basics)
- CI/CD integration of security checks

#### 📊 Monitoring & Logging:

- Why monitoring/logging matters in DevOps
- Difference: Logging vs Monitoring vs Observability
- Metrics, Alerts, Dashboards
- Prometheus basics (pull-based metrics, exporters)
- Grafana dashboards (beautiful visualizations)
- Basic alerting (via Alertmanager or Grafana)

---

### 🔧 Tools You’ll Use

- **Security**: `trivy`, `grype`, `gitleaks`, `talisman`
- **Monitoring**: `Prometheus`, `Grafana`, `Node Exporter`, `Alertmanager`
- **Logging**: `Loki`, `Fluentd` (optional)
- CI Tools: GitHub Actions, Jenkins (to automate scans)

---

### 📚 How to Learn

| Type        | Resource                                                                 |
|-------------|--------------------------------------------------------------------------|
| 📺 Video     | [Prometheus + Grafana Basics (freeCodeCamp)](https://youtu.be/h4Sl21AKiDg) |
| 📘 Docs      | [Prometheus Docs](https://prometheus.io/docs/introduction/overview/)     |
| 📘 Docs      | [Trivy Docs (by AquaSec)](https://aquasecurity.github.io/trivy/)          |
| 🧪 Labs      | [Katacoda DevSecOps Scenarios](https://www.katacoda.com/courses/devsecops) |
| 🧑‍💻 Hands-on | Try Prometheus + Grafana using Docker Compose setup                        |
| 🎮 Bonus Game| [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) (for web app security testing)

---

### 🧪 Projects / Mini Tasks

- [ ] Scan your own Docker image using `trivy` or `grype`
- [ ] Integrate `trivy` into a GitHub Actions pipeline
- [ ] Use `gitleaks` to scan for secrets in your repo
- [ ] Run Prometheus + Node Exporter in Docker
- [ ] Visualize CPU/memory metrics in Grafana
- [ ] Add alerts to notify when CPU > 70%
- [ ] Monitor one of your apps and show the dashboard
- [ ] Optional: Use Loki to log container logs and send to Grafana

---

### 🧩 Checkpoints

- [ ] Can you explain “Shift Left” in security?
- [ ] Can you add a security scan to a CI pipeline?
- [ ] Can you visualize metrics in Grafana?
- [ ] Can you distinguish logs vs. metrics vs. traces?
- [ ] Can you detect and fix a CVE found in an image?

---

### 🎯 Pro Tips

- Security is everyone’s job, not just InfoSec teams.
- Monitoring is your best friend when things go wrong.
- Keep security and observability simple and automated.
- Set alerts that matter; not every warning needs a wake-up call.
- Show your dashboards in portfolios; it stands out in interviews.

---

### 🧠 Completion = You Can...

> Add automated security checks to your pipelines and set up live dashboards to monitor app health and performance. You’ll secure and observe like a real DevOps/SRE engineer.
