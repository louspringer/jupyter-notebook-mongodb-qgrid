# jupyter-notebook-mongodb-qgrid
Dockerfile for datascience notebook based on jupyter/datascience-notebook with openpyxl, qgrid and pymongo added.

# Mount Host Filesystem
```bash
docker run -it --rm -p 8888:8888 -v `pwd`:/home/jovyan/work louspringer/jupyter-notebook-mongodb-qgrid:latest
```
Mounts the current working directory to /home/jovyan/work in the container. The container will be able to retrieve and save notebooks to this directory. 
