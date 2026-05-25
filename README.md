# fluffy-octo-memory
## Introduction
The fluffy-octo-memory project is a Docker-based deployment of ERPNext, a comprehensive enterprise resource planning system. It utilizes Render for cloud hosting and provides a scalable, secure, and efficient solution for managing business operations.
## Key Features
* Dockerized ERPNext application
* MariaDB database for data storage
* Redis caching for improved performance
* Render-based cloud hosting
* Automated environment variable generation
## Tech Stack
* Docker
* ERPNext
* MariaDB
* Redis
* Render
## Installation
1. Clone the repository: `git clone https://github.com/your-username/fluffy-octo-memory.git`
2. Navigate to the project directory: `cd fluffy-octo-memory`
3. Create a Render account and set up a new web service
4. Configure the `render.yaml` file with your Render account details
5. Deploy the application to Render: `render deploy`
## Usage
1. Access the ERPNext application at the Render-provided URL
2. Log in with the administrator credentials (username: `Administrator`, password: `admin123`)
3. Configure the application settings as needed
## Environment Variables
The following environment variables are required:
* `DB_HOST`: the hostname of the MariaDB database
* `REDIS_CACHE`: the hostname and port of the Redis cache
* `DB_PASSWORD`: the password for the MariaDB database (generated automatically by Render)
* `SITE_NAME`: the domain name of the ERPNext application
* `ADMIN_PASSWORD`: the password for the administrator account (default: `admin123`)