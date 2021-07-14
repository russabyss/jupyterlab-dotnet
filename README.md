# jupyterlab-dotnet

Repo contains Dockerfile for building JupyterLab image with preinstalled [dotnet interactive](https://github.com/dotnet/interactive) on dotnet 5.0 with C#, F# and PowerShell kernels.
Also contains: python3, R and Julia kernels.

![image](https://user-images.githubusercontent.com/35697797/125592907-0f8e48c8-aeb7-4c85-8da6-08c0edae2649.png)


For building image use: `docker build . -t "IMAGE_NAME"`

To run container use: `docker run -p 10000:8888 -e JUPYTER_ENABLE_LAB=yes --name CONTAINER_NAME -d -v LOCAL_PATH:/home/jovyan/work IMAGE_NAME`
