# docker-larvio-playground
A VNC docker image for playing with [LARVIO](https://github.com/PetWorm/LARVIO). `Ubuntu Bionic` and `ROS Melodic`.

## Play with LARVIO
Build the image if you git clone this repo. 
```
docker build -t larvio_vnc_bionic /YOUR_PATH_TO_THIS_REPO
```
Otherwise you can pull it from dockerhub.
```
docker pull petworm/vnc-larvio-playground
```
Download [LARVIO](https://github.com/PetWorm/LARVIO) and [EuRoC dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets). 

Load LARVIO and dataset when running container. An example is given in `run.sh`.

Open [VNC Viewer](https://www.realvnc.com/en/connect/download/viewer/) and visit `127.0.0.1:5900` to monitor the desktop.