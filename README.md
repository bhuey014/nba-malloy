# 🏀 NBA Trends Through Malloy (2010–2024)

## Overview
This project uses Malloy to analyze NBA regular season data from 2010 to 2024. 
The goal was to explore how the game has changed over 14 seasons — from which 
teams dominated, to the rise of the 3-point shot, to the era's best scorers.

## The Problem
The NBA looks completely different than it did in 2010. More threes, different 
stars, faster pace. I wanted to use real data to see if that was actually true 
or just perception. This dataset gave me 14 seasons of player and team stats 
to find out.

## How It Works
- `regular_season_totals_2010_2024.csv` — used for team-level queries
- `regular_season_box_scores_2010_2024_part_1.csv` — used for player-level queries
- `nba.malloy` — contains the source definitions and all queries
- `nba_story.malloynb` — the narrative notebook telling the full story

## Key Findings
- The Golden State Warriors had the most wins (676) from 2010–2024
- 3-point attempts nearly **doubled** from 18 per game in 2010 to 34+ by 2020
- 3-point shooting **percentage** stayed flat around 35% — teams shoot more, not better
- Luka Doncic leads all players in scoring average (28.3 ppg) among players with 100+ games

## What I Learned
I was surprised that 3-point accuracy barely moved while attempts nearly doubled. 
That means the entire strategic shift wasn't about getting better at shooting threes 
— it was a philosophical change in how the game is played. Malloy made it easy to 
explore these trends across 14 seasons of data quickly.

## Who Would Care
NBA front offices, coaches, and analysts would find this useful for understanding 
long-term strategic trends. Sports journalists and fans curious about how the 
modern game evolved would also find value here. The 3-point volume trend in 
particular could inform decisions about how to build a roster or defend against 
modern offenses.

## How to Run
1. Install [Malloy VS Code Extension](https://marketplace.visualstudio.com/items?itemName=malloydata.malloy-vscode)
2. Clone this repo
3. Open `nba_story.malloynb` in VS Code
4. Click "Run All"

## Data Source
[NBA Data 2010–2024 by NocturneBear](https://github.com/NocturneBear/NBA-Data-2010-2024)