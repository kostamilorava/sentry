## Instructions

1. Generate secret key:
    ```
    docker run --rm sentry config generate-secret-key
    ```
   
2. Run docker compose:

    ```shell
    docker-compose up -d
    ```

3. Run migrations/setup:
   ```shell
   docker-compose run --rm web upgrade
   ```
