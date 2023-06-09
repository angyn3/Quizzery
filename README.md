# Quizzery

### 1. Summary
This is a quiz about JavaScript basics written in JavaScript. It features 20 multiple-choice-questions, a 60 second timer, and a local leaderboard.

### 2. Features
#### 2.1 Landing page
The landing page features a short introductory text that explains the game and a button to start the game. You can also access the local leaderboard from the landing page by clicking "View leaderboard."

#### 2.2 Quiz pages
Once the game has been started, a countdown timer in the upper right corner of the screen indicates the remaining time. The player has 60 questions to answer as many questions as possible. There are 20 questions to be played. Once the timer is at 0 or all questions have been played, the game is over. The player gets visual feedback below the questions after answering each question indicating if their choice was correct or not.

#### 2.3 Highscore page
Once the game is over, a summary of the game is displayed indicating the number of correctly answered questions.
The user can also enter their initials in order to log their game to the local leaderboard. This information is being stored in the local storage of the application and will be available also after reloading the page. There is a validator in place to make sure the user does not submit empty initials.

#### 2.4 Leaderboard
The leaderboard can be accessed from after the game is played as well as from the landing page. It displays all players in the order of the games played locally.

### 3. External APIs, Libraries, and Frameworks 
This application uses Bootstrap, utilizing responsive Styles and components. More information about Bootstrap is available under https://getbootstrap.com with documentation under https://getbootstrap.com/docs/4.5/getting-started/introduction/
