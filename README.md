# Code-collaborator

The main goal of the project is to create advancement in E- Learning.
The main problem that the educational system is facing is how to provide practical knowledge through E-learning.

Code collabrator is a real-time interactive web-based lab made for students & teachers. On codelabs students can practice live programming and teachers can monitor them. 
This is very necessary in this era of pandemic where even education is being pushed all online.

* Code Collabrator have the following features:

 1) Create room: The admin (teacher) creates a room with a secret link and password.

 2) Join the room: Participants who have the link and password can enter the room and complete their programming tasks, assigned by teachers.

 3) Code Editor: This code editor supports 4 major programming languages: C, C++, Java, and Python. It also has the enter, exit, run, and Submit functions.

 4) Real-time live coding: In real time, the admin(teacher) can manage the room, guide and verify each student's specific code.

 5) Check the code: after sending the code, Admin can download the sent code as a pdf.

## Tech Stack used : 

**Client:** Ejs, Bootstrap, CSS, JS

**Server:** Node, MongoDB, Socket.io

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PORT` (write the localhost post mine is 3001)

`MONGO_DB_URl` ( default is mongodb://localhost:27017 )

`JWT_SECRET` (Obtained from Proper authentication from JWT site)

  
## Installation Guide: 

- Step 1: Install dependencies

    ```bash
  npm install
    ```

- Step 2: Start the server

    ```bash
  npm run start
    ```

- Step 3: Open any web browser and then paste the server address to see the webpage working on your local machine



## Happy coding 
