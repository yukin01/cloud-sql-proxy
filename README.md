# cloud-sql-proxy
Cloud SQL Proxy using Docker Compose

https://cloud.google.com/sql/docs/mysql/quickstart-proxy-test  
https://cloud.google.com/sql/docs/mysql/connect-docker

1.  Enable the Cloud SQL Admin API [[ENABLE THE API]](https://console.cloud.google.com/flows/enableapi?apiid=sqladmin&hl=ja&_ga=2.26319933.-1253806915.1536294986)
1.  Create service account with Cloud SQL role
1.  Download private key to `env/service-account-key.json`
1.  Set environment variables to .env file
1.  Check `docker-compose.yml`
    ```
    $ docker-compose config
    ```
1.  Build and run
    ```
    $ docker-compose up
    ```
