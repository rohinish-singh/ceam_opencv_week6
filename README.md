# 🐍 OpenCV Hand Tracking Snake Game

An interactive, real-time computer vision twist on the classic arcade Snake game. Instead of using a keyboard or controller, players use their webcam and hand gestures to control the snake, with the tip of their index finger acting as the snake's head! 

Built entirely in Python using **OpenCV** and **cvzone**.

## 🎥 Gameplay Demo

> **Gameplay Video:**
> 
> *[Replace this text with a link to your video, or use the syntax below to embed a local video/GIF]*
> 
> `![Snake Game Demo](path/to/your/video_or_gif.gif)`

---

## ✨ Features
*   **Real-Time Hand Tracking:** Uses `cvzone`'s HandTrackingModule to accurately follow the user's index finger.
*   **Dynamic Snake Body:** The snake's tail visually follows the path of the finger and grows as food is consumed.
*   **Alpha-Channel Overlays:** Supports transparent PNG images (like a donut) for food spawning.
*   **Self-Collision Detection:** Mathematically calculates point-in-polygon intersections to detect if the snake hits its own body, triggering a "Game Over."
*   **Live Score Tracking:** Real-time visual feedback for score and game states.

---

## 🛠️ Tech Stack & Dependencies
*   **Python 3.x**
*   **OpenCV** (`opencv-python`) - Core image processing, capturing, and drawing.
*   **cvzone** - Wrapper for Mediapipe to handle the hand detection and easy image overlays.
*   **NumPy** - Array manipulation for bounding boxes.
*   **Math & Random** - Standard Python libraries for coordinate geometry and food spawning.

---

