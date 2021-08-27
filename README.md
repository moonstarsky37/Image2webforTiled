# Image2webforTiled
It just my note for the automation code from a list of image from a folder convert to model and show on web


## Source image infomation
* Numbers: 177
* EXIF: Has GPS and camera info.

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
- [ ] Create a GUI for this.

### Module 2:
- [x] Create an Cesium web server for demo.
- [x] Export tiled model from projects with user defined path. (from  module 1)
- [ ] Let user defined web title and html filename can use in regular expression
- [x] Auto create new page with user definded name and convert tiled model to cesium server.
- [ ] Create a GUI for this.
