---
title: "How to install Ract JS using Vite: A Fast and Efficient Guide."
datePublished: Tue Jul 09 2024 18:56:59 GMT+0000 (Coordinated Universal Time)
cuid: clyerw3w2000409ie9u5p7x5z
slug: how-to-install-ract-js-using-vite-a-fast-and-efficient-guide
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1720551243962/0d8203ed-93ec-412e-8cab-1ac3e98832a5.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1720551413189/f1b29149-089d-49a9-a829-9e173189a77f.png
tags: javascript, reactjs, frontend-development

---

**Introduction:**

Vite is a modern development server that provides a fast and efficient way to build and deploy web applications. In this article, I will take you through a step-by-step guide to installing React JS using Vite, allowing you to take advantage of its speedy development capabilities.

**Step 1:** Install Node.js

Before installing React with Vite, ensure you have Node.js installed on your computer. Download ([https://nodejs.org/](https://nodejs.org/)) and install Node.js from the official website if you haven’t already.

**Step 2:** Creating a New React.js Project

To create a new React.js project with Vite, open your terminal and run the following command:

npm create vite@latest my-react-app

(Replace my-react-app with your preferred project name.)

This command will generate a new project. Vite will provide you with a list of frameworks you can use, and since we are only interested in React.js, you can simply select React from the list and press enter on your keyboard. Vite will then provide you with a list of variants you can work with, from which you can select JavaScript or any other variant you want.

**Step 3:** Navigating to Your Project Directory

Once the project has been created, navigate to the directory using the following command:

cd my-react-app

(You can also replace my-react-app with the name you choose when creating you project.)

**Step 4:** Installing Dependencies

You can install the project dependencies by running the following command:

npm install or npm i

This command will install all the necessary dependencies specified in the package.json file, including React.js and Vite.

**Step** [**5**](http://localhost:3000/)**:** Starting the Development Server

After [](http://localhost:3000/)the dependencies have been installed, you can start the development server by running the following command:

npm r[u](http://localhost:3000/)n dev

This [c](http://localhost:3000/)ommand will start the Vite development server, which will serve your React.js application. You can access your application by navigating to [](http://localhost:3000/)link provided in your web browser.

**Step 6:** Exploring Your Project

The my-react-app directory will have the following structure:

my-react-app/

├── index.html # The main HTML file

├── main.jsx # The entry point for your React app

├── package.json # Project dependencies and scripts

└── public/# Static assets (images, fonts, etc.)

**Step 7:** Making Changes and Seeing Results Instantly

Vite excels at hot module replacement (HMR). As you modify your code (.jsx,.css, etc.), Vite automatically updates the browser without a full refresh, significantly enhancing your development workflow.

Step 8: Building for Production

Once you’re satisfied with your React.js application and ready to deploy it to production, you can build the project by running the following command:

npm run build

This command will generate a production-ready build of your application in the dist directory.

**Conclusion**

Vite offers a refreshingly fast and efficient way to develop React.js applications. With its lightning-fast development server and HMR, you can focus on creating exceptional user experiences without getting bogged down by lengthy build times. Dive into the world of React development with Vite and experience the difference!