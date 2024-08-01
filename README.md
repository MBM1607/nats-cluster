# NATS Cluster

This repository contains the necessary files to create a NATS cluster (3 nodes) using Docker
Compose with custom configuration files.

## Requirements

- Docker
- Docker Compose

## Usage

You need to add a .env file with the same variables as the `.env.template` file.

There is a helpful script `start` that will automatically prompt you for the necessary variables
on first run.

```bash
./start
```
