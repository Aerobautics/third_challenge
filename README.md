#third_challenge
This is the third hackathon challenge.

## April Tag Autonomy
This package contains the necessary stuff to launch the RasPiV2 camera on the Jetson Nano, and run the Apriltag software on the resulting video stream.

## Configuration
The configuration for the Apriltag is contained in the 'config' folder. Right now, it is set up for the 'tag16h5' family of apriltags and only the first 5 tags 0 through 4. I highly encourage you to look through as much of the apriltag documentation as possible, but the config files should both be fairly self-explanatory/easy-to-read. One of the most import config items is the size of the tags as you've printed them out. The documentation can be found here: http://wiki.ros.org/apriltag_ros

## Apriltag images
You can find the images for this family here:
https://github.com/AprilRobotics/apriltag-imgs/tree/master/tag16h5
The images are "small" because they only use one pixel per square feature in the tag. In order to make use of the images you will have to scale them up and print them. As a word of caution, a lot of programs such as Microsoft Word or PowerPoint will try to be too helpful and interpolate the image while scaling it up, which is not what you want. I have found GIMP, an open-source image manipulation program, allows you to scale an image up without interpolation.
