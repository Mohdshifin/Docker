# Docker Containerization Study

As part of my Docker containerization study, I have successfully built and deployed two projects. These projects demonstrate my ability to containerize applications, manage dependencies, and orchestrate multi-container environments.

---

## 1. Day3-Task-Docker (Node.js)

In this project, I containerized a Node.js application with a focus on efficiency. I successfully ran the application **without** installing `node_modules` on my local host by leveraging Docker's internal file system.

### Key Learnings:
* **Dockerfile:** Created a custom image to package the Node.js environment.
* **.dockerignore:** Optimized build times by excluding local dependencies and logs.
* **Docker Compose:** Streamlined the deployment process.
* **Volumes:** Implemented persistent storage and "bind mounts" to sync code changes instantly.
* **Networking:** Configured a dedicated network for secure container-to-container communication.

---

## 2. Full-Stack-Docker (React & Node)

This project involved containerizing a complete full-stack application, featuring a **React.js** frontend and a **Node.js** backend.

### Key Learnings:
* **Multi-Service Dockerfiles:** Created independent, optimized Dockerfiles for both the Frontend and the Backend.
* **Orchestration:** Used **Docker Compose** to link both services together, allowing them to run as a single application with one command.
* **Full-Stack Connectivity:** Managed environment variables and networking so the React frontend could seamlessly communicate with the Node.js API.

---

## How to Run These Projects

1. Clone the repository.
2. Navigate to either project folder.
3. Run:
   ```bash
   docker-compose up --build

