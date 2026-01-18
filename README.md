# Fighting Game Decision Analyzer

This project explores learning high-level decision-making in fighting games by modeling player intent from match situations.

## Current Status (v0)
- Manual labeling of decision points from high-level gameplay
- Initial dataset stored as CSV (timestamped decisions)
- Baseline machine learning model (decision tree)
- Coarse action categories (poke, wait, approach, etc.)
- Currently focused on neutral decisions (starting with Ed, SF6)

Actively working and evolving

## Long-term Goal
- Phase-aware policy models (neutral / oki / defense)
- Matchup-conditioned decision prediction
- Real-time inference from gameplay footage

## Why this exists
First and foremost it's my personal project to sharpen my own Machine Learning and fighting games skills
Most fighting game analysis focuses on execution.
This project focuses on *decision-making* and actual intent of that decision.
The long-term goal is to build a system that can analyze gameplay and predict strong decisions, eventually in real time.
## How to run locally

Clone the repo:
```bash
git clone https://github.com/IDKFAs/fg-decision-analyzer
cd fg-decision-analyzer

