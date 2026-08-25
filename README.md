# Smart Classroom & Timetable Scheduler — Frontend

This is a complete responsive frontend prototype using HTML, CSS and JavaScript.

## Run
Open `login.html` in a browser.

Demo login accepts any username/password. Choose Admin, Faculty or Student.

## Included
- Login and role selection
- Dashboard
- Student, Faculty, Subject management
- Classroom and Laboratory management
- Timetable creation
- Timetable conflict detection
- Room/Lab availability
- Notifications
- Profile
- Responsive UI
- LocalStorage demo database

## Backend integration
The forms currently use browser LocalStorage so the frontend can be demonstrated without a server. Replace the LocalStorage functions in `js/data.js` and CRUD functions in `js/app.js` with REST API calls when connecting to the Node.js/Express/MySQL backend.
