# docker-larvio-playground
A VNC docker image for playing with [LARVIO](https://github.com/PetWorm/LARVIO). `Ubuntu Bionic` and `ROS Melodic`.

## Play with LARVIO
Build the image. 
```
docker build -t larvio_vnc_bionic /YOU_PATH_TO_THIS_REPO
```
Download LARVIO and dataset. Load LARVIO and dataset when running container. An example is given in `run.sh`.

Open VNC Viewer and visit `127.0.0.1:5900` to monitor the desktop.