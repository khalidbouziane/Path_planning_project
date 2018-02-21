# Path_planning_project

### The Goal of this Project

In this project, the goal is to design a path planner that is able to create smooth, safe paths for the car to follow along a 3 lane highway with traffic. A successful path planner will be able to keep inside its lane, avoid hitting other cars, and pass slower moving traffic all by using localization, sensor fusion, and map data.

### Compilation
The code compile without errors with cmake and make.
A new file was added src/spline.h. It is the Cubic Spline interpolation implementation: a single header file taht we can use  instead of polynomials.

## Valid Trajectories

### The car is able to drive at least 4.32 miles without incident
I ran the simulator for more than 5 miles without incidents

### The car drives according to the speed limit.
No speed limit red message was seen.

### Max Acceleration and Jerk are not Exceeded.
Max jerk red message was not seen.

Car does not have collisions.
No collisions.

### The car stays in its lane, except for the time between changing lanes.
The car stays in its lane most of the time but when it changes lane because of traffic or to return to the center lane.

### The car is able to change lanes
The car change lanes when the there is a slow car in front of it, and it is safe to change lanes (no other cars around) or when it is safe to return the center lane.

Here is a picture of the car driving 20 miles with no incident.

<img src="15_miles.png" alt="sim_pic">
