# Simple Music Player

Welcome to the Simple Music Player! This application allows you to play your favorite songs, navigate through your playlist, and view album art. Follow this guide to get started.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Requirements](#requirements)
5. [Known Issues](#known-issues)
6. [Future Improvements](#future-improvements)
7. [License](#license)

## Features

- Play, pause, and navigate through your music tracks.
- Display album art if available.
- Interactive progress bar to seek within the track.
- Playlist management to add and select tracks.

## Installation

### Prerequisites

Make sure you have Python installed on your system. You can download it from the [official Python website](https://www.python.org/).

### Clone the Repository

```bash
git clone https://github.com/yourusername/simple-music-player.git
cd simple-music-player

Install Required Packages
Install the required Python packages using pip:

bash
Copy code
pip install pygame pillow eyed3
Usage
Running the Application
To start the application, navigate to the directory where you cloned the repository and run:

bash
Copy code
python music_player.py
User Interface
Select Track: Click the "Select Track" button to browse and add a music file to your playlist.
Play/Pause: Click the "Play" button to start playing the selected track. The button will change to "Pause" during playback.
Next/Previous: Use the "Next" and "Previous" buttons to navigate through your playlist.
Song Library: Double-click a song in the list to load and play it.
Progress Bar: Click on the progress bar to seek to a different part of the track. The current and total time of the track are displayed below the progress bar.
Adding Tracks to the Playlist
Click on the "Select Track" button.
Browse and select the desired music file (supported formats: .mp3, .wav).
The selected track will be added to the playlist and will start playing automatically if no other track is currently playing.
Viewing Album Art
If the selected track contains embedded album art, it will be displayed on the canvas.

Requirements
Python 3.x
pygame
pillow
eyed3
Install the dependencies using:

bash
Copy code
pip install pygame pillow eyed3
Known Issues
The progress bar and time labels might not update in real-time on slower systems.
Limited support for audio formats other than MP3 and WAV.
Error handling for unsupported files and missing album art could be improved.
Future Improvements
Support for additional audio formats.
Enhanced error handling and user feedback.
Option to save and load playlists.
Improved UI with themes and customization options.
Integration with online music libraries and streaming services.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy your music experience with the Simple Music Player! If you encounter any issues or have suggestions for improvements, feel free to contribute or open an issue on GitHub.
