## Jupyterhub Docker Fork

Build a Docker image from Dockerfile
``` bash
sudo docker build -t agaton/jupyterhub .
```

Run Docker container
``` bash
sudo docker run -p 8000:8000 agaton/jupyterhub
```

SSH into container
``` bash
sudo docker exec -it <CONTAINER_ID> bash
```

Add user credentials to container
``` bash
adduser username
```

Login with the provided credentials