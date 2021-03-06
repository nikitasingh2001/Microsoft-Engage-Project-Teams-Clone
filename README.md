Microsoft Teams Clone 
==============
#### To build a Microsoft Teams Clone, in Microsoft Engage 2021 ####

Introduction
------------

The Challenge of this project was to build a Microsoft Teams Clone and Your solution need to be a fully functional prototype with at least one mandatory functionality - a minimum of two participants should be able to connect with each other using your product to have a video conversation and also there was a adopt stage where we need to include a chat app in our application.

To view a demo of the execution of the project, download the repo, and then open the index.html file on your browser. The index.html file is located in the MS-Teams-Website folder. This demo works on Microsoft Edge, Google Chrome, Firefox, and Safari. You can also view the online demo below. And access the services of video calling and group chatting by visiting at services section.

### **Visit Website** - https://nikitasingh2001.github.io/MS-Teams-Website/
### **Another-link to visit website** - https://nikitasingh02engage2021.netlify.app/

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ul>
    <li>
      <a href="#Main-Website">About Main Website</a>
    </li>
    <li>
      <a href="#video-app">Video-App</a>
    </li>
    <li>
      <a href="#chat-App">Chat-App</a>
    </li>
    <li>
      <a href="#Agile">How I implemented Agile methodology during my project phase?</a>
    </li>
    <li>
      <a href="#Contributing">Contributing</a>
    </li>

  </ul>
</details>


## About Main Website
A **Web-App** which provides you facilities like Video-Calling and group chatting

### Technology Used for frontend development:
1. Html
2. CSS
3. Java Script 

### First Look
![image](https://user-images.githubusercontent.com/69220037/124892175-4572ce00-dff7-11eb-82fb-b3a602bd1f98.png)

### How to access the services we provide??
### Visit services section
![image](https://user-images.githubusercontent.com/69220037/124892416-7b17b700-dff7-11eb-9ece-24790ec26645.png)

### Click on **START VIDEO** or **START CHAT** to start video call conversation or group-chat respectively.
![image](https://user-images.githubusercontent.com/69220037/124892914-e8c3e300-dff7-11eb-9b65-1ee8a4ab67db.png)

If you want to know in detail visit `MS-Teams Website` Folder or you can visit my git hub repository https://github.com/nikitasingh2001/MS-Teams-Website




## Video-App

MS-TEAMS VIDEO CALL APP
==============

A **Video Call** application where multiple users can connect and have face-to-face conversation with chat features available 
1. **Sockets.io** - Used to implement the real-time functionalities by sending triggering and monitoring events on a topic-subscription based model.
2. **uuid** - Used to create unique ID's for inviting other user
3. **nodemon** - Nodemon is a utility that will monitor for any changes in your source and automatically restart your server.
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

### Dependencies you need to install for local set up
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

If you want to know in detail visit `MS-Teams Video Calling App` Folder or you can visit my git hub repository https://github.com/nikitasingh2001/MS-TEAMS-VIDEOCHAT-APP




## Chat-App
MS-TEAMS CHAT APP
==============

A **Real-Time** chat application with multiple rooms and video chat facilities
1. **Sockets.io** - Used to implement the real-time functionalities by sending triggering and monitoring events on a topic-subscription based model.
2. **moment.js** - Used to format time at which messages are send and received
3. **nodemon** - Nodemon is a utility that will monitor for any changes in your source and automatically restart your server.
## **Live Demo** - https://teamschatapp.herokuapp.com/
## Preview 
### Join Page
![image](https://user-images.githubusercontent.com/69220037/124859195-10ea1c80-dfcd-11eb-90aa-936461334dff.png)

### Chat Box ui
![image](https://user-images.githubusercontent.com/69220037/124859450-95d53600-dfcd-11eb-98e3-3d25bb847411.png)

### Welcome Message and Notification on the joining of any user
![image](https://user-images.githubusercontent.com/69220037/124859691-fa909080-dfcd-11eb-8d64-e07e5def0d39.png)

### Auto Scroll down on spamming of messages
![image](https://user-images.githubusercontent.com/69220037/124860019-8b676c00-dfce-11eb-9eb4-e60650c575cc.png)

### Leave Room facility if you want to end the chat and video call facility if you want to have face-to-face conversation 
![image](https://user-images.githubusercontent.com/69220037/124860369-28c2a000-dfcf-11eb-8c11-f2794e58a3cb.png)

## Dependencies you need to install for local set up
### `npm install`
Run this to install all dependencies required for the app to run
<ul>
  <li>npm install express</li>
  <li>npm install socket.io</li>
  <li>npm install moment</li>
  <li>npm install -D nodemon</li>
</ul>

### `npm start`
Use this command to run the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view running app it in the browser. 
The page will reload if you make edits.<br />

If you want to know in detail visit `MS-Teams Chat App` Folder or you can visit my git hub repository https://github.com/nikitasingh2001/MSTeamsChatApp


## Agile
### How I implemented agile methodology using Scrum framework??
So, we have to build a product like MS-Teams clone in our case so we know that MS-Teams have so many features. So, we priortize some requirement like in our case is to build a minimum requirement for qualifying that was to build a functional prototype in which two people can have video conversation with each other and then we start working on product but if you make use of scrum it normally goes with sprints. So, as in our case to complete the task we have one-month but our client or to be more specific our mentor will not be waiting for entire month to deliver this so what we can do is to give something which is potentially deployable product. So, to implement this what we will do we take some important requirement for a particular sprint(which is 1 week in my case).
  
Now, we have product backlog which have all the requirements from start of the project to the end but agile allows us to make changes even in later phase of development so it's not fixed. So, we will take some backlog that is going to be sprint backlog but before this you need to plan well so in the upcoming week you will work on that particular part. And after completion of each sprint we give increment that is **potentially deployable product** to our mentors but it may happen that in particular week you are not able to complete all which you have decided for that particular sprint so you can send that backlog for next week with some other feature but before the start of next sprint you are going to have sprint retrospective that is discussion with mentors what you are able to achieve?, What are your backlogs? , What are you plans for next week?

**Here, below in table I have summarised how my scrum board looks like for this project which briefly describes about my backlogs, my plans for next week, how much I was able to achieve**
  
**For the first two weeks-**
![image](https://user-images.githubusercontent.com/69220037/125159468-2742d480-e195-11eb-85c0-000ac1ce0c66.png)

**For the next two weeks-**
![image](https://user-images.githubusercontent.com/69220037/125159505-6d983380-e195-11eb-919f-1c70b5f8d3cf.png)

So, all the participants are actually going to thank microsoft because not only just keep working on task which we were assigned we also got a chance to experience the **adopt stage** of agile.
So, basically what happened that in the last week of this project we were assigned a new task that was like we need to adopt with changes that as a client they are demanding from us to add a new feature in our prototype that was to build a Chat App.
As, we were following agile methodology we were able to achieve this easily even in later phase of the development of project.
 
## So, this is how I applied the agile methodology while creating the solution for the challenge assigned to us.
### Be Agile!!

#### If you want to read in detail about agile do visit Agile.md file 


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request































