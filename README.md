# Interactive Portfolio

<p>
  <img src="https://img.shields.io/badge/PlayCanvas-FF3300?logo=playcanvas&logoColor=white&style=for-the-badge" height="30">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge" height="30">
  <img src="https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white&style=for-the-badge" height="30">
  <img src="https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white&style=for-the-badge" height="30">
</p>

## Overview

This is an interactive portfolio built using [PlayCanvas](https://playcanvas.com). It provides a first-person experience where users can explore a virtual space and interact with objects that showcase projects I’ve worked on.
All 3D models and assets in this project were created using Blender and reflect some of the objects I have in my own personal space :)

<p align="center">
  <img src="./Resources/InteractivePortfolio-StartMenu-1.gif" width="75%" height="auto" alt="Loading GIF..." loading="lazy">
</p>

---

## Links
Link to portfolio: [link](https://tyradman.github.io/interactive-portfolio/)

---

## Features

### First-Person Navigation
Users can move around in a 3D environment using first-person controls.

<p align="center">
  <img src="./Resources/InteractivePortfolio-FirstPerson.gif" width="75%" height="auto" alt="Loading GIF..." loading="lazy">
</p>

---

### Interactive Objects
Each object represents a project -or a set of small projects- and displays a UI text when interacted with, which prints the information about the project.

<p align="center">
  <img src="./Resources/InteractivePortfolio-Interactive.gif" width="75%" height="auto" alt="Loading GIF..." loading="lazy">
</p>

---

### Projects HTML Display

Clicking on the interactive objects provides more details about the projects by overlay the 3D environment with an HTML page. The logic of the HTML, CSS, and JS of the external pages isn't included in this repository.

<p align="center">
  <img src="./Resources/InteractivePortfolio-HTMLConnect.gif" width="75%" height="auto" alt="Loading GIF..." loading="lazy">
</p>

---

## How It Works
- The interactions in the experience is handled using PlayCanvas' API to control the character, Camera, rays (for looking at object) and more.
- Displaying videos on textures is done using [this shader](https://developer.playcanvas.com/tutorials/video-textures/) provided by PlayCanvas on their website.
- Interactions with clickable objects trigger actions like sending a message to a Post API, which opens the HTML page that overlays the interactive page or viewing a pdf file like my resume.
- Clicking outside the bounds of the HTML overlay hides the page and returns control to the interactive experience.

## Technologies Used
- **PlayCanvas**: The primary engine for the interactive environment.
- **JavaScript**: For scripting object interactions and API communication.

## Future Improvements
- Add animations to interactive objects.
- Additional projects and representations in the portfolio.


---
