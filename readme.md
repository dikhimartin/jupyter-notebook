## jupyter-datascience-notebook 

The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text. Its uses include data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.


### How to start services
``` shell
docker-compose up -d
```

### How to stop services
``` shell
docker-compose stop
```

### Server running on
```shell
http://127.0.0.1:8888/?token=token_access
```

### How to get token
```shell
docker-compose logs
```
### Docker shell description
```shell
To access the notebook, open this file in a browser:
datascience-notebook-container |         file:///home/jovyan/.local/share/jupyter/runtime/nbserver-6-open.html
datascience-notebook-container |     Or copy and paste one of these URLs:
datascience-notebook-container |         http://5c4c2932b353:8888/?token=5edd7c9cc9699df9b09bc6e5ec00102ca1ec1c22deaab087
datascience-notebook-container |      or http://127.0.0.1:8888/?token=5edd7c9cc9699df9b09bc6e5ec00102ca1ec1c22deaab087
```
### line of token
http://127.0.0.1:8888/?token=5edd7c9cc9699df9b09bc6e5ec00102ca1ec1c22deaab087


### References
- [jupyter] (https://jupyter.org/)
- [docker.jupyter/datascience-notebook] (https://hub.docker.com/r/jupyter/datascience-notebook/)

### Developed By
- Dikhi Martin

### Lisence
- MIT