# RAG-Docker-Compose

## Setup Instructions

### 1. Cloning the frontend and backend repo's

  First we need to clone both the repos inside our docker-compose folder. To clone the repo's run the following command one by one in the terminal;

  ```bash
  git clone https://github.com/BobbieRule/RAG-Frontend.git
  git clone https://github.com/BobbieRule/RAG-Backend.git
  ```

### 2. Configure Environment For both clone repo's:

  Run the following command in both the cloned folders.

   ```bash
   cp .env.example .env
   ```

   Add values for the environment keys in the .env file.

### 3. Start the docker container
  To start the docker container run the following command

  ```bash
  docker-compose up -d
  ```

  This command will build the docker images and start the docker container. Visit the proper localhost with specified ports to verify the containers.

  To stop the docker container run the following command

  ```bash
  docker-compose down
  ```