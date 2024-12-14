# T3A2 - Fullstack MERN application. 

## Links
- GitHub repo:
- Trello board:

## Table of content 

## R1. Description of the website
### Purpose
BabyLog is a digital tool for parents and carers to manage, view and track key information about children's growth metrics and immunisation status. The focus is on simplifying the process of recording and tracking growth and immunisation data, providing easy to understand educational resources as well as offering practical tools to promote actions that can improve a child's wellbeing.  BabyLog aims to support those providing caregiving responsibilities, ultimately empowering them with knowledge and handy tools.

### Features and Functionality
### Features:
* User account: user can sign up or log in, and log out.
* Child/children profile: user can create and manage multiple children’s profiles under one account. A child profile will include personal information such as name, date of birth, expected due date and the option to add notes and a profile picture.
* Caregiving roles: For those providing care, parents can grant access to the child profile providing that the carer has created an account with BabyLog. The parent will provide access to the data at their discretion (read only or full access).
* Growth tracking: the growth metrics recorded are height, weight and head circumference (head size). The data entered can be visualised as a list or as a graph. Based on the World’s Health Organisation growth standards.
* Immunisation tracking: logging vaccines and notification of upcoming or late vaccines following the Australian National Immunisation Program (NIP) schedule.
* Notes: The child’s profile will include a section for notes for users to enter additional information about the child or note from a doctor's appointment. 
* Important numbers page: this page will contain emergency numbers and the number of relevant healthcare related * organizations such as Nurse on call. This page will have the option to download the list for printing or sharing. 
Educational resources: It will include general information on the importance of immunisation, vaccine benefits and potential side effects. Content will be sourced from reliable institutions and organisations like the WHO, the Australian Institute of Health and Welfare (AIHW), and the Department of Health and Aged Care.
Access and Permissions: The main user (the user entering the child’s data) can grant access to carers or others using the app.
Secured data storage: the data will be stored in the database ensuring privacy compliance. 

### Functionalities:
* User authentication and authorisation: Use JWT for tokens to implement secure authentication. Use role based access controlled by the main user. 
* Database operations: Information to be stored in MongoDB database. CRUD operations (Create, Read, Update and Delete) for child profiles, growth data, immunisation records and notes. 
* Generate charts: Use a charting library to visualise the data. 
* Notification system: Create and schedule reminders for upcoming vaccinations using Node.js tool node-schedule 
* File download functionality: Allows users to export and download a list of important numbers.
* NIP data integration: Upload the Australian NIP schedule into the database for reference
* WHO standards integration: Use WHO growth standards as a reference for percentile.

### Target Audience
The app features are created primarily for parents interested in a simple solution for keeping track of growth metrics (weight, height, head circumference) and monitor immunisation status of one or more children in separate profiles. It is also targeted for parents interested in keeping a digital record easily accessible instead of just a physical record reducing the risk of losing or misplacing paper records. 
By offering clear and simple educational information, the app can become a helpful source of education within a family group. The feature of adding notes to the profile can be used as a tool to communicate between users. 

### Tech Stack:
* **Frontend**:
  * React
  * Vite
* **Backend**:
  * Express
  * Node.js
* **Database**:
  * MongoDB
* **Deployment**:
  * Netlify 
* **Packages and dependencies**:
  * Mongoose
  * Dotenv
  * Bcrypt
  * Node-schedule
  * Chart.js
* **Project management**:
  * Trello
* **Other tools**:
  * Canva
  * Figma
 
  ## R2. Dataflow Diagram

  ## R3. Application Architecture Diagram

  ## R4. User Stories

  ## Wireframes for multiple standard screen sizes, created using industry standard software

  ## Screenshot of Trello (or similar kanban system) board throughout the duration of the project
