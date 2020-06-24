

The `install` file will install all the files you need to build an autonomous robot including:
- Teensy Firmware
- Sensor Driver
- Navigation Stack

You need to pass two arguments to the install file, where:
```
$ ./install <base> <sensor>
```

##### base 
The type of robot you want to build. Valid arguments are 
- 2wd
- 4wd
- ackermann
- mecanum

##### sensor 
The lidar you're going to use for your build. Valid arguments are 
- xv11
- rplidar
- ydlidar
- hokuyo
- kinect
- realsense


