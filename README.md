# [**Chatmate**](https://chatmate-5x3f.onrender.com/)
Chat app using MERN and Socket.io


---
## Features
- Real Time Message sending using socket.io
- Secure communication with JWT and Bcryptjs authentication. Ensured privacy, user authenticity, and information protection in the chat application.
- Group chat as well as one-to-one chat functionality
- Real Time Notifications

## Tech Stack
- MERN
- Socket.io
- ChakraUI
- React-Lottie
- JSON Web token
- Bcryptjs

## Required Environment Variables

| VARIABLE   | Sample value                 |
| ---------- | ---------------------------- |
| MONGO_URI   | mongodb://localhost/chatroom |
| JWT_SECRET | **** |
| NODE_ENV | production |

## Installation Instructions

1. Install _Node.js_
2. Install _npm_
3. If you plan to use a local instance of _MongoDB database_, install _MongoDB atlas_.
4. Clone this github repo.
5. In the local project directory, create a new file called "`.env`".
6. Setup the environment variables as described above.
7. Open the local project directory in a terminal, and run: `npm install`.

## Available Scripts

### In the project directory, you can run:

`cd client`

### `npm run start`

Runs the front-end client app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.


`cd server`

### `nodemon index.js`

Runs the back-end server app in the development mode.<br>
Open [http://localhost:5000](http://localhost:5000) to view it in the browser. Please note that the server requires an active instance of the **MongoDB database**. Either provide a _MongoDB atlas_ link in the `URI` environment variable, or use a local database, by placing its DATABASE in the same.

## Application Screenshots
![image](https://github.com/Kunal-Vijay/Chatmate/assets/79903746/c312f27e-3840-4057-b44f-15751a811fd4)
![image](https://github.com/Kunal-Vijay/Chatmate/assets/79903746/6ab045fa-0c51-469f-8d90-ce982cea6588)
![image](https://github.com/Kunal-Vijay/Chatmate/assets/79903746/50a23c10-43d3-464c-a471-1d24f5e1e6f6)


---