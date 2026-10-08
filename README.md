# Cricket Statistics Analyzer

A Python-based cricket statistics analysis system and automated algorithmic verification suite developed for international cricket player records.

## Features
- **Player Database**: Comprehensive record of 70+ international cricket players stored in JSON format (`data/players.json`).
- **Searching Algorithms**:
  - Linear search by player role (Batsman, Bowler, All-Rounder, Wicket-Keeper).
  - Recursive binary search by player name.
- **Sorting Algorithms**:
  - Custom Bubble Sort algorithm to rank players by runs, wickets, batting average, strike rate, and more.
- **Advanced Metrics & Analytics**:
  - Batting and Bowling averages
  - Strike rate & Economy rate
  - Boundary percentage calculation
  - Custom Player Impact Score
  - Head-to-head comparison cards between any two players
- **Report Generation**: Export analysis summaries to text format (`cricket_analysis_export.txt`).
- **Automated Verification**: Built-in test suite verifying all algorithms and calculations.

## Project Structure
```text
cricket_analyzer/
├── cricket_analyzer.py          # Main interactive analyzer & verification entry point
├── test_analyzer_cricket.py     # Core algorithms, utility functions, and test suite
├── cricket_analysis_export.txt  # Exported statistical summary report
├── README.md                    # Project documentation
├── .gitignore                   # Git configuration
└── data/
    └── players.json             # Dataset containing 70+ international player statistics
```

## How to Run

### 1. Interactive Mode
Run the main program to launch the interactive terminal menu:
```bash
python cricket_analyzer.py
```

### 2. Automated Test Suite
Run the automated verification suite to validate all search, sort, and statistical algorithms:
```bash
python cricket_analyzer.py --test
```
or:
```bash
python test_analyzer_cricket.py
```
