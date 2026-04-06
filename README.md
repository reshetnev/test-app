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

## Development

Source code location:

- Entry point: index.js (CLI)
- Core modules: src/
  - src/input.js — wrapper around readline for prompts
  - src/quiz.js — Quiz class and quiz logic
  - src/colors.js — ANSI color helpers
- Data: data/questions.json — question categories and content

To run locally during development:

```bash
node index.js
```

If you'd like to iterate on code and test changes quickly, run the command repeatedly; there is no watcher configured. Ensure your Node version matches the engines requirement in package.json (>= 18.0.0).

Recommended developer notes:
- Keep data/questions.json valid JSON when editing.
- The application uses only built-in Node APIs, so there are no additional dev dependencies to install.
