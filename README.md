## Hey there 👋 My name is Christian
Welcome to my GitHub! I originally received my bachelor's degree in mathematics, but chose to further pursue robotics after solo-building my first robot, Walter. Walter was built in a time when I had minimal coding experience and absolutely no practice with microcontrollers or sensors of any sort. It taught me so much and showed me the power of building something tangible.

I'm currently pusuing my Master's in Robotics at the University of Michigan (Go Blue!) where I've been exposed to many other types of robots and practices in engineering and computer science. I've found a love for computational neuroscience along the way, and have seen the vast good that neurotechnology can provide to mankind in the future.

Outside of engineering, I've incredibly passionate about entrepreneurship, social impact, stand-up comedy, and film. I appreciate you spending your time with me here on this page! Take care!

### Connect with me on LinkedIn: 
<img align="left" alt="Christian Leonard | LinkedIn" width="60px" src="https://github.com/MrChristianL/MrChristianL/blob/main/images/Linkedin-logo.png" /> [/in/christian-leonard]

### Languages and IDEs I Currently Use Include:

<img align="left" alt="Python" width="60px" src="https://github.com/MrChristianL/MrChristianL/blob/main/images/Python_logo_icon.png" /> <img align="left" alt="Arduino" width="60px" src="https://github.com/MrChristianL/MrChristianL/blob/main/images/arduino-1-logo-png-transparent.png" />   <img align="left" alt="Processing" width="66px" src="https://github.com/MrChristianL/MrChristianL/blob/main/images/180px-Processing_3_logo.png" />  <img align="left" alt="Visual Studio Code" width="60px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" /> <img align="left" alt="Java" width="60px" src="https://github.com/MrChristianL/MrChristianL/blob/main/images/java_logo.jpg" />  <img align="left" alt="C++" width="60px" src="https://github.com/MrChristianL/MrChristianL/blob/main/images/1200px-ISO_C%2B%2B_Logo.svg.png" /> <img align="left" alt="Terminal" width="60px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />

<br/><br/>
<br/><br/>

<!-- ABOUT THE PROJECT -->
## Meet Walter - My First Robot
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

## Computational Neuroscience -- The Personal Weight It Brings
The world of neurotechnology and neural engineering really sort of snuck up on me. I wasn't aware of its existence until coming to U-M, but once I found it, I knew I had to dive straight in. 

During the summer of 2019, several tragedies struck my family. One such tragedy was my parents and me being hit by a drunk driver. The crash left my mom with severe nerve damage and a nearly 100% reduction in range of motion in my mother's left arm from her elbow to her fingers. Neural engineering was the first time I felt hopeful about my mom getting some of her life back. For so long, she had been controlled by pain and has been limited in her capabilities because of what the crash did to her arm -- the freedom it took from her. Now was my chance to better understand, and perhaps even help, with her condition. It was also a unique opportunity to do a bit of that with myself, as well, as I live with epilepsy that is still a relatively new experience to me (thanks again, summer of 2019).

To date, my crowning achievement in the field of Computational Neuroscience has been implementing a remedial version of a Bhadra-Kilgore block on a Deep Root Ganglion Neuron in an attempts to create a non-opioid solution to chronic pain. 

<img src="https://github.com/MrChristianL/MrChristianL/blob/main/images/BK_Functional.png" width="350">

I'm currently performing additional research under Dr. Cindy Chestek at U-M's Cortical Neural Prosthetics Lab.

<!-- CONTACT -->
## For more information regarding the Walter Project
E-Mail:   <img align="left" alt="Christian Leonard | LinkedIn" width="40px" src="https://github.com/MrChristianL/MrChristianL/blob/main/images/logo-gmail-png-file-gmail-icon-svg-wikimedia-commons-0.png" /> mrchristianleonard@gmail.com

Project Repository Link: [Arduino-Maze-Solving-Robot](https://github.com/MrChristianL/Arduino-Maze-Solving-Robot)


## To hear what Mars sounded like on my 23rd birthday, click the link below! 
(Courtesy of NASA and the amazing folks at the JPL)
- Thanks to the Perseverance Rover, I was lucky enough to find this audio clip taken from the surface of Mars that just so happens to have been recorded on Feb 20th, 2021 -- my 23rd birthday! 
- [Mars Audio - Perseverance Rover]


<!-- MARKDOWN LINKS AND IMAGES -->
[linkedin-shield]: https://github.com/MrChristianL/MrChristianL/blob/main/Linkedin-logo.png
[/in/christian-leonard]: https://www.linkedin.com/in/christian-leonard/
[mrchristianleonard@gmial.com]: mrchristianleonard@gmail.com
[Mars Audio - Perseverance Rover]:https://mars.nasa.gov/resources/25629/nasas-perseverance-rover-microphone-captures-sounds-from-mars/?utm_source=iContact&utm_medium=email&utm_campaign=nasa-mars&utm_content=20210301+-+Mars+Newsletter
