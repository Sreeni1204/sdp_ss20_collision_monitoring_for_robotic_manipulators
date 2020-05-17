# sdp_ss20_collision_monitoring_for_robotic_manipulators
## Members:
- Alan Gomez
- Samuel Parra
- Brennan Penfold

## References
This library is an implementation of the following papers:

* Real-Time Obstacle Avoidance for Manipulators and Mobile Robots, Oussama Khatib, 1986.
* Biologically-inspired dynamical systems for movement generation: automatic real-time goal adaptation and obstacle avoidance, H. Hoffmann et al., 2019.


## Requirements:
- KDL (https://www.orocos.org/kdl/installation-manual)
- Eigen (http://eigen.tuxfamily.org)
- CMAKE V3.5


## Building
In the root folder create a build folder:
``` ...\sdp_ss20_collision_monitoring_for_robotic_manipulators> mkdir build```
CD into the build folder and run cmake for the first time to configure the build environment:
```
    ...\sdp_ss20_collision_monitoring_for_robotic_manipulators$ cd build
    ...\sdp_ss20_collision_monitoring_for_robotic_manipulators\build$ cmake ..
```
If VS Code is being used the CMAKE Tools extension is helpful as it allows the library to be
built by pressing F7.

Otherwise the following commands need to be run from the build folder:
```
    ...\sdp_ss20_collision_monitoring_for_robotic_manipulators\build$ cmake ..
    ...\sdp_ss20_collision_monitoring_for_robotic_manipulators\build$ cmake --build .
```

## Execution
The executable file compiles as /build/collision_monitoring
