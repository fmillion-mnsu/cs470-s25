# Fitts' Law Project

## Overview

For this project, you will write a simple program to test *[Fitts' Law](https://lawsofux.com/fittss-law/)*. In this experiment, you will measure how fast a user can point to and click on random circles shown on the screen while using a mouse or a trackpad.

## Instructions

* Design an experimental protocol to run your study. Determine when and where the experiment will take place, who your participants will be and what your participants will be doing during the experiment.  
* Recruit 10 participants for this test with similar computer usage abilities. Participants must be 18 years or older.
* At the same time, write the code to implement the experiment. Test your code thoroughly! (You don’t want a crash mid-experiment…)

## Program requirements

* Present participants with a welcome screen which includes an **informed consent** electronic statement. Have participants agree (and record their choice) before beginning the experiment. This can be done with a button on the screen that says “I agree” or any other method you indicate that requires user interaction to agree.

* For each trial, you will present a circle of one of three diameters on screen, which will be located one of 3 distances initial position of the cursor, in one of 2 directions (left or right). At the start of each trial, the cursor should be at the center of the screen. and consider two directions (left, right). This yields a total of 18 possible tests (3 sizes * 3 distances * 2 directions).

* Each individual trial involves having the participant click on the circle as fast as they can. For each trial, the cursor must begin at the **center** of the screen. After repositioning the cursor, the user would then move the cursor towards a circle and click on the circle.

    > Depending on the language you use to code this experiment, you can either force the mouse pointer back to the center of the screen at the start of each test, or if that is not possible, you can require the user to *click* a "Next" button which is at the center of the screen, thus placing the cursor back at the start by virtue of the participant clicking the button.

* You will present each possible configuration a total of 10 times. There will be a total of 180 trials in each experiment run. You should present the trials completely randomly. 

* The software must calculate the time to complete each task, the actual distance travelled for each task and the errors in each task. Errors are instances where the user did not click inside of the circle. Each trial should run until the user successfully clicks inside the circle.

* The program must provide feedback to the user when a task is completed and presents a completion screen at the end of the test. The program must also provide a way to terminate the test early.

* For each trial, the program should record:
    * The setup of the trial (circle size, distance, direction)
    * The time taken from when the trial began to when the user successfully clicked the mouse.
    * The distance the mouse traveled (you can calculate this as pixels)
    * How many errors (if any) the user caused before clicking successfully

## Deliverables

1. Write a report describing your experimental findings.

    Your report should contain:
    
    * A description of your protocol including the independent and dependent variables and the possible confounding variables in your setting, 
    * An explanation of the results obtained from linear regression using Fitts’ Law. 
    * Answer the following questions: 
        * What difference does it make if tasks are performed in different directions?
        * What differences did you observe between participants with respect to error rates, time completions and distance travelled per task?
    * A discussion of any problems you encountered during the experiment and potential limitations to the experiment.

2. The code used for your experiment.
