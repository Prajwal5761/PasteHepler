
# PasteHelper

PasteHelper is a simple web application built using React and Vite that helps users store their copied content in the browser's local storage for future reference. This makes it easy to access previously copied content without losing it when navigating between different applications.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Features

- Automatically saves copied content from the clipboard.
- Displays the copied content in a list.
- Stores content in the browser's local storage for persistence across sessions.
- Option to clear saved content.

## Tech Stack

- **Frontend:** React (with hooks)
- **Build Tool:** Vite
- **Storage:** Browser Local Storage

## Installation

Steps to install and run the project on your local machine.

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/pastehelper.git
   cd pastehelper
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the development server:**

   ```bash
   npm run dev
   ```

4. **Build for production:**

   ```bash
   npm run build
   ```

## Usage

1. Copy text from anywhere on your system.
2. PasteHelper automatically captures the copied content and stores it in the local storage.
3. Access and view your saved copied content on the app.
4. Clear the content list using the clear button if needed.

## Project Structure

```bash
.
├── public              # Static assets
├── src                 # Source files
│   ├── components      # React components
│   └── styles          # CSS styles
├── index.html          # Main HTML file
├── package.json        # Project metadata and dependencies
└── vite.config.js      # Vite configuration
```

## Contributing

Guidelines for contributing to the project:

- Fork the repository.
- Create a new branch (`git checkout -b feature-branch`).
- Make your changes and commit (`git commit -am 'Add new feature'`).
- Push to the branch (`git push origin feature-branch`).
- Create a Pull Request.

