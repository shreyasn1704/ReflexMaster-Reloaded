# ReflexMaster-Reloaded
ReflexMaster is a real-time Arduino-based reflex and memory game featuring three dynamic difficulty modes, multiplayer scoring, and instant feedback through LEDs, buzzer, and LCD. Designed to test speed, accuracy, and focus in a fun competitive setup.


---

## 📌 Key Highlights

- Three Dynamic Game Modes – Easy (Reflex), Medium (Memory Sequence), and Hard (Reverse Memory Challenge).

- Real-Time Interactive Feedback – LEDs, buzzer tones, and 16×2 I2C LCD provide instant visual and audio responses. 

- Multiplayer Scoring System – Supports up to 5 players with individual score tracking and winner detection.

- Adaptive Difficulty Engine – Reaction time, blink speed, and sequence length automatically adjust based on player performance.  


Inspired by a basic Arduino LED reaction game, ReflexMaster is my extended version with added game modes, scoring logic, multiplayer support, and real-time LCD feedback. 
 

---

## Platform

- Designed setup and simulated in Tinkercad



## Game Flow

1) Power ON & Init: Arduino sets up LEDs, buttons, buzzer, LCD; splash screen shows game title.

2) Menu Selection: Choose number of players (1–5), tries, and game mode (Easy/Medium/Hard); selections auto-confirm.

3) Player Setup: Scores, streaks, and lives reset; “Get Ready” shown.

4) Gameplay:

   - Easy: Press blinking LED within reaction time.

   - Medium: Repeat LED sequence in order.

   - Hard: Repeat LED sequence in reverse.
     
Difficulty adapts dynamically.

5) Scoring & Feedback: Updates score/streak/lives; LCD & buzzer give instant feedback.

6) Quit/Game Over: Long reset press quits; max wrong attempts ends game.

7) Winner Declaration: Highest score wins; tie handled; final message shown.

8) Return to Main Menu: Flags reset, ready for next round.


---



## 🎥 Simulation Video

[📺 Watch the video](<https://drive.google.com/file/d/1Trx0nZ9UGFgUraRSregWFIHMX0YnjzLS/view?usp=sharing>)

---

## 👩‍💻 Author

**Shreya S N**  
BTech ECE | GECK | APJAKTU  
2025  
