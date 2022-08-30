# Mapty

The goal of this application is to log the location, duration and distance information for running and cycling workouts with popup pins on the map.

## Project Description

This application helps users to log their workout records on the map.

The application automatically obtains the user's current location coordinates using a geolocation api when the user first loads the application and displays the location in the right view. When the user clicks the workout location on the map, an input form appears on the left side.
When the form is filled out and the user presses 'enter', we can see the popup pin on the map with the workout information.
The application uses local storage to persist the previous records even when the user reloads the app.

### What I've learned

- object oriented programming
- geolocation api
- 3rd party library (leaflet)
- local storage

### Live demo link

[https://mapty-hyeyoung.netlify.app/](https://mapty-hyeyoung.netlify.app/)

### Logic flowchart

![App Screenshot](https://github.com/hykim-soulis/Mapty/blob/master/Mapty-flowchart.png?raw=true)

## How to Install and Run the Project

1. Clone the project

```bash
  git clone https://github.com/hykim-soulis/Mapty.git
```

2. Go to the project directory

```bash
  cd my-project
```

3. Double-click the index.html file

## Resource

This project is a css and javascript project done with the Udemy course: The Complete JavaScript Course 2022 by instructor Jonas Schmedtmann. HTML and part of CSS files were provided by the instructor.

The below link is the instructor's github address.

[Instructor's GitHub](https://github.com/jonasschmedtmann/complete-javascript-course.git)
