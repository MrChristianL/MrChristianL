## Hey there 👋 My name is Christian

<br/><br/>

<!-- ABOUT THE PROJECT -->
### Meet Walter - My First Robot
<img src="https://github.com/MrChristianL/MrChristianL/blob/main/images/Walter.jpg" width="600">

### WalTER - The Wall Tracking Extraction Rover
Walter was first thought of as a minimalistic approach to providing a robot capable of searching enclosed areas, such as caves, with an emphasis on search and rescue efforts. With a limited budget and timeframe, Walter was boiled down to the core tenets necessary to make progress toward this goal.
<br/><br/>
Instead of a cave, Walter uses a 5x5 maze as the enclosed area for this instance. Being my first venture into robotics and search algorithms, Walter employed the Left Hand Rule (LHR) method of exploring and solving the maze to make use of the limited storage available on the Arduino. The single ultrasonic sensor fastened to the front of the robot allows Walter to detect the presense of walls within the maze, and then respond accordingly. Walter *does not* memorize the maze environment. The robot's memory is wiped before each trial, remembering a new set of obstacles that need to be drawn each time. 

### Walter Solving The Maze Using LHR and Ultrasonic Sensors
<img src="https://github.com/MrChristianL/MrChristianL/blob/main/images/Solving.gif" width="500">

Note that the robot also makes small corrections to its placement within the maze to effectively execute turns and maneuver the maze. This is due to Walter's relative size within the maze, requiring a high level of precision when determining Walter's next actions within the maze. Walter's best efforts to correct his position to nearby obstacles presents itself in a sort of wiggle-type movement of microcorrections. 

## The Goal of Walter
Rather than having the goal of making it from start to finish, the main focus of the project was to have Walter be able to traverse the maze, remembering every obstacle encountered throughout the journey, and then be able to draw the layout of the maze from memory after completion. Though Walter had a definitive start and end position for the sake of this project, Walter was capable of navigate throughout the environment when placed anywhere.

### 2D Re-Creation of Maze Environment
<img src="https://github.com/MrChristianL/MrChristianL/blob/main/images/Drawing.gif" width="350">
Though the programming of Walter employs C++, the drawing of the obstacles as seen above occurs in Processing, utilizing the Arduino's onboard EEPROM functionality to recall the location of each obstacle in an array-like fashion. This memory would be purged each time, allowing Walter to start from scratch with each subsequent run of the maze.
<br/><br/>

## My Progression of Robotics
Since attending the University of Michigan, I've worked on a couple of additional robots. I worked on another robot similar to Walter that also had to navigate a maze environment. This robot, effectionately named CarL (get it.. because he's a car... not my best, I'll admit). CarL utilized more advanced algorithms and sensors to do a similar job. It was a great first step in advancing my robotics knowledge. After CarL came Louis, a 6DOF robotic arm that taught me much about kinematics and provided a brief introduction into computer vision.

<img src="https://github.com/MrChristianL/MrChristianL/blob/main/images/Mbot.png" width="303"> <img src="https://github.com/MrChristianL/MrChristianL/blob/main/images/Armlab.png" width="300">

These two robots opened my eyes to many of the flaws and mistakes I made when I worked on Walter by myself. For comparision, what took me roughly two years to complete with Walter took only about six weeks on CarL.

## Computational Neuroscience

To date, my crowning achievement in the field of Computational Neuroscience has been implementing a remedial version of a Bhadra-Kilgore block on a Deep Root Ganglion Neuron in an attempt to create a non-opioid solution to chronic pain.

<img src="https://github.com/MrChristianL/MrChristianL/blob/main/images/BK_Functional.png" width="350">

I performed additional research under Dr. Cindy Chestek at U-M's Cortical Neural Prosthetics Lab.

<!-- CONTACT -->
E-Mail:   <img align="left" alt="Christian Leonard | LinkedIn" width="40px" src="https://github.com/MrChristianL/MrChristianL/blob/main/images/logo-gmail-png-file-gmail-icon-svg-wikimedia-commons-0.png" /> mrchristianleonard@gmail.com

LinkedIn: <img align="left" alt="Christian Leonard | LinkedIn" width="60px" src="https://github.com/MrChristianL/MrChristianL/blob/main/images/Linkedin-logo.png" /> [/in/christian-leonard]

## To hear what Mars sounded like on my 23rd birthday, click the link below! 
(Courtesy of NASA and the amazing folks at the JPL)
- Thanks to the Perseverance Rover, I was lucky enough to find this audio clip taken from the surface of Mars that just so happens to have been recorded on Feb 20th, 2021 -- my 23rd birthday! 
- [Mars Audio - Perseverance Rover]


<!-- MARKDOWN LINKS AND IMAGES -->
[linkedin-shield]: https://github.com/MrChristianL/MrChristianL/blob/main/Linkedin-logo.png
[/in/christian-leonard]: https://www.linkedin.com/in/christian-leonard/
[mrchristianleonard@gmial.com]: mrchristianleonard@gmail.com
[Mars Audio - Perseverance Rover]:https://mars.nasa.gov/resources/25629/nasas-perseverance-rover-microphone-captures-sounds-from-mars/?utm_source=iContact&utm_medium=email&utm_campaign=nasa-mars&utm_content=20210301+-+Mars+Newsletter
