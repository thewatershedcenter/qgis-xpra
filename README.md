# qgis-xpra

Ubuntu container with Xpra for running remote desktop applications in browser.

Image is built from NVIDIA Docker image and is compatible with GPUs - need to install additional software.

```
docker run -it -p 9876:9876 tswetnam/qgis-xpra:bionic 
```

#### Run with NVIDIA GPU

```
docker run -it --gpus all -p 9876:9876 tswetnam/qgis-xpra:bionic 
```
