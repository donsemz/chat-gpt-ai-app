# A simple app using the OpenAI api for answering questions

## The app is built using:
HTML, CSS, JS, Vite, NodeJS and OpenAI API

## The app demonstrates:
Project Setup using Vite
Server side code with NodeJS
Responsiveness with pure CSS
Events using JS
Render Markdown from strings
Prism for code highlighting
Make API requests
Error Handling
Clean SOLID Principles in coding

## Project Summary
This code is for a chatbot. It imports two images, one for the user and one for the bot. It then creates a form element and a chat container element. It then defines functions to load dots while waiting for a response from the bot, type out the text of the bot's response, generate a unique ID, and create a chat stripe (a line of text in the chat). Finally, it adds an event listener to the form so that when it is submitted or when enter is pressed, it calls the handleSubmit function. The handleSubmit function takes in user input from the form and adds it to the chat container as a user chat stripe. It then generates a unique ID and adds an empty bot chat stripe with that ID to the container. It then calls loader() on that empty stripe to add dots while waiting for a response from the bot. When it receives that response, it clears any loading dots and types out the bot's response using typeText().

