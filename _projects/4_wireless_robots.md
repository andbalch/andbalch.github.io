---
title: "Wirelessly-Powered Autonomous Warehouse Robots"
excerpt: "For my junior research project at the Governor's School, I designed and built a platform for warehouse robotics (like those used by Amazon) that were powered through wireless induction. Everything I did in this project, from programming and cloud infrastructure to computer-aided design and manufacture, was entirely self-taught. It placed first at the Tidewater Science and Engineering Fair and was accepted to the International Science Fair, but this was canceled due to COVID. Click the link for more details, or check out my <a href='https://www.andrewbalch.com/paper/2020-02-08-junior-research'>writeup</a>!<br/><img src='/images/projects/bot_testing.png' width='50%' height='50%'>"
collection: projects
---

For my junior research project at the Governor's School, I designed and built a platform for warehouse robotics (like those used by Amazon) that were powered through wireless induction. Everything I did in this project, from programming and cloud infrastructure to computer-aided design and manufacture, was entirely self-taught. It placed first at the Tidewater Science and Engineering Fair and was accepted to the International Science Fair, but this was canceled due to COVID.

Project backboard:  
<embed src="/files/robot_backboard.pdf" width="500" height="375" type="application/pdf">
<br/>

The robot was capable of lifting and moving a few hundred pounds, which required a lot of well-designed parts to hold it all together.  
<img src='/images/projects/robot_front.jpg'>

This is the technical drawing for one of the many parts I CAD'ed: a bracket for the worm drive motors.
<img src='/images/projects/motor_bracket.png'>

A matrix of induction tiles powered the robot as it moved across the mock warehouse floor.  
<img src='/images/projects/induction_tiles.jpg'>

Of course, it couldn't drive right on the wiring, so I had to build a false floor to protect the induction coils.  
<img src='/images/projects/floor_tile.jpg'>

A relay array determined when each tile would receive power. These were controlled by an Arduino microcontroller connected to AWS IoT. It communicated with Java code running in the cloud that planned out pick and place locations for each of up to 3 robots, estimated the exact time each tile would be occupied by a bot, and dynamically ran a pathfinding algorithm to avoid fallen products and other robots.  
<img src='/images/projects/relay_array.png'>

In the end, I was never able to get the induction coils to work reliably. Induction requires that the two coils have identical capacitance and that the electricity going through the 'transmitting' coil oscilates at a specific frequency. These two factors were likely beyond something I could achieve by hand. What I ended up doing was using the algorithm I wrote to simulate a set of jobs executed by induction and battery-powered robots, and compared their efficiency. Check out my written report on this project [here](https://www.andrewbalch.com/paper/2020-02-08-junior-research)!
