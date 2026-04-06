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

## Features

- Interactive command-line interface (no external UI)
- Multiple categories loaded from data/questions.json
- Configurable number of questions per session
- Multiple-choice questions with immediate feedback and explanations
- Progress bar and score summary at the end
- Small utility helpers for colored output (src/colors.js)
- Easy-to-edit JSON question store for extensibility

## Prerequisites

- Node.js >= 18.0.0 (project sets engines: node >= 18.0.0)
- No additional dependencies; uses builtin Node.js APIs

## Installation

1. Clone the repository:

```bash
git clone https://github.com/reshetnev/test-app.git
cd test-app
```

2. Install dependencies (none required) and ensure Node.js >= 18 is installed. You can verify Node version with:

```bash
node --version
```

3. (Optional) Run the app with npm scripts (see below) or directly with node:

```bash
npm start
# or
node index.js
```
