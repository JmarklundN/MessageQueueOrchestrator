# MessageQueueOrchestrator
Repository for orchestrating RabbitMQ with Docker Compose

This repository orchestrates the RabbitMQ server and the `Send` and `Receive` projects.

## Prerequisites
- Docker and Docker Compose installed.

## Services
- RabbitMQ: Message broker for communication.
- Send: Publishes messages to RabbitMQ.
- Receive: Listens and processes messages from RabbitMQ.

## Usage

1. Clone this repository.
2. Run the following command to build and start all services:
   ```bash
   docker-compose up --build


## Setup
1. Install Docker and Docker Compose.
2. Run `docker-compose up` to start RabbitMQ.
3. Access RabbitMQ Management UI at [http://localhost:15672](http://localhost:15672).
