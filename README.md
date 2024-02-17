# Reddit-Datapipeline-engineering
Reddit Data pipeline Engineering

We are going to integrate Reddit, Airflow, Celery, Postgres, S3, AWS Glue, Athena and RedShift to create seamless ETL process


1. Create venv file
```
python3 -m venv env
source env/bin/activate
```

2. Instll required packages

```
pip install apache-airflow pandas numpy praw
```

```
mkdir config dags data etls logs pipelines tests utils

touch airflow.env docker-compose.yml Dockerfile

pip freeze > requirements.txt

docker compose up -d --build



pip install configparser

pip freeze > requirements.txt

docker compose up -d --build
```


3. install aws cli

4. create new s3 bucket - `reddit_engineering`


```
pip install s3fs
pip freeze > requirements.txt

docker compose up -d --build

```

