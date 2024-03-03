# React Comment App

## Overview
The React Comment App is a simple React application that displays comments with profile images and usernames. Each comment is rendered as a card with the profile image, username, and comment text.

## Languages
- **JavaScript**
- **HTML**

## Frameworks & Libraries
- **React**
## Project Structure
The project consists of the following files and directories:
- **`public/`**: Contains the `index.html` file where the React app is rendered.
- **`src/`**: Contains the React components and main app files.
  - **`src/App.js`**: The main component that maps over comments and renders `Card` components.
  - **`src/Card.js`**: Component that renders a comment card with `Header` and `Body`.
  - **`src/Header.js`**: Component for the header of the comment card, displaying profile image and username.
  - **`src/Body.js`**: Component for the body of the comment card, displaying the comment text.
  - **`src/commentData.js`**: Contains sample comment data with profile images, usernames, and comments.
  - **`src/index.js`**: The entry point of the React app, renders the `App` component into the root `div`.

## Notes
This is a learning project developed in the codeacademy.com react course.
