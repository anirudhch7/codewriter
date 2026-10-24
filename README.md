# CodeWriter

CodeWriter is a web-based code editor that allows you to write HTML, CSS, and JavaScript code in real-time and see the output instantly. It provides a split-pane interface with live preview capabilities.

## Features

- **Live Code Preview**: See your changes reflected in real-time as you type
- **Triple Editor Layout**: Separate editors for HTML, CSS, and JavaScript
- **Syntax Highlighting**: Code syntax highlighting powered by CodeMirror
- **Local Storage**: Your code is automatically saved to local storage, so your work persists across browser sessions
- **Collapsible Editors**: Expand or collapse individual editor panes to focus on specific code
- **Material Theme**: Clean, modern interface with CodeMirror's Material theme

## Technology Stack

- **React** - Frontend framework for building the user interface
- **CodeMirror** - Versatile text editor implemented in JavaScript for the browser
- **react-codemirror2** - React wrapper for CodeMirror
- **Local Storage API** - For persisting code across sessions

## Installation

1. Clone the repository:
```bash
git clone https://github.com/anirudhch7/codewriter.git
cd codewriter
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The app will open in your browser at [http://localhost:3000](http://localhost:3000).

## Available Scripts

### `npm start`

Runs the app in development mode. The page will reload when you make changes, and lint errors will appear in the console.

### `npm test`

Launches the test runner in interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder. The build is optimized and minified for best performance.

### `npm run eject`

**Note: This is a one-way operation!**

Ejects from Create React App, giving you full control over configuration files.

## Usage

1. **Write HTML**: Use the HTML editor to create your page structure
2. **Style with CSS**: Add styles in the CSS editor to design your page
3. **Add Interactivity**: Write JavaScript code to make your page interactive
4. **View Results**: The output pane automatically updates to show your rendered page

All your code is automatically saved to local storage, so you can close the browser and return to your work later.

## Project Structure

```
codewriter/
├── public/           # Static files
├── src/
│   ├── components/   # React components
│   │   ├── App.js    # Main application component
│   │   └── Editor.js # Code editor component
│   ├── hooks/        # Custom React hooks
│   │   └── useLocalStorage.js  # Hook for localStorage persistence
│   ├── index.css     # Global styles
│   └── index.js      # Application entry point
└── package.json      # Project dependencies and scripts
```

## License

This project is open source and available for educational purposes.
