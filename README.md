# NARUTO - OpenVC Used Project

An interactive browser-based hand-tracking project inspired by Naruto and Sasuke powers.  
Built using **MediaPipe Hands**, this project detects both hands in real time through your webcam and triggers animated visual effects based on hand gestures.

## Features

- Real-time hand tracking using webcam
- Detects left and right hands separately
- Naruto power effect for left hand
- Sasuke power effect for right hand
- Smooth fade-in / fade-out animations
- Blue skeleton hand landmarks for tracking feedback
- Works directly in browser (no installation required)

## Demo Controls

| Gesture | Action |
|--------|--------|
| Left Hand Open | Activates Naruto Power |
| Right Hand Open | Activates Sasuke Power |
| Hand Closed / Removed | Power fades away |

## Tech Stack

- HTML5
- CSS3
- JavaScript
- MediaPipe Hands API

## Project Structure

```bash
project-folder/
│── index.html
│── assets/
│   ├── naruto.mp4
│   └── sasuke.mp4
│── README.md