# Personal Introduction Program

## Project Overview
A beginner Python program that asks the user for their name, age and favorite hobby, then displays a personalized welcome message. Built as part of The Developers Arena Python task. The code was developed and tested in Google Colab.

## Setup Instructions
**Option 1: Google Colab (used for development)**
1. Open https://colab.research.google.com and create a new notebook.
2. Paste the contents of `personal_intro.py` into a code cell.
3. Run the cell and answer the three questions.

**Option 2: Run locally**
1. Install Python 3.8 or newer from https://www.python.org/downloads/
   (On Windows, tick "Add Python to PATH" during installation.)
2. Clone this repository:
   `git clone https://github.com/medha-mishra/<repo-name>.git`
3. Open the folder in a terminal:
   `cd <repo-name>`
4. Run the program:
   `python personal_intro.py`

No extra packages are needed. See `requirements.txt`.

## Code Structure
- `personal_intro.py`: the main program
  - `ask()`: helper function that asks a question and rejects empty answers
  - Main section: prints the header, collects the three answers, and prints the welcome message
- `requirements.txt`: dependency list (none required)
- `screenshot.png`: sample run of the program in Google Colab

## Sample Output
What is your name? Medha
How old are you? 19
What is your favorite hobby? exploring nature
Welcome, Medha!
You are 19 years old and you love exploring nature.
We're happy to have you here. Have a great day!

Screenshot.png
https://docs.google.com/document/d/104o1OJ_Q-wB6JRfUEi-aXhTi8LEo4pItGi8g45YMTQg/edit?usp=drivesdk
