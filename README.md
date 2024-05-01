# Wordle Auto

Wordle Auto is a tool designed to solve Wordle puzzles using a greedy best-first searching algorithm. It generates a complete list solving all 2309 words.

## Usage

To use Wordle Auto:

1. Navigate to the directory containing the `Wordle.py` file.
2. Run the script using Python 3:

   ```bash
   python3 Wordle.py
## Directory Structure
/run_all/: Contains a list of all runs using various seed words (salet, soare, [raise clout nymph]) using all possible words in the heuristic functions.
/run_all_answers/: Uses the same seed words but only considers the answers list in the heuristic functions.
## How it Works
Wordle Auto employs a greedy best-first searching algorithm to solve Wordle puzzles. It iteratively generates guesses based on the feedback received from previous guesses, aiming to narrow down the solution space efficiently.

## Contribution
Contributions to Wordle Auto are welcome! If you have ideas for improvement or want to report issues, feel free to create a pull request or open an issue on the GitHub repository.
