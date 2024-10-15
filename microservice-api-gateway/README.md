
# Microservice API Gateway

## Overview ##
This project demonstrates a microservice architecture using Flask, with rate limiting, JWT-based authentication, and an API gateway that communicates with multiple services.

## Features ##
- JWT-based authentication for secured access.
- Rate limiting to prevent abuse of API resources.
- API Gateway that routes to `user`, `review`, and `business` microservices.

## Setup ##

### Requirements ##
- Python 3.x
- Flask
- Requests
- Flask-Limiter
- PyJWT
- Python-dotenv

### Installation ##

1. Clone the repository:
   ```bash
   git clone https://github.com/Sebabo7/backend-microservices.git
   cd microservice-api-gateway
