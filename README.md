# Purpose

- This repo was forked from <https://github.com/robopeak/rplidar_ros>
- Its purpose is to provide an option for user to rotate the lidar in laser frame. So the lidar can be mounted rotated in horizontal direction.

## Details
- Added option "rotated".
```
  <param name="rotated"    type="bool"   value="true"/>
```

- By default "rotated" is set to false. The lidar needs to be mounted as what the manufacturer suggested. See below picture.

![rplidar A1](https://raw.githubusercontent.com/1plus-1/rplidar_ros/master/rplidar_A1.png)

- When "rotated" set to true. The orientation between laser frame and lidar is like this.

![rplidar A1 Rotated](https://raw.githubusercontent.com/1plus-1/rplidar_ros/master/rplidar_A1_rotated.png)
