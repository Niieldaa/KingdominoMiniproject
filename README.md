# Miniproject for Med3 Image Processing-Robot Sensing - AAL (MED3A/ROB3)

# King Domino Score Calculator

This project is based on the board game **King Domino**.

The goal of the program is to calculate the total score of a player's board automatically using computer vision

## How it works
In King Domino, points are calculated by:
- Finding connected areas of the same terrain type (e.g. forest, water, field, etc.)
- Counting how many tiles are connected in each area
- Counting how many crowns are in that area

The score for each area is:

area size × number of crowns

The program analyzes the board, groups connected terrain tiles, counts crowns, and calculates the total score.

## Features

- Detects connected terrain areas
- Counts crowns in each area
- Calculates score automatically
- Simulates the scoring rules of King Domino

## Visuals
<img width="150" alt="image" src="https://github.com/user-attachments/assets/5a58d100-aab6-4999-b281-d9316f2292f3" />
<img width="150" alt="boardgame" src="https://github.com/user-attachments/assets/2bd54fdb-9fec-47ed-9661-9126791f6466" />
<img width="150" alt="Crown" src="https://github.com/user-attachments/assets/e8d8e5dc-6e49-4a14-80fd-cc6b10d87497" />
