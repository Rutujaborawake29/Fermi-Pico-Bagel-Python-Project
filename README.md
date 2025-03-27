# Fermi Pico Bagel - Number Guessing Game 🎲  

## 📌 Overview  
Fermi Pico Bagel is a fun number-guessing game where the player attempts to guess a secret number using logical hints. The hints provided—*Fermi*, *Pico*, and *Bagel*—help the player refine their guesses.  

- **Fermi** 🔴: A digit is correct *and* in the correct position.  
- **Pico** 🟡: A digit is correct but *not* in the correct position.  
- **Bagel** ⚫: No correct digits.  

## 🎯 Game Objective  
Guess the secret number by analyzing the hints provided for each attempt. The game continues until the player correctly guesses the number.  

## 📜 Rules  
1. The secret number consists of **three unique digits**.  
2. The player enters a **three-digit** guess.  
3. The game provides hints based on the player's guess:  
   - `"Fermi"` if a digit is in the correct position.  
   - `"Pico"` if a digit is in the secret number but in the wrong position.  
   - `"Bagel"` if no digits match.  
4. The game repeats until the player correctly guesses the number (all `"Fermi"` responses).  

## 🏗️ Project Structure  
The game is implemented in Python and structured in the following steps:  
- **Step 1**: Define the secret number (`original_number`).  
- **Step 2**: Take user input (`guess_number`).  
- **Step 3**: Validate input length.  
- **Step 4**: Check for duplicate digits.  
- **Step 5**: Generate hints using `"Fermi"`, `"Pico"`, and `"Bagel"`.  
- **Step 6**: Loop until the player wins.  

## 🖥️ How to Run the Game  
1. **Clone this repository**:  
   ```bash
   git clone https://github.com/yourusername/Fermi_Pico_Bagel.git
   cd Fermi_Pico_Bagel
   ```
2. **Run the Python script**:  
   ```bash
   python fermi_pico_bagel.py
   ```
3. **Follow the prompts** to play the game.  

## 🏆 Example Gameplay  
```plaintext
Enter your guess: 297  
["Pico", "Pico", "Bagel"]  

Enter your guess: 429  
["Fermi", "Fermi", "Fermi"]  
🎉 You win! 🎉  
```

## 🔗 Related Resources  
- Play an online version: [Fermi Pico Bagel](https://communicrossings.com/html/js/pfb.htm)  
