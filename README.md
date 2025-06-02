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

The project is to program a robotic arm that can catch a ball thrown in a general area. The program first identifies the ball, plots its trajectory, predicts its virtual position inside the area parameter and finally intercepts the ball to catch it. 

To start the project I need to program the code to identify tennis balls and model a state chart program. 
State charts are advanced state machines which can model two or more states parallely to create a new state in effect. I will have to learn how to code one and consider.

Step 1 : Identify the ball - we can use a HUSKY camera and train it to recognize a ball. This involves taking pictures of the ball in different positions and distances from the camera.
Step 2 : Predict its movement - we first plot its trajectory as a generalised function so that we can estimate the maximum height, range and time of interception. We also need to determine its exact position in three dimension space. Hypothetically, a few frames of recorded positional data are sufficient in order to predict its movement, provided that that the entire TIME of flight is known or recorded. 
Step 3 : Program the appendage to intercept the ball - This part of the project can be simply hypothetical. I don't think I would have time to learn a new language to code the movement and interacting with hardware might be hard as it is not easy documentable.

BONUS Steps : - swat the ball away
              - intercept the ball with another ball
              - catch and then throw (this will involve training the program to identify hands or people) back to the person

