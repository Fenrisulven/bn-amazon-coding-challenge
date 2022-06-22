# bn-amazon-coding-challenge
Submission for the Bright Network work sample provided via Amazon and their coding challenge

Amazon Coding Challenge
Bright Network Internship, June 2022

# Overview:
Thank you for choosing to take part in Amazon's Coding Challenge for Bright Network. We are very happy to have you here. We hope you have as much fun implementing this challenge as we had creating it!

In this challenge, you are going to implement Amazon's pathfinding algorithm for Amazon's self-driving delivery vehicles. The self-driving vehicle will need to create a path on a 2D-grid that contains a starting point (x,y), a delivery point (x,y) and a number of obstacles. Your vehicle can navigate to any of the adjacent squares (even diagonally), as long as the squares are inbound and do not contain an obstacle.

# General notes:
You can use any language and ideally the output is to a command line.

![image](https://user-images.githubusercontent.com/37941097/175008658-79e1171f-5065-4839-a949-53685e4cfcaf.png)

# Phase 1:
Implement a 10x10 grid that contains a starting point on (0,0), the delivery point on (9,9) and the following obstacles on locations (9,7) (8,7) (6,7) (6,8).

Your algorithm should calculate a valid path avoiding the obstacles and reaching the delivery point.

Your solution sohuld print the path in the format of [(x1,y2), (x2,y2)...] and also the number of steps.

# Phase 2:
Add an additional 20 randomly placed obstacles and print their location using the format [(x1,y1), (x2,y2)...].

The obstacles should not overlap existing ones and should not be places at the start and delivery points.

Your algorithm should calculate a valid path avoiding the obstacles and reaching the delivery point.

Your solution sohuld print the path in the format of [(x1,y2), (x2,y2)...].

# Bonus:
In the event your vehicle is unable to reach its destination, your algorithm should print "Unable to reach delviery point" and identify which obstacles to be removed in order for the vehicle to reach its destination.

Your algorithm should suggest the least amount of obstacles using the format [(x1,y1, (x2,y2)...)] in order for your vehicle to reach its destionation.
