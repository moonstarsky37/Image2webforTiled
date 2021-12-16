# Image2webforTiled
Automation code from a list of image from a folder convert to model and show on web with 3D tile model.

## Source image infomation
* Numbers: 177
* EXIF: Has GPS and camera info.
### Hardware info.
* GPU: Nvidia GTX 1060 6GB
* CPU: Intel i7-8700
* RAM: 64GB

### Execute time
* Adding photos time: 0.43 sec
* Aligning photos time: 247.57 sec
* Building Depth Maps time: 292.87 sec
* Building DenseCloud time: 541.71 sec
* Building TiledModel time: 1456.68 sec
* Creating Web time: 22.50 sec
Total: 43 min
## Current results
https://imgur.com/MYhKF3m
![https://imgur.com/MYhKF3m](https://user-images.githubusercontent.com/9031339/131091962-368732c4-1172-4964-92aa-2d0bda6cea1d.gif)
![](https://i.imgur.com/KZRcqvI.jpg)![](https://i.imgur.com/kJF3jEH.jpg)


## Procedure
### Module 1:
- [x] Argument parse for user define image path.
- [x] Aligning images with tie points.
- [x] Auto calibrate camera.
- [x] Build dense point cloud, depth maps in scripts
- [x] Build mesh, tiled model and save as a projects in local
- [x] Create a GUI for this.

### Module 2:
- [x] Create an Cesium web server for demo.
- [x] Export tiled model from projects with user defined path. (from  module 1)
- [x] Let user defined web title and html filename can use in regular expression
- [x] Auto create new page with user definded name and convert tiled model to cesium server.
- [] Create a GUI for this.
