# airflow-docker
## Running apache airflow 2.0 in docker with local executor.
Here are the steps to take to get airflow 2.0 running with docker on your machine. 
1. Clone this repo
2. Create dags, logs and plugins folder inside the project directory
```bash
mkdir ./dags ./logs ./plugins
```
3. Install docker desktop application if you don't have docker running on your machine
- [Download Docker Desktop Application for Mac OS](https://hub.docker.com/editions/community/docker-ce-desktop-mac)
- [Download Docker Desktop Application for Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows)
4. Launch airflow by docker-compose
```bash
docker-compose up -d
```
5. Check the running containers
```bash
docker ps
```
6. Open browser and type http://0.0.0.0:800 to launch the airflow webserver

![](images/screenshot_airflow_docker.png)