# Fitness-Tracker
Group Project for CPSC 481: Human Computer Interactions. Our project is a mobile fitness-tracker app that allows users to schedule fitness activities, track workout progress, track calories and fluid consumption, and measure their time spent being active. 

## My Collaborator
Jarin Thundathil   <br />
Md Abdullah Mehedi  <br />
Melanie Nguyen  <br />
Harsh Patil 


# My Contribution
This is my first real project in my journey of learning react, my css knowledge was minimal at this point, so the styling applied is quite basic. The main objective of this project was to design an application that could help complete meaningful fitness tasks, while simplifying user workflows. I contributed in all Workout related functionality, namely, the "My Workouts" Landing Page as well as the "My Stats" page. Despite being a design class I chose to implement complete functionality, complete with error handling for incorrect inputs.

Users can:
  - Change the date for their given workout
  - Add a workout
  - Delete a workout
  - Rename a workout
The My Workouts page is design for workouts to persist, meaning once a workout is added the workout persists for everyday

For the "My Stats" page users can see more information about a given workout in editable inputs that are autofilled with the current information.

## Running Instructions (For devs hosting locally)
1. Clone this repository
2. Install node.js and npm
3. Install node-modules with `npm install`
4. Run command `npm start`

## Running instructions (For evaluators and everyone else)
1. Visit our [GitHub pages site](https://jarint.github.io/fitness-tracker) for the deployed version of this app (last redeploy: Dec. 06, 2023)  <br />
**Note:** The system session is not persistent so refreshing this page may clear all data that you've input. If you want to clear all data and are having issues, clear your browser cache or access the link through a private browser tab to ensure your browsing data is not being stored locally.

## General System Walkthroughs
#### Walkthrough 1 - Scheduling a Workout
1. From the Home screen, click a day on the calendar
2. Scroll down to the event field and enter the name of a new workout
3. Enter the start and end time of the workout in the time field
4. Tap save. When you click the home icon, your new workout will be added to your schedule.

#### Walkthrough 2 - Adding an exercise to a Workout
1. From the home page, click the My Workouts screen
2. Click the "Add Exercise" button and enter the name of the exercise and the number of sets and reps to complete.
3. Click "Add" and the new Exercise will now be present on the My Workouts page.

#### Walkthrough 3 - Tracking Nutrition and Hydration
1. From the Home page, click on the "Nutrition Goals" panel
2. Click "Set Goal"
3. Add your nutrition and hydration goals for the day
4. Click "Confirm"
5. Click on either the Nutrition or Hydration progress bars
6. Click the "Edit" button
7. Add in the type of Food/Beverage consumed and the approximate weight/volume from the drop down menu, or using the "Add Item" button
8. Click "Save"

#### Walkthrough 4 - Tracking a Run
1. From the Home page, click the "Time Active" panel
2. Set a goal time and goal distance with the fields at the top of the page
3. click the "Start" button
4. When completed, click the "Stop" button, followed by the "Save" button to save your progress.

## Summary
The use cases described in the system walkthroughs cover the major functionalities of our system. Not enumerated among these are the various fields for deletion and editing activities. See our system demonstration video [here](https://drive.google.com/drive/folders/1sYZt4tW6pRzHfJs1viEhCmewZV8Wurnt?usp=sharing) for more detailed walkthroughs that show the editing/deletion features of each use case.
