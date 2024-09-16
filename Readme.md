# portainer with Docker Compose

This repository contains a Docker Compose configuration to set up portainer containers.

## Prerequisites

- Docker: Make sure you have Docker installed on your system. You can download and install Docker from [here](https://www.docker.com/get-started).
- Or:
```
curl -fsSL https://get.docker.com -o get-docker.sh
```
```
sudo sh get-docker.sh
```
## Usage

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/laochris/DC-mysql-phpmyadmin
    ```

2. Navigate into the cloned directory.

    ```bash
    cd DC-mysql-phpmyadmin
    ```

3. Modify the `docker-compose.yml` file to customize ports, volumes.

4. Execute the following command to start the containers.

    ```bash
    docker-compose up -d
    ```


6. After you're done, you can stop and remove the containers by executing:

    ```bash
    docker-compose down
    ```

    This will stop and remove both containers.


