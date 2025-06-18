## 🐳 Docker & Containers for DevOps

> Build once, run anywhere; containers are how modern apps stay fast, portable, and isolated. Time to dockerize your DevOps skills.

---

### ✅ What You Need to Know (to be "Done" with Containers & Docker):

- What is a container vs. a VM?
- Why containers are important in DevOps workflows.
- Install Docker and run your first container (`hello-world`).
- Understand Dockerfile and how to build images.
- The difference between an image and a container.
- Use `docker build`, `docker run`, `docker ps`, `docker stop`, `docker exec`.
- Create and use Docker volumes for persistent storage.
- Use Docker Compose to define multi-container setups.
- Tag, push, and pull images from Docker Hub.
- Understand container networking (ports, bridge mode, etc.).
- Basics of container security and best practices.

---

### 🔧 Tools You’ll Use

- `docker`, `docker-compose`
- Dockerfile
- Docker Hub (or GitHub Container Registry)
- VS Code Docker extension (optional but handy)
- Portainer (GUI for managing containers – optional)

---

### 📚 How to Learn

| Type        | Resource                                                                 |
|-------------|--------------------------------------------------------------------------|
| 📺 Video     | [Docker Crash Course – freeCodeCamp](https://youtu.be/fqMOX6JJhGo)       |
| 📘 Docs      | [Official Docker Docs](https://docs.docker.com/get-started/)             |
| 🧠 Interactive | [Play with Docker](https://labs.play-with-docker.com/)                   |
| 📙 Cheatsheet | [Docker CLI Cheat Sheet](https://dockerlabs.collabnix.com/docker/cheatsheet/) |

---

### 🧪 Projects / Mini Tasks

- [ ] Install Docker and run the `hello-world` container
- [ ] Build your own Docker image using a custom `Dockerfile`
- [ ] Create a containerized Python/Node app and expose it to a port
- [ ] Use Docker Compose to run a frontend + backend app (e.g., Nginx + Flask)
- [ ] Use a volume to persist container data
- [ ] Push your image to Docker Hub
- [ ] Explore multi-stage builds and image size optimizations
- [ ] Try Portainer to manage containers visually

---

### 🧩 Checkpoints

- [ ] Can you explain what happens when you run `docker run`?
- [ ] Can you build and run a container from a `Dockerfile`?
- [ ] Can you describe the difference between an image, container, and volume?
- [ ] Can you write and run a `docker-compose.yml` file?
- [ ] Can you troubleshoot common errors (like port already in use, permission issues)?

---

### 🎯 Pro Tips

- Use `.dockerignore` to keep builds clean.
- Always pin your image versions (e.g., `nginx:1.23` instead of `latest`).
- Keep containers small, single-purpose, and stateless.
- Containers are ephemeral; persistent data goes in volumes or external services.
- Security matters! Don’t run everything as root.

---

### 🧠 Completion = You Can...

> Build, run, and manage containerized applications with confidence — and use Docker as a foundation for Kubernetes, CI/CD, and production deployments.
