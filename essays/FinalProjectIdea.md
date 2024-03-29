---
layout: essay
type: essay
title: "Final Project Idea"
date: 2022-11-01
labels:
  - Software Engineering
  - Meteor
---
# Project: Reverse Bingo
Team members: Jennie Parrott, Candace Huynh, Matthew Matsuo

## Overview
*The problem:* Educators face the challenge of keeping students engaged and effectively supporting their study habits. Traditional educational games like bingo, while useful, often fail to fully capture students' sustained interest or offer deep learning engagement. Reverse bingo introduces a novel twist on this classic, promising a more dynamic, strategic, and interactive learning experience. This approach aims to rekindle student enthusiasm for game-based learning, making study sessions more engaging and productive.

*The solution:* A reverse bingo app tailored for educational use, designed to captivate students’ interest and enhance classroom engagement. This app features customizable content to match curriculum requirements, supports real-time participation to foster a competitive learning environment, and offers analytics for educators to monitor progress. 

## Approach:
The reverse bingo app serves two main user groups: students and educators. Each group has distinct capabilities within the app to enhance the learning and teaching experience. Every player gets a card consisting of 25 squares with definitions to questions. The instructor generates a random question and reads it aloud. If the student can match the definition/answer on their bingo card to the question, they can mark the square the definition is on. The first student to mark five in a row wins.

Possible mockup pages include:
- Landing page
- Student home page
- Teacher home page
- Game page
- Question display page

## Use case ideas:
### User Registration and Login:
- Goal: Allow new users to create an account and existing users to log in.
- Steps: Users navigate to the landing page, choose to sign up or log in, and enter the required information.
  
### Joining a Game:
- Goal: Users can join an upcoming reverse bingo game.
- Steps: After logging in, users are taken to the dashboard where they can see a list of available games. They select a game to join and are placed in a game room.
  
### Playing the Game:
- Goal: Engage in the game 
- Steps: Players first log into the game using their credentials. After logging in, the player selects their role in the game, whether it’d be the gamehost or contestant. Depending on which role was selected, different pages will display. The gamehost or instructor will have access to add questions into the random generator pool as well as the randomizer button that will randomly display a question from the database once clicked. 
The contestant page will display a randomly generated five by five grid of “definitions” or “answers” to each trivial question provided by the gamehost in the initial setup of the game. Each contestant will answer the question currently displayed and mark the corresponding answer on their own grids. Assuming the contestant answers correctly, the objective of the game is to fill or match in five grids in a straight or diagonal row, like the traditional bingo game. 

## Beyond the basics:
### Viewing Scores and History:
- Goal: Users can view their past performance and game outcomes.
- Steps: On the profile page, users can see their game history, including wins and losses. Users can also view previous games in detail from the questions to the answers associated with them to better remember the concepts covered. 
