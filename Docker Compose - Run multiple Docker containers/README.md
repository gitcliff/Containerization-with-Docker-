#   9 - Docker Compose - Run multiple Docker containers


# 📖 Summary

Completed **Lab 9 - Docker Compose - Run Multiple Docker Containers**, focusing on **orchestrating multi-container applications** using a single `docker-compose.yaml` file.
Tasks included **configuring MongoDB and Mongo Express services with persistent volumes and network dependencies, launching them together via Docker Compose, and connecting a Node.js backend app** to the MongoDB instance.
This approach solved the challenge of **managing multiple interconnected containers** efficiently and **enabled scalable, production-like environments for development and testing**.

---

# 🛠️ Tools Used

* **Docker Compose**: 🐳 *Automated the setup and orchestration of multi-container environments*
* **MongoDB**: ⚙️ *Provided a database container with authentication and persisted data using Docker volumes*
* **Mongo Express**: 🌐 *Delivered a GUI for managing MongoDB data visually*
* **Node.js (Express)**: 💻 *Backend application connected to the MongoDB container for API interaction*

---

# 🎯 Skills Gained

* ✅ **Multi-Container Orchestration**: Managed MongoDB, Mongo Express, and Node.js services declaratively via `docker-compose.yaml`
* ✅ **Service Dependencies & Networking**: Used `depends_on` and custom Docker networks for seamless inter-service communication
* ✅ **Persistent Storage**: Configured Docker volumes to ensure MongoDB data remained intact across container restarts
* ✅ **Full-Stack Integration**: Connected backend Node.js app to MongoDB database in a containerized environment

---

# ⚠️ Challenges Faced

* 🧩 **Setting Up Service Dependencies**: Solved startup sequence issues between MongoDB and Mongo Express using `depends_on`
* 🧹 **Cleanup & Resource Management**: Learned to gracefully shut down and remove networks, volumes, and containers with `docker-compose down`

---

# 💡 Why It Matters

This lab reinforced best practices for **container orchestration**, showing how **Docker Compose simplifies multi-container management** by using declarative YAML configurations.
Such skills are essential for building scalable microservice architectures and enabling consistent, repeatable deployments across development and production environments. 🚀

---