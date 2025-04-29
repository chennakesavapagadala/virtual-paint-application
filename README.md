# ✋ Hand Gesture Drawing App using OpenCV & MediaPipe

This is a Python-based drawing application that allows you to draw, select shapes, and erase on the screen using hand gestures. It uses **OpenCV**, **MediaPipe**, and **NumPy** for real-time hand tracking and drawing.

## 📌 Features

- 🖍️ **Draw**: Draw freely on the screen with your hand.
- ✏️ **Line**: Draw straight lines by raising your index finger.
- 🔲 **Rectangle**: Draw rectangles with two points (start and end).
- ⚪ **Circle**: Draw circles with a starting point and radius.
- ❌ **Erase**: Erase drawn content with a simple gesture.
- 👆 **Tool Selector**: Choose between drawing tools using your hand gestures.

## 🛠️ Tech Stack

- Python
- OpenCV
- MediaPipe
- NumPy

## 🖼️ How It Works

This program allows you to:

- Select drawing tools (line, rectangle, circle, draw, and erase) by moving your hand to a specific area on the screen.
- Perform drawing and erasing actions with gestures like raising your index finger or creating shapes.
- Uses MediaPipe to detect hand landmarks and OpenCV for drawing on the screen in real-time.

## 📂 File Structure

hand-gesture-drawing/ ├── main.py # Main script for drawing app ├── tools.png # Image with tool icons (for selecting tools) ├── requirements.txt # Required libraries
