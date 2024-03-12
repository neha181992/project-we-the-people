# Welcome to we-the-people

## Overview
We-the-people is a digital crowdfunding platform designed to facilitate connections between college-based startups and their backers. Our platform not only serves as a conduit for funding but also raises awareness about the crowdfunding ecosystem, empowering college entrepreneurs to register for crowdfunding, gather public feedback, and extend their reach.

## Project Repository: project-we-the-people
This repository hosts the codebase for our crowdfunding application, developed using the MERN stack. Follow the instructions below to set it up.

## Getting Started with Create React App
This project was initialized with [Create React App](https://github.com/neha181992/project-we-the-people).

## Backend Setup Instructions
1. Clone the repository and navigate to the 'server' folder in your terminal:
   ```
    cd server
    ```
2. Install the required Node.js packages by running:
    ```
    npm install
    ```
3. Next, ensure you have a `.env` file containing the below credentials

    ### Environment Variables

    ```
    JWT_SECRET=e5d477b86e46108076f109e3b958e1c7f1948659bb7c2dc00aa18c61a474b81d

    ACTIVATION_TOKEN_SECRET=e5d477b86e46108076f109e3b958e1c7f1948659bb7c2dc00aa18c61a474b81d

    PORT=5000

    MONGO_URI=mongodb+srv://nehagupta18oct:Nehamongo34@tumo.7tsryxw.mongodb.net/?retryWrites=true&w=majority&appName=tumo

    RAZORPAY_KEY_ID=rzp_test_ROhDid9hsKbY7e

    RAZORPAY_SECRET=5Gi8eIyTuZSd7m9mTuGcdXnj
    ```
4. To start the server, execute the following command:
    ```
    npm start
    ```


## Frontend Setup Instructions
1. Open your terminal and navigate to the 'app' folder in your terminal:
   ```
    cd app
    ```
2. Run the following command to install dependencies:
    ```
    npm install --force
    ```
3. Once installation is complete, start the application by running:
    ```
    npm start
    ```

The app will launch in your default browser at [http://localhost:3000](http://localhost:3000). Any changes you make will trigger an automatic reload, and any errors will be displayed in the console.


## Deployment Information
Our project is now deployed on RENDER, utilizing their free server option. However, please be aware that this may result in slightly slower performance due to the limitations of the free tier.\
 You can access the live demo by visiting the following link: [Working Demo](https://mernfront-t2t1.onrender.com/).


