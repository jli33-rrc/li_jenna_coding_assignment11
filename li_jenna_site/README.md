# Development Environment Setup

This project demonstrates how to containerize and run a simple Next.js web application on localhost:7775 (127.0.0.1:7775) using Docker.

## Prerequisites
- Docker installed on your machine. [Docker](https://www.docker.com/get-started) on your machine if it's not already installed.

---

## Steps to Run the Application

### 1. Clone the Repository

Clone this project repository and navigate to its directory:

```bash
git clone https://github.com/jli33-rrc/li_jenna_coding_assignment11.git
cd li_jenna_coding_assignment11
```

### 2. Build the Docker Image

Build the Docker Image by using the following command:

```bash
docker build -t li_jenna_coding_assignment11 .
```

### 3. Run the Docker Container

Run the Docker Container by using the following command:

```bash
docker run -it --name li_jenna_coding_assignment11 -p 7775:7775 li_jenna_coding_assignment11
```

### 4. Access the Application

Once the container starts successfully, you can access the application in your web browser at:

- Local: (http://localhost:7775)
- Network: (http://127.0.0.1:7775)
