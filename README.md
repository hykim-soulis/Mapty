# Mapty

The goal of this application is to log the running and cycling workouts location, duration and distance information by popup pin on the map for user.

## Project Description

This application helps users to log their workout record on the map.

The application automatically obtain user's current location by browser using geolocation api when the user first load and display on the right side. When the user clicks the workout location on the map, an input form appears on the left.
Fills out the form and preeses enter, user can see the popup pin on the map with the workout information.
The application uses local storage to preserve the previous record even though the user reload the app.

### What I've learned

- object oriented programming
- geolocation api
- 3rd party library (leaflet)
- local storage

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

This project is a css and javascript coding-along with the Udemy The Complete JavaScript Course 2022 by instructor Jonas Schmedtmann. HTML and part of CSS files were provided by the instructor.

The below link is the instructors github address.

[Instructor's GitHub](https://github.com/jonasschmedtmann/complete-javascript-course.git)
