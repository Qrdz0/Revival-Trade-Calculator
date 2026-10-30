# Revival Trade Calculator

![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-success)

A lightweight, fast, and responsive trade calculator designed for virtual economies and revival communities. 

Instead of guessing if a trade is worth it, users can select items from both sides of a trade and instantly see the total RAP (Recent Average Price) difference. 

## Live Demo

You can view the live version here: `[Insert your GitHub Pages Link Here]`

## Features

- **Win/Loss/Fair Calculator:** Automatically compares the total value of both sides and displays a clear visual banner (Green for Win, Red for Loss, Gray for Fair).
- **Demand Multiplier:** Items in the database have a "Demand" stat. A demand of `1.5` increases the item's calculated value by 50%, reflecting real-world trading where rare items go for more than their raw RAP.
- **Real-time Search:** Quickly filter through massive inventories to find specific items.
- **Zero Dependencies:** Built entirely with Vanilla HTML, CSS, and JS. No React, no Node.js, no build steps required.
- **Retro Theme:** Uses a classic dark-mode and gold UI inspired by classic gaming communities.

## How to Use (For Developers)

This calculator is designed to be easily adapted for any game (Roblox, custom revivals, MMOs, etc.).

1. Clone or fork this repository.
2. Open the `items.json` file.
3. Replace the mock data with your own items using the format below.
4. Host it for free using GitHub Pages.

### `items.json` Format

To add an item, use the following JSON structure:

```json
[
    { 
        "id": 1, 
        "name": "Dominus Aureus", 
        "rap": 125000, 
        "demand": 1.5, 
        "image": "https://example.com/image.png" 
    }
]
