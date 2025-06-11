## 🎮 Fruit Catch Game

### 📝 Description  
A simple and fun game where the player controls a basket to catch falling fruits.  
Built in ARM assembly for STM32, rendered on a TFT LCD. Each caught fruit increases the score; missing fruits reduces chances.

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
