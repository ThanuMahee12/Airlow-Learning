# Apache Airflow Learning
![AirflowLogo](/asserts/docs/AirflowLogo.png)

## Overview
Apache Airflow is an open-source platform for developing, scheduling, and monitoring batch-oriented workflows. Airflow’s extensible Python framework enables you to build workflows connecting with virtually any technology. A web-based UI helps you visualize, manage, and debug your workflows. You can run Airflow in a variety of configurations  from a single process on your laptop to a distributed system capable of handling massive workloads.
## Prerequisites
### Running on Windows
 - Docker
 - Python
## Steps
- Build Docker image:
   ```bash
   docker build --pull --rm -f 'DockerFile' -t 'learn-airflow:latest' '.'
   ```
- Build Docker Compose
  ```bash 
  docker compose -f 'Docker-Compose.yml' up -d --build 
  ```
- web ui is scussfully open `http://localhost:8080/`
  password can see in `C:\Users\thanu\Downloads\Airlow-Learning\.airflow\simple_auth_manager_passwords.json.generated`
  
  ![webUi](/asserts/docs/AirflowWebui.png)
## Resources

- [YouTube Playlist: Apache Airflow Tutorials](https://youtube.com/playlist?list=PLc2EZr8W2QIAI0cS1nZGNxoLzppb7XbqM&si=Whc3yNa4Co_XwXC4)
- [Apache Airflow Official Page](https://airflow.apache.org/)
- [Docker Official Page](https://www.docker.com/)