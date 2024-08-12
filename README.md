# CV Web Page with Docker

This project demonstrates how to create and serve a simple HTML-based CV using Docker and Nginx.

## Overview

This project uses Docker to containerize a basic web page that displays a CV (Curriculum Vitae). The web page is built with HTML and styled with inline CSS.

## Project Structure

- `index.html`: The HTML file containing the CV content.
- `Dockerfile`: The Dockerfile used to build the Docker image.

## Getting Started

To get started with this project, follow these steps:

### Prerequisites

- Docker: Ensure Docker is installed and running on your machine.

### Building the Docker Image

1. Clone the repository:
   ```sh
   git@github.com:petersameh0/mycv.git
2. Navigate to the project directory:
   ```sh
   cd mycv
3. Build the Docker image: 
   ```sh
   docker build -t cv-webpage .

### Running the Docker Container
1. Run the Docker container:
   ```sh
   docker run -d -p 8080:80 cv-webpage
2. Open your web browser and navigate to http://localhost:8080 to view your CV.

