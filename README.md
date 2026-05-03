# FNAF 1 — Discord Bot Edition

A fully playable Five Nights at Freddy’s remake inside a Discord bot.

This project recreates the core gameplay of Five Nights at Freddy’s 1 using Discord commands and an image-based UI.  
It is a fan-made, non-commercial project created purely for fun.

All credits for the original game go to Scott Cawthon.

<img width="468" height="281" alt="image" src="https://github.com/user-attachments/assets/e64602fe-bd8e-4f64-b01b-9e56ce3253be" />

---

## Features

- Camera system with multiple rooms  
- Door controls (left and right)  
- Light controls (left and right)  
- Ability to return to the desk at any time  
- Night selection (1–6)  
- Uses static images to simulate the FNAF experience  
- Written in Python using `discord.py`  

---

## Getting Started

### Requirements

- Python 3.10 or higher  
- `discord.py` installed  
- A Discord bot token  
- A server where you can invite your bot  

---

## Installation

```bash
git clone https://github.com/rookmelder/FNAF-discord-bot
cd FNAF-discord-bot
pip install -r requirements.txt
```

---

## Running the Bot

Add your bot token to the script (or use an environment variable), then run:

```bash
python main.py
```


---

## How to Play

Use the following commands in any channel where the bot is allowed to respond:

- `!start [night]` — Start the game (default is night 1)  
- `!stop` — Stop the game *(important: the game does not stop automatically)*  
- `!l <l/r>` — Toggle the left or right light  
- `!r <l/r>` — Toggle the left or right door  
- `!desk` — Return to the desk  
- `!c <camera>` — Switch to a specific camera  

## Project Structure

FNAF-discord-bot/
│
├── main.py        # Main bot logic
├── classes.py     # Game classes and logic
├── pics/          # All images used for the game
└── README.md

## Disclaimer

This is a fan project.

If you are the copyright holder and want this removed, contact me and I will take it down.

### Contact

If you have questions or suggestions, you can reach me on Discord:
rookmelder
