# Team Career Camp - Student Interview Database

This web application is designed for Team Career Camp to maintain a database of student interviews. It allows employees to input student details, interview information, and results, and provides the functionality to download the data in CSV format.

## Tech Stack

- Node.js
- MongoDB
- CSS and EJS template
- Passport.js (Used for Authentication)

## Packages Used

├── express@4.18.1
├── express-ejs-layouts@2.5.1
├── express-session@1.17.3
├── mongoose@6.3.3
├── node-fetch@2.6.7
├── nodemon@2.0.16
├── objects-to-csv@1.3.6
├── passport-local@1.0.0
├── passport@0.5.3
├── validator@13.7.0
├── connect-flash@0.1.1
├── connect-mongo@4.6.0
└── ejs@3.1.7


## Local Setup

To run this project on your local system, follow these steps:

1. Clone the repository from GitHub.
2. Extract the downloaded folder.
3. Open a terminal and navigate to the project directory.
4. Run the following command to install the required dependencies:

```bash
npm install
Run `npm install` to install required dependencies

Start the server using the following command:
-npm start
## Features

- Employee Sign Up and Sign In with authentication using Passport.js.
- Add new students and view the list of students.
- Create interviews, allocate students to interviews, and mark result status.
- Download a complete CSV of all the data with the specified columns.
- Bonus Feature: External Jobs List, fetching real available jobs in India for React and Node.js from open APIs.

## Live Demo

You can find the live demo of this project on GitHub:

[GitHub Repository](Link_Git_Hub_Link)

Please note that this application is for internal use by Team Career Camp only.

## About

This web application was developed by [Your Name] as part of a project for Team Career Camp. For any inquiries or support, feel free to contact [Your Email Address].

I hope this application proves to be a useful tool for maintaining student interview records. Happy interviewing!

## Screenshots

- Sign Up
  ![Sign-Up](./images/signup.PNG)

- Sign In
  ![Sign-In](./images/login.PNG)

- Student Page
  ![Student-Page](./images/studentlist.PNG)

- Interview Page
  ![Interview-Page](./images/companylist.PNG)

- Add student
  ![Add-Student](./images/AddStudent.PNG)

- Schedule Interview
  ![Interview](./images/InterviewSchedule.PNG)

