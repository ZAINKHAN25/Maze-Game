# Maze Game Readme

This repository contains a simple maze game implemented in JavaScript. Players navigate through a maze from the start point to the end point using arrow keys or swipe gestures. The game includes features such as customizable difficulty levels, a victory message display, and the ability to load custom sprites for the player and end point.


![Screenshot 2024-02-09 173609](https://github.com/ZAINKHAN25/Maze-Game/assets/121414309/3e89e5a8-e00c-470a-88b1-3966bee7620a)



## Getting Started

To get started with the maze game, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/maze-game.git
   ```

2. Open the `index.html` file in a web browser to play the game.

## Game Features

### Customizing Difficulty

You can customize the difficulty of the maze by selecting the difficulty level from the dropdown menu.

### Loading Custom Sprites

The game allows you to load custom sprites for the player and the end point. The provided example includes a key sprite for the player and a home sprite for the end point. You can replace these sprites with your own by modifying the `sprite.src` and `finishSprite.src` paths in the JavaScript code.

```javascript
sprite.src = "./path/to/your/player-sprite.png";
finishSprite.src = "./path/to/your/end-sprite.png";
```

Make sure to set the appropriate paths for your custom sprites.

### Resizing the Maze

The game is responsive, and the maze adjusts its size based on the dimensions of the container element (`#view`). You can resize the window, and the maze will adapt accordingly.

## Technical Details

The maze game is implemented using HTML, CSS, and JavaScript. The key functions and components include:

- **Maze Generation:** The maze is dynamically generated using a randomized depth-first search algorithm.

- **Player Movement:** Players can navigate through the maze using arrow keys or swipe gestures.

- **Sprite Customization:** Custom sprites for the player and end point can be loaded and adjusted for brightness.

- **Responsive Design:** The game adapts to different screen sizes, providing a consistent experience on various devices.

## Contributing

Feel free to contribute to the project by creating issues, suggesting enhancements, or submitting pull requests. Your feedback and contributions are welcome!

## License

This maze game is open-source and available under the [MIT License](LICENSE).
