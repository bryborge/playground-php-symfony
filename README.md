# PHP Symfony Playground

## Prerequisites

*   Docker
*   Docker Compose
*   Symfony CLi

## Up and Running

1.  Clone the repo.
1.  Copy and tweak .env configuration for your needs.

    ```sh
    cp .env.example .env
    ```

1.  Create your project.

    ```sh
    symfony new src
    ```

1.  Run Compose

    ```sh
    docker-compose up
    ```

1.  Access your project at `localhost:8080`.
