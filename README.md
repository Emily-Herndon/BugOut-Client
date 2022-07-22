# BugOut

### Description
#### BugOut is a development project and bug management system. Users will be able to submit, track and resolve issues easily. Bugs can be created with different priority levels and have their working status changed as the issue becomes resolved. Projects can have a feed of issues with team commentary. Users will be able to sign up as managers or members, each with different permissions.

[Server Repo](https://github.com/Emily-Herndon/BugOut-Server)
---

---
## Website Photos
![Login Page](./public/images/Login%20Page.png)

![Register Page](./public/images/Register%20Page.png)

![Projects Dashboard](./public/images/Projects%20Dashboard.png)

![Profile Page](./public/images/Profile%20Page.png)

![Project Form Page](./public/images/Project%20Form%20Page.png)

![Project Detail and Bug Form Page](./public/images/Project%20Detail%20and%20Bug%20Form%20Page.png)


---

## Technologies Used
- MongoDB was used to manage document-oriented information
- React was used for building composable user interfaces
- Tailwind CSS was used to style  
- Mongoose was used to manage relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB
- Axios was used to make HTTP requests from node. js or XMLHttpRequests from the browser 
- Jwt-decode helped decoding JWTs tokens
- Bcrypt was used to build passwords for security
- Cors was used to make requests from one website to another website in the browser
- Dotenv allowed us to separate secrets from your source code
- Express helped manage routing, sessions, HTTP requests, error handling, etc
- Jsonwebtoken was used to to share security information between two parties: a client and a server.

---
## Installation Instructions
- Fork and clone 
- Enter npm install in the terminal 
- Install MongoDb
- Enter nodemon on the server
- Enter npm run start on the client 

## ERDs
![Routing Chart](./public/images/ERDs.jpg)

---

## Restful Routing Chart
![Routing Chart](./public/images/RESTful-Routing-Chart.jpg)

---

## Wireframes
![Wireframes](public/images/Bug-Out-Wireframes.jpg)

---

## User Stories
As a user:
- I want to sign up as a manager or member
- I want log in and see all projects in the tracker
- I want to be authorized to manager roles or member roles
- As a manager, I want to create projects and be able to close bugs
- As a member, I want to create bugs and update statuses

- On my manager profile, I want to see my own projects with a form to add new ones
- On my member profile, I want to see my projects that I am assigned to with a form to add a bug to that project

- I want to be able to stay signed in for a certain duration
- I want to be able to log out
---

## MVP Goals
- [X] a login page with authentication methods 
- [X] authorized page views based on login credentials
- [X] ability to show all projects
- [X] ability to only see 'assigned'/'owned' projects
- [X] ability to add projects if authorized
- [X] ability to add bugs if authorized
- [X] ability to close bugs if authorized
- [X] ability to sort projects and bugs

---

## Stretch Goals
- [X] mobile friendly/responsive front end
- [X] dark mode
- [X] tailwind styling
- [] Carousel on /project 

---
## Difficulties 
- The element that gave us the most issue was the checkboxes 
- Another minor difficulty was adjusting to tailwind 