# MEAN
Udemy class taught by Maximilian Schwarzmuller. 


MongoDB - user data, messages, database
Express - host
Angular - client-side (js framework to create UI for users)
Node.js - js runtime/server side language for authentication and core logic running on the server

Angular
---
- A client-side (browser) Framework which allows you to build Single-Page-Applications (SPA)
- Handles the entire front end logic
- Renders UI with dynamic data 
- handles user input 
- communicates witht he backend services
- provides a mobile app like User Experience

Node.js
---
- server side library: JS on the server-side
- listens to requests and sends back responses
- executes server-side logic 
- interacts with databases and files
- alternative to PHP, ruby on rails, Java, ect. 

Express
---
- node.js framework which simplifies writing server-side code and logic
- based on Node and offers the same functionaities
- middleware-based: funnel requests through functions
- includes routing, view-rendering and more
- simplifies the useage of node

MongoDB
---
- a noSQL database which stores "documents" in "collections" instead of records in tables
- store application data 
- enforces no data schema or relations
- easily connected to node/express (it shouldn't be connected to angular-> causes vulnerabilities)
- a powerful database which can easily be integrated into a node/express environment

Single-Page-Application (SPA)
---
index.html  
- includes scripts to house the angular framework and the angular app
- allows for instant re-rendering, instant user feedback and makes buidling highly engaging UIs possible.

Client (Browser) - Angular (build UI)
- SPA, presentation/UI (SPA is not necessarily served by Node backend)
Server - Node.js, MongoDB 
- Business logic, persistant data storage, authentication logic

Connecting the Client & the Server
- AJAX (background) - requests and recieves without reloading the page 
- JSON data Format


