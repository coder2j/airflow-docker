# Apache Airflow  Tutorial Series [YouTube](https://www.youtube.com/watch?v=z7xyNOF8tak&list=PLwFJcsJ61oujAqYpMp1kdUBcPG0sE0QMT)
## Updated Tutorial Episode
1. [Introduction and Local Installation](https://youtu.be/z7xyNOF8tak)
2. [Get Airflow running in Docker](https://youtu.be/J6azvFhndLg)
3. [Airflow Core Concepts in 5 mins](https://youtu.be/mtJHMdoi_Gg)
4. [Airflow Task Lifecycle and Basic Architecture](https://youtu.be/UFsCvWjQT4w)
5. [Airflow DAG with BashOperator](https://youtu.be/CLkzXrjrFKg)
6. [Airflow DAG with PythonOperator and XComs](https://youtu.be/IumQX-mm20Y)
7. [Airflow TaskFlow API](https://youtu.be/9y0mqWsok_4)
8. [Airflow Catchup and Backfill](https://youtu.be/OXOiUeHOQ-0)
9. [Schedule Airflow DAG with Cron Expression](https://youtu.be/tpuovQFUByk)
10. [Airflow Connection and PostgresOperator](https://youtu.be/S1eapG6gjLU)
11. [Add Python Dependencies via Airflow Docker Image Extending and Customizing](https://youtu.be/0UepvC9X4HY)
12. [AWS S3 Key Sensor Operator](https://youtu.be/vuxrhipJMCk)

## Running apache airflow 2.0 in docker with local executor.
Here are the steps to take to get airflow 2.0 running with docker on your machine. 
1. Clone this repo
1. Create dags, logs and plugins folder inside the project directory
```bash
mkdir ./dags ./logs ./plugins
```
1. Install docker desktop application if you don't have docker running on your machine
- [Download Docker Desktop Application for Mac OS](https://hub.docker.com/editions/community/docker-ce-desktop-mac)
- [Download Docker Desktop Application for Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows)
1. Launch airflow by docker-compose
```bash
docker-compose up -d
```
1. Check the running containers
```bash
docker ps
```
1. Open browser and type http://0.0.0.0:800 to launch the airflow webserver

![](images/screenshot_airflow_docker.png)