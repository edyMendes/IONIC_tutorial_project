# IONIC Tutorial Project

Welcome to the Ionic Learning Playground!

### Overview
This project serves as an educational introduction to the Ionic framework, showcasing the fundamentals of building a simple tab application. Whether you are a beginner exploring the world of mobile app development or an experienced developer eager to learn Ionic, this project is designed with education in mind.

### Features
**Hello World Tab**

In the "Hello World" tab, experience the basic capabilities of Ionic by triggering a friendly "Welcome to the Ionic Vue app." message alert. This serves as a starting point to understand how to handle user interactions within an Ionic app.

**Todo App Tab**

Dive deeper into Ionic's capabilities with the "Todo App" tab. Explore the creation of a simple yet functional todo list application. This tab demonstrates Ionic's ability to manage data, handle user input, and update the user interface dynamically.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Ionic CLI](https://ionicframework.com/docs/cli)

### Installation

To run the project for the web, open the project folder and run:

```
npm install
ionic serve
```
To run it on Android, use the following commands:

```
ionic build
ionic cap add android
ionic cap open android
ionic cap run android -l --external
```

When the last command finishes running, you should see this message on the screen:

```
[INFO] Development server running!
```

Only after this, you can run your app on Android Studio.

## Built With
- [Ionic](https://ionicframework.com/) - The web framework used
