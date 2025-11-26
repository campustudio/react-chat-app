# React Chat App

## Introduction

1. Frontend is based on React, backend is based on Node.js
2. Chat mode is based on creating and joining chat rooms
3. After starting one backend service and two frontend services, two-person chat conversation can be achieved
4. If the other party doesn't reply after 20 seconds, a chatbot will reply with a prompt message
5. Frontend and backend communication is implemented based on WebSocket protocol

## Local Startup Method (It is recommended to watch the video demonstration first to familiarize yourself with the operation before running it locally, to avoid various environment issues. Note: if your local Node version is too low, please upgrade to a newer version to ensure dependencies can be installed properly)

### Execute the following commands respectively:

- 1. Open the first terminal window, navigate to the server directory under the root directory and run `npm install` to install backend dependencies. After installation, run `npm start` in the same directory to start the backend service. The backend service will run on `localhost:3000` by default
- 2. Open the second terminal window, return to the project root directory and run `npm install` to install frontend dependencies. After installation, run `npm start` in the same directory to start the first frontend service. It will prompt that port 3000 is occupied and ask if you want to use a new port. Type yes to start. The browser will open a new page automatically, and the service will run on `localhost:3001` by default
- 3. Open the third terminal window, run `npm start` in the project root directory to start the second frontend service. As above, it will prompt whether to use a new port. Type yes to start. The browser will open a new page automatically, and the service will run on `localhost:3002` by default
- 4. At this point, we now have 1 backend Node.js service and 2 frontend React services running simultaneously
- 5. Now you can perform two-person chat conversation scenarios in the two frontend browser windows. Please refer to the video demonstration for specific operations
- 6. Note: Because the OpenAI account has no quota left, although the service calls successfully, it doesn't have much effect. Currently using fixed text for simulation. I've also explained this in the code and UI
