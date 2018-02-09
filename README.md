# my_lidar_alarm

An extension to wsnewman's lidar_alarm where multiple pings (51) are being utilized to determine how the robot should move. To view a demonstration of the code, conduct the following commands:

## Example usage_
Start up the STDR simulator:
`roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch`
Start the reactive motion commander node:
 `rosrun my_lidar_alarm my_reactive_commander`
Start the lidar alarm node:
 `rosrun my_lidar_alarm my_lidar_alarm`

Note that my_reactive_commander is the same to wsnewman's except that I changed the yaw_rate slightly.


    
