<p align="center">
<img src="https://github.com/user-attachments/assets/8fe0ff78-ccdc-4a70-b6f6-908536f3a6e0" width="300">
</p>

<h1 align="center"> 
Fruit Catch Game
</h1>

<p align="center">
A simple and fun game where the player controls a basket to catch falling fruits.  Each caught fruit increases the score; missing fruits reduces chances.
</p>

---
## 🎮 Gameplay Showcase

Here’s a quick look at the game in action:
<p align="center">
<img src="https://github.com/user-attachments/assets/0a210db6-dc43-405f-af47-b780277bd623" width="500">
</p>

---

### 🕹️ Controls

| Button   | Action            |
|----------|-------------------|
| A_LEFT   | Move basket left  |
| A_RIGHT  | Move basket right |
| EXIT     | Exit game         |

---

### 🧩 Game Loop Structure  
1. Generate fruit at a random position  
2. Wait for user input  
3. Process input (move basket)  
4. Return to start of loop  

---

### 🧠 Logic Overview  
- Fruits fall vertically  
- Basket tracks horizontal movement  
- Collision detection checks if a fruit is caught  

---

### ❌ End Conditions  
- Reaching `max_score`  
- Exceeding `max_lose_score`  
- Exit input is received  
