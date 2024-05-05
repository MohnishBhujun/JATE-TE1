# JATE-TE1

JATE application with PWA

## Table of Contents
  - [Description](#description)
  - [User Story](#userstory)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Installation](#installation)
  - [Demo Video](#demo-video)
  - [Link to Deployed application](#link-to-deployed-application)
  - [Screenshots](#screenshots)

## Description

This application demonstrates the deployment of a Progressive Web Application. 

Users can take notes which will persist after the application is closed - it can also be installed onto the desktop for offline use. 

## User Story

AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use


## Acceptance Criteria

GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application


## Installation

To use this application 

1.) Git Clone the Repository 

2.) Ensure Node.JS is installed on your system. 

3.) Initialize node by running npm i

4.) Run application using npm start

## Demo Video

https://github.com/MohnishBhujun/JATE-TE1/assets/149837818/ffc505e4-1a58-4201-9085-768e2a695bed

## Usage

Allow users to create a social media platform with an already-built backend platform

## Link to Deployed Application

https://jate-te1.onrender.com

## Screenshots

The Text Editor web application running as a freestanding Progressive Web App (PWA) icon on the desktop:
![Screenshot 2024-05-05 184911](https://github.com/MohnishBhujun/JATE-TE1/assets/149837818/714daeaa-2114-4090-86e9-e1918d548071)

The application's manifest.json file:
![Screenshot 2024-05-05 184523](https://github.com/MohnishBhujun/JATE-TE1/assets/149837818/9a123ff9-b628-48e9-a6b5-bf2e745c8ca9)

The application's IndexedDB storage:
![Screenshot 2024-05-05 184708](https://github.com/MohnishBhujun/JATE-TE1/assets/149837818/559ca220-5697-493e-abfa-19bdf797183d)
