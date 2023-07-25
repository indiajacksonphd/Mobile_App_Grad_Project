# Mobile_App_Grad_Project: Endless Mario - Unity Game Replication Guide

## Introduction

Welcome to "Endless Mario"! This guide will walk you through the process of downloading Unity and replicating the game on your computer. "Endless Mario" is a flappy bird type game with Racoon Mario instead of the flappy bird. Let's get started!

## Prerequisites

Before you begin, ensure that you have the following installed on your computer:

1. Unity Game Engine: "Endless Mario" is built using Unity, so you'll need to have Unity installed to work on the project. You can download Unity for free from the official Unity website: https://unity.com/.

2. TextMeshPro Package: The game uses TextMeshPro for displaying the player's score. Unity's Package Manager will handle this automatically, so you don't need to download it separately.

## Getting Started

Follow these steps to download and replicate "Endless Mario" on your computer:

1. Download Unity:
   - Go to the Unity website: https://unity.com/.
   - Click on the "Get Unity" button.
   - Choose the "Personal" plan and click "Get started."
   - Follow the on-screen instructions to complete the installation.

2. Clone or Download the Project:
   - Clone the project repository using Git: https://github.com/indiajacksonphd/Mobile_App_Grad_Project
   - Download from my Amazon Web Services S3 bucket: https://lgphycloudlogs1.s3.amazonaws.com/GradProject_JACKSON_application_folder.zip
   - Download the project as a ZIP file and extract it to a location on your computer.

3. Open the Project in Unity:
   - Launch Unity on your computer.
   - Click on "Open" and browse to the location where you cloned or extracted the project.
   - Select the folder named "EndlessMario" and click "Select Folder" to open the project.

## Understanding the Project Structure

The project is organized into three main folders:

- **Assets**: Contains all the assets used in the game, such as scripts, sprites, and audio files.
- **Scenes**: Contains the game scenes. In this project, you'll find one scene named "GameScene" representing the game level.
- **Prefabs**: Contains prefab assets that can be reused in the scene.

## Making Changes and Testing

You can make changes to the game and test them by following these steps:

1. Open the "GameScene" by navigating to "Scenes" in the Project window and double-clicking on "GameScene."

2. To move Racoon Mario, open the "Player" object in the Hierarchy window and modify the "PlayerMovement" script attached to it.

3. To customize obstacle generation, open the "ObstacleGenerator" script attached to the "ObstacleGenerator" object in the Hierarchy window.

4. To change the appearance of obstacles, modify the "pipePrefab" GameObject found in the "ObstacleGenerator" script or edit the "Obstacle" Prefab directly.

5. To test the game, click on the Play button (▶) at the top of the Unity interface. This will launch the game in the Unity editor, allowing you to play and test your changes.

## Building the Game

Once you are satisfied with your changes and want to share the game, you can build it for various platforms. To build the game:

1. Click on "File" in the Unity menu bar.

2. Select "Build Settings."

3. Choose your target platform (e.g., Windows, Mac, Android, etc.).

4. Click "Build" and select a location to save the built game.

## Conclusion

Congratulations! You have successfully downloaded Unity and replicated "Endless Mario" on your computer. Have fun exploring the code and making your own modifications to the game. If you encounter any issues or have questions, feel free to seek help or resources online.

Enjoy the endless fun of "Endless Mario"!
