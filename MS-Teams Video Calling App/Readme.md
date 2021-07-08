MS-TEAMS VIDEO CALL APP
----------------------------------------
----------------------------------------
A **Video Call** application where multiple users can connect and have face-to-face conversation with chat features available 
1. **Sockets.io** - Used to implement the real-time functionalities by sending triggering and monitoring events on a topic-subscription based model.
2. **uuid** - Used to create unique ID's for inviting other user
3. **nodemon** - Nodemon is a utility that will monitor for any changes in your source and automatically restart your server.
## **Live Demo** - https://video-chat-app-v1.herokuapp.com/
## Preview 
### Join Page 
![image](https://user-images.githubusercontent.com/69220037/124866025-5ad8ff80-dfd9-11eb-8dd5-a0c48955a6d5.png)

### After you join
![image](https://user-images.githubusercontent.com/69220037/124870939-0fc2ea80-dfe1-11eb-99d0-c224c5fb049e.png)

## Way to invite your friend 
### Click on the button as shown in the image copy the URL and share with your friend 
![image](https://user-images.githubusercontent.com/69220037/124871160-56b0e000-dfe1-11eb-9494-65b716ee7516.png)

### Now the connection is established you can have face-to-face conversation
![image](https://user-images.githubusercontent.com/69220037/124869986-a42c4d80-dfdf-11eb-9199-1ebf9e0224a2.png)

### Chat feature (Send and receive messages during the meeting with other participants easily)
![image](https://user-images.githubusercontent.com/69220037/124870647-af33ad80-dfe0-11eb-8e53-0196821eb3a4.png)

## Dependencies you need to install for local set up
### `npm install`
Run this to install all dependencies required for the app to run
<ul>
  <li>npm install express</li>
  <li>npm install socket.io</li>
  <li>npm install ejs</li>
  <li>npm install uuid peer</li>
  <li>npm install -dev nodemon</li>
</ul>

### `npm start`
Use this command to run the app in the development mode that will run the server.js.<br />
Open [http://localhost:3000](http://localhost:3000) to view running app it in the browser. 
The page will reload if you make edits.<br />
