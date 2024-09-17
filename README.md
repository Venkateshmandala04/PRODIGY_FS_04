# Prodigy_FS_04 Real-Time Chat Website

Welcome to the *Real-Time Chat Website*! This project is a robust chat application built with the MERN stack (MongoDB, Express.js, React.js, and Node.js), along with Socket.io for real-time communication, Redux Toolkit for state management, and Tailwind CSS for styling.

## Features

- *Real-time Chat*: Send and receive messages instantly with other users.
- *User Authentication*: Sign up, log in, and log out using JWT and Google Authentication.
- *Group Creation*: Create chat rooms and invite others to join.
- *Notifications*: Receive alerts for new messages.
- *Emojis*: Add emojis to your messages.
- *Profile Page*: Update your avatar and display name.
- *Search Functionality*: Easily find and connect with users.
- *Responsive Design*: Optimized for various screen sizes and devices.

## Technologies Used

- *MERN Stack*: MongoDB, Express.js, React.js, Node.js
- *Socket.io*: Real-time communication
- *Redux Toolkit*: State management
- *Tailwind CSS*: Styling

## Configuration and Setup

To run this project locally, follow these steps:

1. *Clone the Repository*

   bash
   git clone https://github.com/yourusername/real-time-chat-website.git
   

2. *Set Up the Client*

   - Navigate to the client directory:
     bash
     cd real-time-chat-website/client
     

   - Create a .env file in the root of the client directory and add the following:
     
     REACT_APP_GOOGLE_CLIENT_ID=<Your_Google_Client_ID>
     REACT_APP_SERVER_URL='http://localhost:8000'
     

   - Get your Google Client ID by creating a new OAuth Client ID on the [Google Credentials Page](https://console.developers.google.com/apis/credentials). Set up the OAuth client with the following redirect URLs:
     - http://localhost:3000
     - http://localhost:3000/login

   - Install client-side dependencies and start the client:
     bash
     npm install
     npm start
     

3. *Set Up the Server*

   - Navigate to the server directory:
     bash
     cd real-time-chat-website/server
     

   - Create a .env file in the root of the server directory and add the following:
     
     PORT=8000
     URL=<Your_Database_URL>
     SECRET=<Your_Secret_Key>
     CLIENT_ID=<Your_Google_Client_ID>
     BASE_URL="http://localhost:3000"
     

   - Install server-side dependencies and start the server:
     bash
     npm install
     npm start
     

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature:
   bash
   git checkout -b my-new-feature
   
3. Make changes and commit them:
   bash
   git commit -m 'Add some feature'
   
4. Push your branch to your forked repository:
   bash
   git push origin my-new-feature
   
5. Create a Pull Request.
