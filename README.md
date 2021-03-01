# Project Overview

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|Day 1| Project Description | Complete
|Day 1| Wireframes / Priority Matrix / Timeline | Complete
|Day 3| Core Application Structure (HTML, CSS, etc.) | Complete
|Day 4| MVP & Bug Fixes | Complete
|Day 5| Final Touches | Complete
|Day 6| Present | Complete;


## Project Description
I want to build an app where a user can create a list of workout goals they want 
to accomplish and keep track of the calories they burn on each workout. 

## Google Sheet

(https://docs.google.com/spreadsheets/d/1X750WkotcCyRoGFR8YHJo0HzSQT3mrpmAqg7guEqEdQ/edit#gid=138749698) 


## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Do not include the actual image and have it render on the page.  

- [Mobile]()
- [Tablet]()
- [Desktop]()

Wireframing Resources:

- [Mockflow](https://mockflow.com/app/#Wireframe)
- [Figma](https://www.figma.com/)


## Time/Priority Matrix 

[Link](https://res.cloudinary.com/jkeohan/image/upload/a_270/v1591621734/project1_matrix_ocy5gc_h1kg0m.jpg)

[My-Link](https://res.cloudinary.com/ds7w3ysag/image/upload/v1608520133/IMG_2494_f9rbsm.jpg)
[Other-Link](https://res.cloudinary.com/ds7w3ysag/image/upload/v1608520146/IMG_2495_ddyt2s.jpg)

Include a full list of features that have been prioritized based on the `Time and Priority` Matix.  This involves drawing a a square.  In the middle of the square, on the x axis draw a line.  The most left part of the line should start with 0hrs and the end of the line should include 2hrs.  This line will be used to estimate how much time any one feature will take to complete. 

Now draw a vertical line on the y axis.  The top of this line should have `High` and the bottom `Low`.  This line will be used to assign a priority to to each feature you wish to include in the project.  

Now create a separate list starting with A and assign it one of the features.  Continue to assign each feature a letter.  Once complete add each letter to the matrix assigning based on what your feel it's prioirty is an how long it will take to implement. If any one feature takes longer than 2hrs to complete than break it down into smaller tasks and reassign them a new letter. 

Once complete tally up the time and determine how long the project will take to complete. Now break those features into MVP and PostMVP so you can guarantee you will have a fully functioning project to demo. 

### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MVP and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP (examples)

- Pull data using google json api
- Render data on page 
- Allow user to choose favorites 
- Save their choices in firebase

#### PostMVP 

- Anything else that is not MVP

## Functional Components

Based on the initial logic defined in the previous sections try and breakdown the logic further into functional components, and by that we mean functions.  Try and capture what logic would need to be defined if the game was broken down into the following categories.

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe.

#### MVP
| Component | Priority | Estimated Time | Actual Time |
| --- | :---: |  :---: | :---: | 
| Ruby/Rails Models | H | 5hr | hr |
| Username/Password | H | 6hr | hr |
| Hello/Start Routines | H | 8hr | hr |  
| Routine Create | L | 8hr|  hr | 
| Workouts/exercises| M | 8hr | hr|
| Responsive Design | H | 10hrs| hr | 
| Calander | H | hr | 5hr | hr |
| Total | H | 50hrs| hrs |

#### PostMVP
| Component | Priority | Estimated Time | Actual Time |
| --- | :---: |  :---: | :---: | 
| Interaction with Calander | H | 4hr | hr | hr |
| Nutrition | M | 7hr | hr |
| BMI | M | 7hr | hr |
| Authenication | H | hr | 5hr | hr |
| Remove account info | H | 5hr | hr |
| Total | H | 28hrs| hrs |

## Additional Libraries
 Axios - this will provide assistance on retrieving data from API.
 Router - this will provide help with switching to different pages/components on the app.
## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description  

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....
**ERROR**: app.js:34 Uncaught SyntaxError: Unexpected identifier                                
**RESOLUTION**: Missing comma after first object in sources {} object