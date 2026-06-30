# i2i Academy - Containerization - Assignment 2

This repository contains the configuration files for the Containerization homework assignment under the i2i Academy Training Program.

## Project Description
The goal of this assignment is to understand the mechanics of containerization by deploying a static webpage using Docker and Docker Compose, first on a local environment and then replicating the exact setup on a Cloud Virtual Machine.

## Project Structure
- `index.html`: A static HTML page displaying a custom welcome message.
- `docker-compose.yml`: Configuration file spinning up an Nginx container, mounting the local HTML file, and mapping ports.

## How to Run Locally
1. Ensure Docker Desktop is running on your machine.
2. Clone the repository and navigate into the directory.
3. Run the following command:
   ```bash
   docker compose up -d
4. Access the webpage via http://localhost:8080
