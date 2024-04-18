# WebSite-Chat
This is an Basic Chat app based on local host of network where devices (desktops/Laptops) can be connected to chat , I am testing it on mobile but haven't optimised it for the use of mobiles .
First, We will create a backend server which will serve a middleman between mongDB and React FrontEnd.
We will create an Interactive and Simple UI design for the frontEnd in which the message is sent and the other user responds to it. All the messages along with userName will be sent to backend using above created backend.
We will use Socket.IO toupport real time chat.
Lastly, we will create a database in MongoDB to store the messages.
Steps to Create the Project:


Step 1: Create a new project folder and navigate to it:

mkdir chat-backend
cd chat-backend


Step 2: Initialize a Node application and install required dependencies:

npm init -y
npm install express mongoose cors socket.io
Folder Structure (Backend):

<img width="155" alt="Screenshot 2024-04-18 at 11 11 08 PM" src="https://github.com/Alpha606/WebSite-Chat/assets/75906705/43b5ba10-7fcd-4381-ba46-5e1cf94c6fd2">


Dependencies (Backend):

"dependencies": {
    "cors": "^2.8.5",
    "express": "^4.18.2",
    "mongoose": "^8.0.4",
    "socket.io": "^4.7.3"
}


Step 3: To start the server run the following command.

node server.js
Step 4: Creating the frontend of the app by using the following command


/FrontEnd
cd ..
npx create-react-app chat-frontend
cd chat-frontend
Step 5: Install the required dependencies.

npm install axios react-router-dom socket.io-client
Folder Structure(Frontend):
<img width="155" alt="Screenshot 2024-04-18 at 11 11 19 PM" src="https://github.com/Alpha606/WebSite-Chat/assets/75906705/714e2dee-bf3c-4387-9e8f-ef052bb2b3e9">


wq

Dependencies(Frontend):

"dependencies": {
    "@testing-library/jest-dom": "^5.17.0",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "axios": "^1.6.5",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-router-dom": "^6.21.1",
    "react-scripts": "5.0.1",
    "socket.io-client": "^4.7.3",
    "styled-components": "^6.1.8",
    "web-vitals": "^2.1.4"
}

/output
Step 6: To start the frontend run the following command.

npm start
<img width="1339" alt="Screenshot 2024-04-18 at 11 10 48 PM" src="https://github.com/Alpha606/WebSite-Chat/assets/75906705/43f7b929-6d61-4f27-bd39-a66ab4e912b5">

