# Animal Clicker App

Welcome to the Animal Clicker App! This simple React application lets you add random animals to a list and interact with them by clicking on their images. Each click on an animal increases a heart icon's size, showing your love for the creature.

## How to Use

1. Click the "Add Animal" button to add a random animal to the list.
2. Each animal in the list is displayed with its image and a clickable heart icon.
3. Click on the animal's image to show your affection. The heart icon will grow with each click.

## Available Animals

The app features the following animals:
- Bird
- Cat
- Cow
- Dog
- Gator
- Horse

## Project Structure

The project is organized into two main components:

### 1. App Component

The `App` component manages the state of the animal list and renders the UI. It utilizes the `AnimalShow` component to display individual animals.

### 2. AnimalShow Component

The `AnimalShow` component represents an individual animal in the list. It displays the animal's image and a heart icon that grows with each click. The component is reusable and dynamic, making it easy to extend the list of available animals.

## SVG Images

SVG images for each animal are stored in the `svg` directory and imported dynamically based on the selected animal.

## Styling

Styling is applied through CSS files (`App.css` and `animalShow.css`) to ensure a visually appealing and user-friendly interface.

## Challenge Details

This project is part of a 30-day challenge from a Udemy course. The goal is to introduce learners to React by building a simple interactive application. The challenge covers topics such as state management, event handling, and component composition.

Feel free to explore, modify, and enhance the app as you continue your learning journey with React!
