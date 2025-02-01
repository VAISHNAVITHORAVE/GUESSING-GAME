
# 🎯 Guessing Game  

## 🔥 Features:  
✅ **Random Number Generation** – A new number is generated each time the game starts.  
✅ **User Input & Validation** – Ensures the user enters a valid number between 1 and 100.  
✅ **Hint System** – Provides hints if the guess is close to the correct number.  
✅ **Attempts Tracking** – Displays the number of attempts taken to guess the number.  
✅ **Best Score System** – Saves the lowest number of attempts using `localStorage`.  
✅ **Reset Functionality** – Allows users to restart the game without refreshing the page.  
✅ **Interactive UI** – Styled with CSS for a clean and responsive design.  

## 📜 How It Works:  
1. The game generates a **random number** between 1 and 100.  
2. The user enters a guess and clicks **"Submit Guess"**.  
3. The game provides feedback:  
   - "Guess a larger number" if the guess is too low.  
   - "Guess a smaller number" if the guess is too high.  
   - "You're very close!" if the guess is within 5 numbers.  
   - "🎉 Congratulations!" if the guess is correct.  
4. The game tracks **attempts** and updates the **best score** if a new record is achieved.  
5. Once the user guesses correctly, the **input and button are disabled**, and a **"Play Again"** button appears.  

## 🎮 Technologies Used:  
- **HTML** – Structure of the game.  
- **CSS** – Styling and layout.  
- **JavaScript** – Game logic, number validation, hints, and score tracking.  

This is a fun and interactive way to test your guessing skills while improving logic and problem-solving. 🚀
