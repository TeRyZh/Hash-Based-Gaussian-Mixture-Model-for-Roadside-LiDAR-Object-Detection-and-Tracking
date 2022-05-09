# Gaussian-Mixture-Model-for-Roadside-LiDAR-Object-Detection-and-Tracking
Multimodal Gaussian Mixture Model for Realtime Roadside LiDAR Object Detection -- Under Review


### Fig.1 LiDAR Detected Trajectory

![LiDAR Detected Trajectory vs Video Detected Trajectory](https://github.com/TeRyZh/Gaussian-Mixture-Model-for-Roadside-LiDAR-Object-Detection-and-Tracking/blob/main/Images/Trajectories.png)

### Fig.2 Pre-Trained Bakcground Overlayed with Segmented Foreground Points. In this figure, only the foreground objects are updated. The background infrastructure points are considered as stationary components.

<img align="center" width="80%" src="https://github.com/TeRyZh/Gaussian-Mixture-Model-for-Roadside-LiDAR-Object-Detection-and-Tracking/blob/main/Images/Segment%20Animation.gif">

### Fig.3 GMM Model Detection Under Snowy Weather. The snowfalls cause phatom reflections with irregular and random position as displayed in the figure. 
<img align="center" width="80%" src="https://github.com/TeRyZh/Gaussian-Mixture-Model-for-Roadside-LiDAR-Object-Detection-and-Tracking/blob/main/Images/GMM_FrenchJoyce_animation.gif">

### Fig.4 GMM Model Detection Under Occulusions. Redlight phases usually have more severe occulusions than greenlight phases.
<img align="center" width="80%" src="https://github.com/TeRyZh/Gaussian-Mixture-Model-for-Roadside-LiDAR-Object-Detection-and-Tracking/blob/main/Images/GMM_GeorgeAlbany_animation.gif">

### Fig.5 GMM Model Running in RealTime. The bakcground points are getting fewer and fewer when the GMM fully captured the background modes. 
<img align="center" width="80%" src="https://github.com/TeRyZh/Gaussian-Mixture-Model-for-Roadside-LiDAR-Object-Detection-and-Tracking/blob/main/Images/RealTimeSegmentation.gif">
