## Countdown Timer Game

An interactive timer-based game built with React, where players can test their concept on time against a timer, attempting to accurately predict the target  time. The game includes different difficulty levels

---

## Project Screen Shot(s)

<img width="1148" alt="countdown" src="https://github.com/user-attachments/assets/48e9a8da-abfe-403a-a8e9-cbd9d950ee6d">


---

## Features

- **Dynamic Player Names**: Players can change their names by clicking.
- **Multiple Difficulty levels**: challenges include varying target times.
- **Game Turns Log**: A log displays all the moves made during the game.
- **Real-time timer Management**:  The game tracks the remaining time in real-time and stops when the timer is close to zero or when stopped manually..
- **Result Modal**: Displays the player's score or a loss message based on performance.
- **Reset and Replay**: Players can reset the timer and replay each challenge as often as they want..
- **Fully Responsive UI**: The game interface adapts to different screen sizes.
- **Dynamic Status Updates**: Provides real-time status messages, indicating whether the timer is active or inactive.

---

## Installation and Setup Instructions

1. Clone down this repository.
2. Navigate to the project folder in your terminal.
3. Install dependencies:

   ```bash
   npm install
4. To run the application, use:
   ```bash
   npm start
5. open your browser and go to:
   ```bash
   http://localhost:3000

---

## Reflection

### Context
This project was built to practice React component composition, state management, and user interaction handling through timers and modals.

### What I Set Out to Build
I aimed to build a functional timer-based game using React where players can test their precision and reaction time, focusing on applying core React concepts and software development principles. The project was designed to enhance my understanding of:

  - **Component-based Architecture**: Breaking the game into reusable components like `Player`, `TimerChallenge`, and `ResultModal` for better organization and maintainability.
  
  - **State Management**: Using React's `useState` and `useRef` to hooks to handle timer control, player name input, and modal display logic.
  
  - **Event Handling**: Efficiently managing user interactions, such as starting/stopping the timer and resetting the game.
  
  - **Conditional Rendering**: Displaying the score or loss message dynamically based on player performance.

  - **UI/UX Design**: Focusing on a clean, user-friendly interface that’s responsive across devices, making the game intuitive to play.


### Challenges

**Timer Precision:** Maintaining precise countdown behavior was challenging, requiring careful control over intervals and rendering updates.
**Result Detection:** Ensuring accurate score calculation and timely modal display when the player stops the timer.
**Dynamic User Experience:** Managing multiple states simultaneously, including time updates, player inputs, and button toggles.


## Libraries and Frameworks Used

- **React**: Used to build the interactive user interface and manage the state of the game.
- **React Hooks**: For state management (useState) and handling component lifecycle.
- **CSS**: Custom styles are used to build the game interface and layout.
