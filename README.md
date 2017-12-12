# jupyter-notebook-mongodb-qgrid
Dockerfile for datascience notebook based on jupyter/datascience-notebook with openpyxl, qgrid and pymongo added.

# running locally
docker run -it --rm -p 8888:8888 -v `pwd`:/home/jovyan/work louspringer/jupyter-notebook-mongodb-qgrid:latest
