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

## Configuration

Questions are stored in data/questions.json organized by categories. The structure is a JSON object with a "categories" map. Each category key maps to an object with metadata and an array of question objects.

Example structure (summary):

- data/questions.json
  - categories: {
    "javascript": {
      "name": "JavaScript Basics",
      "questions": [
        {
          "question": "What is ...?",
          "options": ["A", "B", "C"],
          "answer": 1,          // zero-based index of correct option
          "explanation": "Brief explanation..."
        }
      ]
    }
  }

How to add categories/questions:
1. Open data/questions.json.
2. Add a new key under "categories" (e.g., "htmlcss") with a "name" and "questions" array.
3. For each question provide: "question" (string), "options" (array of strings), "answer" (integer index into options, zero-based), and optional "explanation" (string).
4. Save and run the app; the new category will appear in the selection list.

Be careful to maintain valid JSON; a trailing comma or missing bracket will cause the app to fail while loading questions.
