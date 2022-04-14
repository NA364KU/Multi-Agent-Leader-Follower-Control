# Multi Agent Leader Follower Control
Uses a modification of the boids flocking rules to enable user control for flock/multi-agent navigation. Here a leader-follower structure is presented which allows the user to provide overall navigation of the "flock" and acts as a virtual leader. 

This is different from regular boids which steer towards the center of mass (known as "cohesion") but rather steers towards the user's desired position.

The code uses a modified version of a boids flocking implementatoin by Daniel Shiffman https://processing.org/examples/flocking.html

# How to Use
Prerequisites: The code is written in Processing3, which can be downloaded here https://processing.org/download

Open and run the main file, then point the mouse to the desired position in the window. The boids will steer/flock towards that point while trying to avoid each other and maintaining a formation.

<img width="534" alt="leader_control" src="https://user-images.githubusercontent.com/95622570/163322734-53114e66-aa8f-482b-bb0c-63414ebd647b.png">
