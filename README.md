# 🏀 The Modern NBA Playbook: Did Playing Faster and Shooting More 3s Actually Win Games?

## Overview
This project uses Malloy to analyze 14 seasons of NBA regular season data (2010–2024).
The goal was to investigate whether the modern NBA's obsession with pace and 3-point 
shooting actually leads to more wins — and who pioneered it.

## The Problem
The NBA looks completely different than it did in 2010. More 3s, faster pace, higher 
scoring. I wanted to use real data to find out when that shift happened, who started it, 
and whether it actually won games.

## How It Works
- `regular_season_totals_2010_2024.csv` — team-level game data
- `regular_season_box_scores_2010_2024_part_1.csv` — player-level game data
- `nba.malloy` — all source definitions and queries
- `nba_story.malloynb` — the full 6 chapter narrative notebook

## The Story — 6 Chapters

### Chapter 1: The Game Got Faster
Points, possessions, and 3-point attempts all trended upward together from 2010–2024.

### Chapter 2: Who Pioneered It?
The Golden State Warriors and Stephen Curry led the 3-point revolution before 
everyone else caught on.

### Chapter 3: Did the 3-Point Revolution Actually Win Games?
Scoring more correlates with winning — but shooting more 3s alone doesn't guarantee it.

### Chapter 4: What Actually Predicts Winning?
Turnovers and assists are better predictors of winning than 3-point volume. 
The fundamentals still matter.

### Chapter 5: Who Mastered the Modern Game?
The Warriors sit at the top with the most wins — the team that pioneered the 
revolution also won the most games.

### Chapter 6: Who Benefited the Most?
Stephen Curry leads all players in 3-point attempts (9.3 per game). Luka Doncic 
is the highest scorer at 28.3 ppg. Nikola Jokic proves you don't need threes to dominate.

## Key Findings
- 3-point attempts nearly **doubled** from 18 per game in 2010 to 34+ by 2020
- The shift accelerated around **2015-16** — the Warriors' first championship season
- **Stephen Curry** and the **Golden State Warriors** pioneered the revolution
- Shooting more 3s doesn't guarantee winning — **turnovers and assists** predict wins better
- **Luka Doncic** (28.3 ppg) is the ultimate product of the modern NBA

## What I Learned
The most surprising finding was that 3-point volume doesn't strongly predict winning. 
Teams that shoot a lot of threes include both great and terrible teams. What separates 
winners is ball movement (assists) and taking care of the ball (turnovers). The 
revolution changed how the game looks — but not what makes a team great.

## Who Would Care
NBA front offices, coaches, and analysts would find this useful for roster building 
and strategic decisions. The finding that turnovers and assists predict winning better 
than 3-point volume could directly inform how teams prioritize player acquisitions.

## How to Run
1. Install [Malloy VS Code Extension](https://marketplace.visualstudio.com/items?itemName=malloydata.malloy-vscode)
2. Clone this repo
3. Open `nba_story.malloynb` in VS Code
4. Click "Run All"

## Data Source
[NBA Data 2010–2024 by NocturneBear](https://github.com/NocturneBear/NBA-Data-2010-2024)
