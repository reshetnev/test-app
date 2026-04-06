# quiz-cli

An interactive command-line quiz game for learning JavaScript.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Available Scripts](#available-scripts)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Usage

Run the application with:

```bash
npm start
```

or:

```bash
node index.js
```

Typical flow (example prompts):

1. The CLI shows a banner and lists available categories (e.g., "JavaScript Basics", "Node.js Fundamentals", "General Programming").
2. You are prompted to select a category by number.
3. You are asked how many questions to attempt (choose a number up to the available questions).
4. The quiz begins. For each question the CLI shows:
   - Question text
   - A list of numbered options
   - A progress bar (e.g., [#####-----] 3/10)
5. You select an option by entering its number. The CLI shows immediate feedback (Correct / Incorrect) and an explanation if present.
6. After all questions, the CLI prints a summary with total score, percentage, performance message, and a short list of incorrect questions with correct answers.
7. You are asked whether you'd like to play again.

Notes:
- Inputs are numeric selections and simple confirmations. The app validates numeric selection and prompts until a valid choice is made.
- Errors while reading the data file will show a colored error message and exit.
