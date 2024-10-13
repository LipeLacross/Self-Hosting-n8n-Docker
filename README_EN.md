## 🌐 [Versão em Português do README](README.md)

# Self-hosting-n8n-docker

This project sets up a self-hosted instance of [n8n](https://n8n.io/), a workflow automation platform, using Docker and PostgreSQL as the database. The `docker-compose.yml` provides a fully configured environment to start n8n with data persistence.

## 🔨 Project Features

- Self-hosted n8n instance running in a Docker container.
- PostgreSQL database to persistently store workflow data.
- Data persistence using Docker volumes for the database.
- Easy setup and deployment using Docker Compose.

### Visual Example of the Project
![n8n Interface](https://docs.n8n.io/assets/img/landing/hero-small.png)

## ✔️ Techniques and Technologies Used

- **n8n**: Workflow automation platform.
- **Docker**: Containerization tool to isolate environments easily.
- **PostgreSQL**: Relational database used to store data.
- **Docker Compose**: Tool to define and run multi-container Docker applications.

## 📁 Project Structure

- **Dockerfile**: Defines the Docker environment for n8n.
- **docker-compose.yml**: Configuration file for Docker Compose to set up n8n and PostgreSQL.
- **README.md**: Project documentation.

## 🛠️ How to Open and Run the Project

To run the project locally, follow these steps:

1. **Make sure Docker and Docker Compose are installed**:
   - Check if Docker is installed by running:
     ```bash
     docker -v
     ```
   - If not installed, download and install [Docker](https://www.docker.com/get-started) and [Docker Compose](https://docs.docker.com/compose/install/).

2. **Clone the Repository**:
   - Copy the repository URL and run the following command in the terminal:
     ```bash
     git clone https://github.com/LipeLacross/Self-hosting-n8n.git
     ```

3. **Set up the Docker environment**:
   - In the root directory of the project, run Docker Compose:
     ```bash
     docker-compose up -d
     ```

4. **Access the application**:
   - Access n8n at `http://localhost:5678`.

## 🌐 Deployment

To deploy the project on a server or platform like Render or Azure, you can use the same `docker-compose.yml` file. Some platforms may require adjustments to the Dockerfile or specific network configurations.
