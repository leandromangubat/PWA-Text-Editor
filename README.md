# PWA-Text-Editor

![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)

This README file provides an overview of the Text Editor Web Application, which allows developers to create and store notes or code snippets with or without an internet connection. The application follows specific acceptance criteria to ensure functionality and reliability.

## Getting Started

To run the Text Editor Web Application on your local machine, simply click on this link: https://warm-plains-47519-91bc2c192fca.herokuapp.com/

## How to Use the Application

The Text Editor Web Application provides a simple and intuitive interface for creating and managing your notes or code snippets. Here's a step-by-step guide on how to use the application effectively:

1. Opening the Text Editor
   After starting the application and navigating to the URL, you will be presented with the text editor interface.

2. Creating and Editing Content
   Start typing and editing your content in the text editor. The application uses IndexedDB to automatically save your content as you type. There is no need to explicitly save your work. Whenever you click off the DOM window, the content in the text editor will be automatically saved in IndexedDB. When you close the text editor and reopen it, your content will be retrieved from IndexedDB, allowing you to pick up where you left off.

3. Installing the Application
   If you wish to access the application offline or directly from your desktop, you can install it as a standalone web application. To do this:
   Click on the "Install" button available in the application. This will download the web application as an icon on your desktop.
   Once installed, you can launch the application directly from your desktop, even without an active internet connection.

## Technologies Used

The Text Editor Web Application utilizes the following technologies:

Node.js
Webpack
Heroku (for deployment)

## Credits

PWA-Text-Editor was developed by Leandro Mangubat.

Email: leandromangubat@hotmail.com

Github: [github.com/leandromangubat](https://github.com/leandromangubat)

## License

This project is licensed under the MIT License.
