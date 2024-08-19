# Dockerized Python 3.12 - Hello World Example

This repository provides a simple example of how to Dockerize a Python 3.12 application. The goal is to help beginners get started with Docker and Python by running a basic "Hello, World!" program in a containerized environment.

## Getting Started

Follow these steps to run the Python application in a Docker container.

### Prerequisites

- [Docker](https://www.docker.com/) installed on your machine.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/docker-python-hello-world.git
    cd docker-python-hello-world
    ```

2. **Build the Docker image**:
    ```bash
    docker build -t python-hello-world .
    ```

3. **Run the Docker container**:
    ```bash
    docker run --rm python-hello-world
    ```

### Expected Output

After running the above command, you should see the following output in your terminal:

```bash
Hello, World!
