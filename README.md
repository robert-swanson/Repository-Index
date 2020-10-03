# Robert Swanson Portfolio

This document serves as the collection point for all my Computer Science work.

## [School Portfolio](https://bitbucket.org/rswanson3141/privateportfolio/src/master/) (private repo)

This is a private repository on Bitbucket because it contains answers to homework assignments for many classes and my professors preferred I didn't publicly share them. **To receive access email me at `robert_swanson@taylor.edu` and I will add you as a read-only collaborator.** You must have a BitBucket account  for me to do this.

This repo contains up-to-date examples of my coding style as well as represents the majority of my programming efforts during my college years.

## [JavaFX Chess](https://github.com/robert-swanson/Chess)

<img src="chess.png" alt="chess" align="right" width="300"/> This was a personal project of mine during the summer of 2017. It offers a fully functional chess user interface as well as a customizable chess engine. The interface offered piece animations, board editing (totally not for cheating with a real game of chess), and helpful graphical indicators. The engine implemented the minimax algorithm, which could be customized from a GUI interface to implement alpha-beta pruning, iterative deepening, a killer heuristic, and transposition tables.

*Disclaimer: I wrote this code in high school and it follows no semblance of good coding practice, please look at more recent projects to get a feel for my current coding style.*



## [Java Neural Network](https://github.com/robert-swanson/JavaNeuralNetworkLibrary)

This was a personal project of mine during the summer of 2018. Using only a [YouTube series](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) explaining the math of neural networks, I implemented a neural network library from scratch. It featured customizable network structures, classification using forward propagation, and training using back propagation.

I tested and applied this neural network to the image classification of digits from the [MNIST](http://yann.lecun.com/exdb/mnist/) dataset. After training I was able to achieve slightly over 90% accuracy.

*Disclaimer: Again, I wrote this code in high school and, though it is a little better than JavaFX chess, it is still poorly written code, please look at more recent projects to get a feel for my current coding style.*

## [Neural Network Chess](https://github.com/robert-swanson/NeuralNetworkChess)

This was an attempt to take the JavaFX project, and implement a chess engine that could utilize the Java Neural Network project. I did this on my own as a project for my "Intro to AI" class in 2020. The engine was implemented to still utilize the minimax algorithm, but change the scoring mechanism from one that simply sums point values of pieces to one that feeds the board state to a NN model that can produce a score for that board state. Ultimately, in the time I had, I was not able to see a competent player arise from my training sessions, for future work I'd like to more carefully analyze my training and scoring processes.

*Disclaimer: just combine the two preceding disclaimers*

## [Raspberry Pi Robot](https://github.com/robert-swanson/PiBot)

<img src="pibot.jpeg" alt="pibot" width="300" align="right" /> This was a personal project of mine that I worked on in 2018 that involved creating a robot from 3D printed parts, which was controlled by a Raspberry Pi Zero W. I created an [instructable](https://www.instructables.com/id/3D-Printed-Raspberry-Pi-Zero-Robot/) that describes the creation process and the operation of the robot.

The frame was designed in blender, the robot-side code used *python* and was controlled by an iOS app (written in *Swift*) that served as the remote controller. This app connected to the raspberry pi via a socket to send instructions. It also connected to a service running on the pi that streamed a video signal from the mounted camera. The app could control movement with either a GUI joystick, or with accelerometers.

## [Rideshare Multi-tier Web App](https://github.com/robert-swanson/RideSharePlatform)
<img src="rideshare.png" alt="pibot" width="300" align="right" /> This was a group project for Multi-Tiered Web Design that implemented a model view controller architecture. It was intended to serve as a platform to connect driving students with those who need a ride home.

It used a PostgreSQL database which interfaced with a hapi server using objection and knex. The front end was implemented in Vue and Vuetify.

## [Python Grader](https://repo.cse.taylor.edu/dfletche/python-grader)

This was a project belonging to a couple of upperclassmen that I joined for a few weeks during the summer of 2019. It followed a similar architecture as my ride share project did. I implemented several back-end security features as well as several user interface features.

## [Health Data Analysis](https://github.com/robert-swanson/HealthData)
<img src="health.png" width="300" align="right"/>This was a project I did for Intro to Data science. I took data collected from my Apple Watch over the last few years, exported it, and parsed it with this R script, which then analyzed for correlation between different health characteristics, particularly those relating to quality and quantity of sleep.

## [CLI Time Tracking Service](https://github.com/robert-swanson/TimeTrackingService)

This was a *bash* project I did in 2019 for one of my classes, but was also a tool I used myself to track my time. 

This is a tool to track time usage by starting, ending, and labeling timers. It is designed to be used with Alfred and can provide suggestions formatted as JSON.

## [Address Book IOS App](https://github.com/robert-swanson/AddressBookApp)

This was a *Swift* project I did in 2019 for one of my classes that implemented a *SQLite* database and basic GUI to offer basic contacts tracking functionality.

## [Monopoly Currency Tracking IOS App](https://github.com/robert-swanson/MonopolyPal)

<img src="monopoly.png" alt="monopoly" width="300" align="right" /> This was a personal project I did way back in 2016 when I was first learning *Swift* and iOS development in Xcode. It was intended to be used as replacement for the bank when playing the board game *Monopoly*. It offered a GUI that allowed users to perform actions (eg Pass Go) and it would both show each players balance, and track the history of the game.