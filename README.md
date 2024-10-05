# Word Game 🎮

**Word Game** is a fun and interactive word-guessing Game inspired by the popular Wordle Game. The Game challenges players to guess a 5-letter word within six attempts. With intuitive Gameplay and responsive UI, Word Game offers a seamless gaming experience for players of all skill levels.

## Features
- 🔤 **5-Letter Word Puzzle**: Guess the word within six attempts.
- 🌀 **Interactive UI**: Provides visual feedback for correct, close, and wrong guesses.
- ⏳ **Loading Spinner**: Fetches the word of the day from an API, ensuring fresh content daily.
- 💻 **Keyboard Interaction**: Type guesses using your keyboard, with support for Enter and Backspace.
- 🎨 **Color Coded Feedback**: 
  - **Green** for correct letters in the correct position.
  - **Yellow** for correct letters in the wrong position.
  - **Gray** for incorrect letters.
- 🎉 **Winner Animation**: Celebrate victories with a rainbow effect animation.
- 🔄 **Responsive Design**: Optimized for both desktop and mobile screens.

## Demo
You can play the game live [HERE](https://youssehf.github.io/word-game/)

## Technologies Used
- **HTML5**: Structure of the web page.
- **CSS3**: Styling and animations.
- **JavaScript (ES6)**: Game logic, DOM manipulation, and interaction.
- **API Integration**: Fetches the word of the day and validates guesses using a word validation API.

## Getting Started
Follow these steps to set up the project locally.


### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/youssehf/word-game.git
   ```
2. Navigate into the project directory:
   ```bash
   cd word-game
   ```
3. Open the project in your browser:
   - For local setup, just open the `index.html` file in any web browser.
   - You can also use a live server if you're using a code editor like VS Code.

### How to Play
1. The game fetches a random 5-letter word when you load the page.
2. Enter a word by typing and press **Enter** to submit your guess.
3. Use **Backspace** to delete a letter.
4. You have **6 attempts** to guess the word correctly.
5. The letters in your guess will change color to indicate:
   - **Green**: Correct letter and correct position.
   - **Yellow**: Correct letter but wrong position.
   - **Gray**: Wrong letter.
6. After 6 incorrect attempts, the correct word will be revealed.

### Game Controls
- **Enter**: Submit your guess.
- **Backspace**: Delete the last letter.
- **Keyboard Letters**: Type your guess.

## Screenshots
![word-game](https://github.com/user-attachments/assets/b40258f9-da63-4323-b219-20fb603d939b)

## Future Enhancements
- 🔢 Add difficulty levels with varying word lengths.
- 🎹 Add an on-screen keyboard for mobile users.
- 📊 Display statistics, such as win percentage and streaks.
- 📱 Improve mobile responsiveness.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m "Add a new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.
