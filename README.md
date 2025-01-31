# RJJ Cricket Scorer
A C-based cricket scoring application that simulates a cricket match between two teams, updates a leaderboard, and saves match results. This project was developed as part of the 1st-semester C Programming course.
## Features
- **Match Simulation**:
  - Simulates a cricket match with two innings.
  - Allows users to input ball-by-ball details (runs, wickets, extras, etc.).
  - Calculates the target score for the second inning.
- **Leaderboard**:
  - Updates the leaderboard (`leaderboard.txt`) with the winning team's score.
  - Displays the current leaderboard with team names and their wins.
- **Match Results**:
  - Saves match details (team names, scores, and winner) in a file (`match_results.txt`).
- **User Authentication**:
  - Requires a username and password to access the application.
## How to Use
### Prerequisites
- A C compiler (e.g., GCC).
- Git (for cloning the repository).
### Steps to Run the Program
 **Clone the Repository**:
1.
bash
https://github.com/Jeevan-Shah/Cricket-Score-Board.git
Navigate to the Project Folder:
2.
bash
cd repository-name
Compile the Code:
3.
bash
gcc cricket_scorer.c -o cricket_scorer
Run the Program:
4.
bash
./cricket_scorer
5.
Login:
Use the following credentials:
Username: RJJ
Password: 2006
6.
Follow the On-Screen Instructions:
Start a new match by entering team names and the number of overs.
Simulate the match by entering ball-by-ball details.
View the leaderboard and match results.
