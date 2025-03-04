# Euchre Card Game

### Developed by:  
- **Solo**  
- **Joey Brinker**  
- **Karina Mireles**  

## Overview  
This is a digital implementation of the classic trick-taking card game **Euchre**, written in Swift. The game simulates a four-player bot-based match, where players take turns playing cards, following the rules of Euchre. The goal is to win hands and score points as a team.  

## Features  
✅ A deck of 24 cards (9, 10, J, Q, K, A of each suit)  
✅ Automatic dealing to four players  
✅ Trump suit selection at random  
✅ AI-controlled players with logic to play valid cards  
✅ Hand and round winner determination  
✅ Scorekeeping system (first to 3 points wins)  
✅ ASCII-style announcement of hand and game winners  

## How to Play  
1. The game initializes with four AI players.  
2. A **random trump suit** is chosen for each round.  
3. Each player receives **5 cards** from the deck.  
4. Players take turns playing one card per trick.  
5. The player who plays the highest-ranking card wins the trick.  
6. The team that wins the most tricks in a round scores a point.  
7. The first team to reach **3 points wins the game!**  

## Running the Game  
To run the game, simply execute the **main.swift** file in a Swift-compatible environment like Xcode or Terminal using:  

```sh
swift main.swift
