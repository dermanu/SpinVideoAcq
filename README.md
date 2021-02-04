# VideoAcq: multicamera video acquisition with build-in LSL synchronization
![GUI](https://bitbucket.org/repo/GgRGAK6/images/232279135-gui.png)

## Features
1. Supports any number of cameras as long as they are [OpenCV](https://opencv.org/) compatible.
2. Uses [LSL](https://github.com/sccn/labstreaminglayer) to synchronize the acquired frames opening one LSL outlet per camera.
3. Saves the acquired frames to disk using the Xvid codec.
4. Additional compression can be achieved on Linux systems upon closing the app
by using the [ffmpeg](https://www.ffmpeg.org/) software to automatically convert the files
saved in *.avi* to *.ogv*.


## Authors

This app was created and is maintained by engineers and scientists at [NEATLabs](http://neatlabs.ucsd.edu/index.html), University of California San Diego,
and is part of a wider suite of programs created for supporting closed-loop
brain-machine interfaces for human and animal subjects.
