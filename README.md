# jupyterlab-dotnet

For building image use: docker build . -t "IMAGE_NAME"

To run container use: docker run -p 10000:8888 -e JUPYTER_ENABLE_LAB=yes --name CONTAINER_NAME -d -v LOCAL_PATH:/home/jovyan/work IMAGE_NAME
