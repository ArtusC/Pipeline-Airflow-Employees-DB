# Pipeline-Airflow-Employees-DB
Pipeline with Airflow, MinIO and MySQL used to simulate a Data Science/Engineer project. 

## For run this project:

1) Make clone/download of the project.

2) Run: `docker-compose up` (put the `-d` if you want to run in detached mode).

         P.S: you need to have the docker installed on your computer.


3) Each of the services will be active (this process can take between 10~15 minutes), being them:

* MinIo (datalake) => localhost:9003
* Airflow (scheduler) => localhost:8081
