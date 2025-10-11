# 🐍 Django Docker Containerization Demo

This project demonstrates **Docker containerization** of a Django application.  
It packages the app along with all its dependencies for **consistent, portable, and scalable deployment**.  
The project also showcases modern **DevOps practices**, simplifying management and ensuring the app runs reliably across different environments.

---

## 🚀 Prerequisites

Before running the project, make sure you have:

- **Docker installed**  
  [Docker Documentation](https://docs.docker.com/get-docker/)
- **Docker daemon running**
  ```bash
  docker info
## 📂 Setup & Run

Follow these steps to build and run the application:

**1️⃣ Navigate to the project directory:**
```bash
cd python-web-app
2️⃣ Build the Docker image:

bash
Copy code
docker build -t django-app .
3️⃣ Run the Docker container:

bash
Copy code
docker run -p 8000:8000 -it django-app
4️⃣ Verify the Docker image:

bash
Copy code
docker images
