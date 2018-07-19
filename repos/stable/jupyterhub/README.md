# Jupyterhub

[https://jupyterhub.readthedocs.io/en/latest/](JupyterHub), a multi-user Hub, spawns, manages, and proxies multiple instances
of the single-user Jupyter notebook server. JupyterHub can be used to serve
notebooks to a class of students, a corporate data science group, or a
scientific research group.


### Advanced
This application uses the following Dockerfile:
  - [Jupyter Hub Server](https://github.com/Uninett/helm-charts-dockerfiles/tree/0ff1eb6/jupyterhub/server/Dockerfile)
  - [User Notebook Server](https://github.com/Uninett/helm-charts-dockerfiles/tree/0ff1eb6/jupyterhub/singleuser/Dockerfile)