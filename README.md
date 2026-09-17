Stone, Paper, Scissor Game (C++)
A interactive command-line application of the classic "Stone, Paper, Scissors" game built using C++. This project was developed as a milestone to apply structured programming principles, logic building, and clean code practices.

🚀 Features
Multi-round System: Players can choose to play from 1 to 10 rounds per game.
Dynamic AI Competitor: The computer makes randomized, unpredictable choices.
Real-time Visual Feedback: The console screen color changes dynamically based on the round result (Green for Win, Red for Loss with an audio alert, and Yellow for a Draw).
Detailed Game Analytics: Provides a comprehensive breakdown of the game stats at the "Game Over" screen, including total rounds, player wins, computer wins, draws, and the ultimate winner.
Replayability: Users can easily restart the game or reset settings seamlessly without closing the application.
🛠️ Concepts & Technical Skills Applied
Structured Programming: Clean separation of concerns using functional programming principles.
Data Structures: Leveraged Custom struct definitions (stRoundInfo, stGameResult) to manage and pass game states efficiently.
User-Defined Types: Used enum (enGameSituation, enGameChoice) to improve code readability and maintainability.
Randomization: Utilizing srand() and time() to generate secure and pseudo-random computer decisions.
CLI UX/UI Enhancement: Implementation of system command controls (system("Color"), system("cls")) to create an interactive user experience.
💻 How to Run
Clone the repository or download the source code.
Open the file in any C++ IDE (like Visual Studio).
Compile and run the main.cpp file.
