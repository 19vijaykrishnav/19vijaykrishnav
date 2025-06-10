Hello World

This is the README.md file for the NEW accout. It will detail all information from the start of the assignment so that I can document the steps that lead to the completed project.
Documented chronologically but not consistently.

Notes:
    #Define the problem/investigation
    #Research other solutions to solve the problem - the main research is going to be in figuring out how to interact with hardware and choosing which programming language to use.
    #Define the user requirements - This needs to come through dialogue with an end user. arrange an interview/ questionnaire / email exchange
    #Explain the proposed solution
    #Identify the SMART objectives - Numbered and specific (This is your success criteria)
    #Model the solution
    #Identify acceptable limitations

IDEAS:
- Music quality enhancer using AI
- Simulator that uses sound to map areas (echolocation)
- Robotic arm that catches different objects in different ways (simulated first and then coded for an actual hand if possible)
The project is to program a robotic arm that can catch a ball thrown in a general area. The program first identifies the ball, plots its trajectory, predicts its virtual position inside the area parameter and finally intercepts the ball to catch it. 

To start the project I need to program the code to identify tennis balls and model a state chart program. 
State charts are advanced state machines which can model two or more states parallely to create a new state in effect. I will have to learn how to code one and consider.

Step 1 : Identify the ball - we use AI for this. Plot a vector map of different objects and identify new objects by obtaining characteristics that most closely resemble the object. 
Step 2 : Predict its movement - we first plot its trajectory as a generalised function so that we can estimate the maximum height, range and time of interception. We also need to determine its exact position in three dimension space. Hypothetically, a few frames of recorded positional data are sufficient in order to predict its movement, provided that that the entire TIME of flight is known or recorded, but I must test the validity of this statement. Additionally, the way the object is handled is also important to the task, as an egg should be caught differently when compared to a rugby ball. 
Step 3 : Program the appendage to intercept the ball - This part of the project can be simply hypothetical. I don't think I would have time to learn a new language to code the movement and interacting with hardware might be hard as it is not easily documentable. It can be simulated. 

BONUS Steps : - swat the ball away
              - intercept the ball with another ball
              - catch and then throw (this will involve training the program to identify hands or people) back to the person

Identifying resources : 
- The project is going to be pursued as a simulation rather than actual coding for a robot
- Godot could be used due to the State Chart modules
- I will have to learn State Charts and my knowledge on godot scripts is limited as of right now
- However, I want to code my own state charts because I think this will be a good learning experience and partly because using game engines allow too much leeway in terms of challenge and limit how much I take away from this project.
- Additionally, I think I should also code the object identifier myself, so that any camera can be used.

What to do :
Identify which IDE and language to use
- How to organize the code
Design the robot arm
Model it in 3D
- Code the AI to identify objects being thrown by assigining attributes and functions to each object. Each element in the vector map could act as a class, where methods and characteristics can be pulled from to take decisions. 
- Code state charts
- Code the maths behind the object moving
- Code the robot arm using state charts

Report structure:
- Introduction
- Contents
- Written report
- Code screenshots
- Conclusion and Application potential
- Resources used and sources

