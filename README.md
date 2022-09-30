# demo_TelloEDU


## Prepration 

1. pick the 3 Tello EDUs that are marked by `E1`,`E2`,`E3`, and place them in a circular shape, as pictured, around the T-zone of the flight area. xyz aligned with XYZ.

2. make sure the Tello EDUs, `E1`,`E2`,`E3`, are defined in the VICON Tracker as objects respectively named ``EDU_1``, ``EDU_2``, ``EDU_3``. Also make sure the ``AUTO ENABLE`` and ``TRACK`` are activated.

3. open a terminal and run 

 ```
  source telloswarm_ws/devel/setup.bash
 ```
 
then run
 
 ```
 roslaunch vicon_bridge vicon.launch
 ```
 
 which gives VICON data 
 
 
 
 ### run tests
 
 0. assumming ``roslaunch vicon_bridge vicon.launch`` from is running.
 
 1. open a terminal and run
 
 ```
 python3 telloswarm_ws/src/TelloSwarm/scripts/demo_circle_EDU.py
 ```
 
