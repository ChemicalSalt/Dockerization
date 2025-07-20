# Dockerize a Basic Django Project - RailSathiBE

## Overview

This repository contains a Dockerized version of the RailSathiBE Django project — a backend API for handling rail complaints.  
It includes a PostgreSQL database and the Django app running inside Docker containers via docker-compose.

## Features

- REST API built with FastAPI  
- PostgreSQL DB containerized with Docker  
- Complaint management: create, update, delete complaints  
- Media file upload handling with threading  
- Health check endpoint  
- Modular, scalable design  

## Getting Started

### Prerequisites

- Docker & Docker Compose installed  
- Git installed  

### Access the app

- API docs: [http://localhost:5002/rs_microservice/docs](http://localhost:5002/rs_microservice/docs)  
- Health check: [http://localhost:5002/health](http://localhost:5002/health)  

### How to Run

1. Clone the repository:

```bash
git clone https://github.com/ChemicalSalt/-Dockerize-a-Basic-Django-Project.git
cd -Dockerize-a-Basic-Django-Project
