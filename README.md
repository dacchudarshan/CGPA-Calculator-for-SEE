# CGPA-Calculator-for-SEE
A simple command-line CGPA (Cumulative Grade Point Average) calculator for students appearing in Scheme of Examination (SEE) exams.

## Features

- 🎓 Calculate CGPA based on expected grades
- 📊 Support for all grade types (S, A, B, C, D, E)
- 🔢 Credit-weighted calculations
- ✨ Interactive command-line interface

## Grade Scale

| Grade | Points |
|-------|--------|
| S     | 10     |
| A     | 9      |
| B     | 8      |
| C     | 7      |
| D     | 6      |
| E     | 5      |

## Requirements

- Python >= 3.10

## Installation

1. Clone the repository and navigate to the project directory.

2. Set up a virtual environment (optional but recommended):
```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Install dependencies (if using Poetry):
```bash
poetry install
```

2. Set up a virtual environment (optional but recommended):
```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Install dependencies (if using Poetry):
```bash
poetry install
```

## Usage

Run the calculator:
```bash
python3 main.py
```

Follow the interactive prompts:
1. Enter the total number of subjects (including labs)
2. For each subject, provide:
   - Subject name
   - Credits
   - Expected grade (S/A/B/C/D/E)

The calculator will then display your calculated CGPA.

## Example

```
🅲 🅶🅿 🅰   🅲🅰 🅻 🅲 🆄 🅻🅰 🆃🅾 🆁

Welcome to CGPA Calculator Brought to you by Drashan❤

Total number of Subjects appearing Including Labs:- 3
1.Subject Name - Data Structures
How many Credits does Data Structures Hold? - 4
What is your expected Grade? A

2.Subject Name - Database Systems
How many Credits does Database Systems Hold? - 3
What is your expected Grade? S

3.Subject Name - Web Development Lab
How many Credits does Web Development Lab Hold? - 2
What is your expected Grade? B

Your CGPA according to your Expected Grades is 8.67.
Thank you😊❤️
```

## Project Structure

```
CGPA-Calculator-for-SEE-main/
├── main.py                 # Main calculator script
├── pyproject.toml          # Project dependencies
├── replit.nix              # Replit configuration
└── README.md               # This file
```

## Author

Created by Drashan ❤

## License

This project is open source and available under the MIT License.
