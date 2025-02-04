# Interactive Portfolio

<p>
  <img src="https://img.shields.io/badge/PlayCanvas-FF3300?logo=playcanvas&logoColor=white&style=for-the-badge" height="30">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge" height="30">
  <img src="https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white&style=for-the-badge" height="30">
  <img src="https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white&style=for-the-badge" height="30">
</p>

## Overview

This is an interactive portfolio built using [PlayCanvas](https://playcanvas.com). It provides a first-person experience where users can explore a virtual space and interact with objects that showcase projects I’ve worked on.
All 3D models and assets in this project were created using Blender and reflect some of the objects I have in my own personal space.

![Home Page](./Resources/InteractivePortfolio-StartMenu-1.gif)

---

## Features

### First-Person Navigation
- Users can move around in a 3D environment using first-person controls.

![Home Page](./Resources/InteractivePortfolio-FirstPerson.gif)

### Interactive Objects
- Each object represents a project and displays a UI text when interacted with, explaining what the object represents and what tools were used to develop it.
- Interactions trigger actions such as sending a message to a Post API, which opens an HTML page that overlays the interactive portfolio or viewing a pdf file like my resume.

![Home Page](./Resources/InteractivePortfolio-Interactive.gif)

### Project Representations
- **Arcade Machines & Screens**:  
  - Some objects, like arcade machines and screens, display videos related to the project they represent using an open source script develop by PlayCanvas community members.
  - Clicking these objects provides detailed insights into the projects, but the logic of that is handled using an HTML page that isn't included in this repository.

- **Other Objects**:  
  - Objects like files represent external resources, such as a resume, and link to external pages.

![Home Page](./Resources/InteractivePortfolio-HTMLConnect.gif)

## How It Works
1. Navigate the environment using standard first-person controls.
2. Approach and interact with objects to learn about different projects.
3. Click on objects to trigger Post API messages that open an HTML overlay or external pages for more detailed information.

## Technologies Used
- **PlayCanvas**: The primary engine for the interactive environment.
- **JavaScript**: For scripting object interactions and API communication.

## Future Improvements
- Enhancements to object interactions and animations.
- Additional projects and representations in the portfolio.

## Acknowledgments
This project is designed as a fun way to showcase my portfolio, combining interactivity with a visually engaging experience, which has always been the way I wanted my work to be viewed.
If you want to try it for yourself, visit: https://tyradman.github.io/interactive-portfolio/

---
