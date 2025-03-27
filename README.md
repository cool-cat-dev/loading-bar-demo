# Godot 4 Smooth Loading Bar Tutorial

This repository contains the completed code for my Godot 4 Smooth Loading Bar tutorial. This system provides a clean and professional way to handle scene transitions with a loading bar in your games.

## Features

- Smooth scene transitions with progress feedback
- Customizable loading bar visuals
- Global loading handler for easy implementation
- Example scenes to demonstrate functionality

## Getting Started

1. Clone or download this repository
2. Open the project in Godot 4.x
3. Run the title scene to see the loading system in action
4. Explore the code to understand how it works

## How to Use in Your Own Project

### Basic Implementation

1. Copy the `Globals/LoadingHandler.gd` to your project's autoload
2. Add the `loading_bar.tscn` scene to your project
3. Call the loading functions from your scene transitions
4. Customize the loading bar appearance as needed

### Extending Functionality

The system is designed to be extended with:
- Loading screen animations
- Tips or hints during loading
- Custom loading visuals
- Loading time statistics

## Project Structure

- `Globals/LoadingHandler.gd` - Core loading management script
- `Scenes/loading_bar.tscn` - The loading bar UI scene
- `Scenes/title.tscn` - Example title screen
- `Scenes/demo_level.tscn` - First example level
- `Scenes/demo_level_2.tscn` - Second example level
- `Scenes/exit.tscn` - Exit scene example
- `Scenes/player.tscn` - Player character

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Thank You!

Thank you for downloading this loading bar demo! I hope it helps improve the polish of your games. If you have any questions or issues, create an issue in this repo or comment on one of my videos.
