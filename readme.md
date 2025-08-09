<img width="3188" height="1202" alt="frame (3)" src="https://github.com/user-attachments/assets/517ad8e9-ad22-457d-9538-a9e62d137cd7" />


# Popping Game 🎯


## Basic Details
### Team Name: Ex CoDe


### Team Members
- Team Lead: Mohammed Shan -  College of Engineering Munnar
- Member 2: Akshay B Arjun - College of Engineering Munnar
- 
### Project Description
This project is a **two-player bubble-popping game** that uses **webcam-based fingertip tracking** via MediaPipe to let players pop bubbles in real time.  
Players compete on split-screen, earning points for popping their own bubbles and losing points if they pop the opponent’s, with a timer and restart feature built-in.

### The Problem (that doesn't exist)  
In today’s fast-paced world, there’s a tragic shortage of competitive, finger-powered bubble-popping games that let two people battle for virtual bubble dominance from opposite sides of the same screen.  
Without this game, countless bubbles float around unpopped, and people are forced to endure the unbearable boredom of _not_ frantically waving at their webcams.

### The Solution (that nobody asked for)
Using advanced fingertip tracking, we let players annihilate innocent virtual bubbles in the name of fun and bragging rights — complete with point stealing, dramatic countdowns, and a restart button you can press _without touching your keyboard_.  
Finally, your fingers have the purpose they never knew they needed.

## Technical Details
### Technologies/Components Used
For Software:
- HTML, CSS, JavaScript
- None (pure vanilla JS)
- MediaPipe Hands for fingertip detection
- Web browser with webcam support, VS Code

For Hardware:
- Webcam (built-in or external)
- Minimum 720p resolution recommended for better tracking accuracy
- Computer or laptop, stable lighting conditions for the camera to detect hands

### Implementation
For Software:
**For Software:**

1.  **Setup Screen** – Players enter their names, choose the number of players, and set game time.
    
2.  **Game Screen** –
    
    -   Split-screen layout with player names and scores on opposite sides.
        
    -   Random bubble spawning in both halves of the screen.
        
    -   MediaPipe Hand Tracking to detect fingertip positions.
        
    -   Collision detection to pop bubbles of the correct color (gain points) or wrong color (lose points and give them to the opponent).
        
    -   Countdown timer at the top center, turning red in the last 5 seconds.
        
3.  **End Screen** – Displays winner and shows a **Restart button**.
    
4.  **Restart with Fingertip** – Players can hover their fingertip over the Restart button for 1 second to return to the setup screen without touching the mouse or keyboard.
# Installation
     https://akshaybarjun.github.io/poppinggame/

### Project Documentation
For Software:
### Project Documentation  
#### For Software:

- **Overview:**  
  The software enables a multiplayer real-time game that detects players’ fingertips via webcam using MediaPipe Hands. Players pop floating shapes by touching them with their fingertips on their side of the screen.

- **Components:**  
  - **User Interface:** Setup screen, game screen with scores and timer, end screen with results and replay options.  
  - **Hand Tracking:** MediaPipe Hands library to detect fingertip positions.  
  - **Game Logic:** Shape spawning, scoring system with penalties and bonuses, timer countdown.  
  - **Collision Detection:** Checks if fingertip coordinates intersect with shape bounding boxes to register pops.  
  - **Audio Feedback:** Plays sounds for popping and penalties.  
  - **Visual Feedback:** Animations for floating score text and flashing score panels.  

- **Flow:**  
  1. Player inputs names and game duration, then starts the game.  
  2. Countdown timer runs, followed by active gameplay with shapes spawning.  
  3. Players pop shapes by hovering their index fingertips over shapes.  
  4. Scores update live, with penalties applied if players pop opponent’s shapes.  
  5. When timer ends, game shows winner and options to replay or reload names.

- **Key Libraries/Tools:**  
  - MediaPipe Hands for hand/fingertip detection.  
  - Native Web APIs for DOM manipulation, audio, and animations.  

- **Limitations:**  
  - Requires camera access and good lighting.  
  - May have reduced accuracy with overlapping or fast hand movements.  

- **Extensibility:**  
  Modular design enables adding new shapes, power-ups, or multiplayer networking in future versions.

# Screenshots (Add at least 3)
<img width="1866" height="925" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/69b017b3-85dc-4edc-ab79-9d98efcc7d42" />
<img width="1920" height="891" alt="Screenshot 2025-08-09 083416" src="https://github.com/user-attachments/assets/3bee7c29-a131-4e2e-b617-557e990036a8" />
<img width="1920" height="912" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/c728754a-401d-43ad-b448-aa28ad6be720" />

## Team Contributions
- Akshay B Arjun : Web Design and Developing 
- Muhammed Shan : Prompt Generation and Creative Idea producer

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--25-25?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)



