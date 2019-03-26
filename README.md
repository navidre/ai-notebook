# Running Dockerfile Locally
Please follow the following steps to work with the Jupyter Notebook locally on your machine. Please replace "navidre" with your own DockerHub username.

1. Building the local Dockerfile: 

```
docker build -t navidre/ai-notebook .
```

2. Running the local Docker of Jupyter Notebook:

```
docker run -it --rm -p 8888:8888 -t navidre/ai-notebook
```

Please follow the instructions printed and paste the address of the Jupyter Notebook in a browser to start.

# (Optional) Shipping image to DockerHub
In case you made any changes and wanted to ship the new image to DockerHub, type the following command in terminal (Change "navidre" to your own DockerHub username):

# (Optional) 

