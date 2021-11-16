# airflow-compose
A deployment of Apache Airflow using docker-compose.  

## References:
+ Original [docker-compose airflow](https://github.com/apache/airflow/blob/main/docs/apache-airflow/start/docker-compose.yaml): an example not intended for production
+ [Explanation](https://github.com/apache/airflow/blob/main/docs/apache-airflow/start/docker.rst) of example above

## Running the example:

1. Clore repository
2. Create the following directories in the same directory of `docker-compose.yml`: `dags`, `logs`, `plugins`
3. Change permision for the directories: `chmod -R 777 dags/ logs/ plugins/`
4. Run: `docker-compose up airflow-init`
5. Run: `docker-compose up`
6. The web-gui should be available in `http://localhost:8080`

