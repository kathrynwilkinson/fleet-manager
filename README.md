
# Fleet Manager

![License: Apache](https://img.shields.io/badge/License-Apache2.0-yellow.svg)

Utilized the MERN stack to create an application that allows a business to effectively manage their WorkForce while streamlining communication between administrators and their employees.

## Table of Contents

- [Description](#fleet-manager)
- [User Story](#user-story)
- [Tech](#tech)
- [Visuals](#visuals)
- [Links](#links)
- [Installation & Usage](#installation-and-usage)
  - [Login Info](#login-information)
- [Contributing](#contributing)
- [Future Development](#future-development)
- [Contact Us](#questions)
- [License](#license)

## User Story

```md
    AS AN ADMINISTRATOR
    I WANT to be able to
    - create invoices, that employees can easily fill out
    - receive job information and create jobs
    - assign jobs to employees
    - monitor employee Job progress
    SO THAT I can efficiently operate and manage my small / medium sized business's fleet employees.

    AS AN EMPLOYEE
    I WANT to be able to
    - view assigned jobs for the day
    - access job-site information (i.e. address, contact information, notes, etc)
    - complete related job-site forms/invoices
    - mark jobs completed
    - have the ability to continue to work while remote and offline
    SO THAT I can continue to complete my job expectations in an easy and organized fashion.
 ```

## Tech

- MongoDb
- Express
- React (w/ hooks)
- Node.Js
- Passport.Js
- Sortable Js
- Moment
- react-material-ui

## Visuals

![sign-in](./client/src/assets/images/project-screenshots/custom-workforce-manager-sign-in.PNG) ![admin-dashboard](./client/src/assets/images/project-screenshots/custom-workforce-manager-admin-dash.PNG)
![job-assignment](./client/src/assets/images/project-screenshots/custom-workforce-manager-job-assignment.PNG) ![job-detail](./client/src/assets/images/project-screenshots/custom-workforce-manager-job-detail.PNG)
![invoice](./client/src/assets/images/project-screenshots/custom-workforce-manager-invoice.PNG)

## Links

- [Github Repository](https://github.com/kathrynwilkinson/fleet-manager)
- [Deployed on Heroku](https://fleet-manager-react.herokuapp.com)

Note: Project was originally developed as a group project. I forked the original group project when it was in a working state and made some minor contributions. More recently, I created a new repository in order to deploy my personal copy of the project and continue working on it. I've since invited some of the original collaborators to assist in updating and maintaining this project.

- Original Group Project: [Custom Workforce Manager](https://github.com/will98nicholson/Custom-Workforce-Manager)
- Group Project Fork: [Custom Workforce Manager personal version](https://github.com/kathrynwilkinson/Custom-Workforce-Manager-personal-version)

## Installation and Usage

This program can be run through a browser using the link to the the deployed application and the login information below:

### Login Information

- Fleet Manager: [Deployed](https://fleet-manager-react.herokuapp.com)
  - Admin Username: Crew #1 | Password: 4CfkVBoxV
  - Employee Username: Crew #2 | Password: Ggjz4t1

Alternatively, to run this application locally you will need to:

Clone this repository to receive all of the files
Set up your environment variables in a .env file
Run "npm install" in the command line of your terminal to set up all of the dependencies
Populate the existing database items by running "npm run seed" in your terminal
Run "npm start" to start the application's connection
Go to the url of the application (http//:localhost:3000) to begin using it

## Contributing

Original project: [Custom Workforce Manager](https://github.com/will98nicholson/Custom-Workforce-Manager)

- Michael Kotte: <https://github.com/mkotte>
- Kathryn Wilkinson: <https://github.com/kathrynwilkinson>
- William Nicholson: <https://github.com/will98nicholson>
- Brandon King: <https://github.com/thebsking>
- Corrinne Worden: <https://github.com/CorrinneW>

This project: [Fleet Manager](https://github.com/kathrynwilkinson/fleet-manager)

- Kathryn Wilkinson: <https://github.com/kathrynwilkinson>
- Jon Jackson: <https://github.com/ocskier>

If you'd like to contribute, send a message and make a pull request!

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](code_of_conduct.md)

## Future Development

- Available offline (PWA functionality)
- Downloadable to android + ios home-screen
- Device camera functionality / implementation
- Fast load speeds
- Mobile app look/feel (currently styled for tablet devices)
- Push Notifications (mobile + desktop)

## Questions?

Please feel free to contact us with any questions via email.

- Kathryn Wilkinson: [kathrynxwilk@gmail.com](kathrynxwilk@gmail.com)
- Jon Jackson: [ocskier@gmail.com](ocskier@gmail.com)
- C. Michael Kotte: [michaelkotte1@gmail.com](michaelkotte1@gmail.com)
- Brandon King: [brandonscottking@gmail.com](brandonscottking@gmail.com)

## License

This project is licensed under the Apache 2.0 License.
For more information, please visit: [Apache Explained](https://choosealicense.com/licenses/apache-2.0/)

&copy; 2021 k.wilkinson | j.jackson | m.kotte | b.king | w.nicholson | c.worden
