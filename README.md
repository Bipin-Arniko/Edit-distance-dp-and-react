# Spell Checker App

A simple React app that suggests similar words using the edit distance algorithm.

## Features

- Real-time word suggestions
- Edit distance ranking (closest matches first)
- Clean Material-UI interface
- Fast search with dynamic programming

## How it works

Enter a word and get suggestions based on similarity. The app calculates how many character changes are needed to transform your input into dictionary words.

**Example**: Type "arpit" → Get "armpit" (1 change), "armit" (1 change)

## Setup

```bash
# Clone the repo
git clone https://github.com/yourusername/spell-checker-app.git
cd spell-checker-app

# Install dependencies
npm install

# Start the app
npm start
```

Open `http://localhost:3000` to use the app.

## Tech Stack

- React
- Material-UI
- JavaScript
- Levenshtein Distance Algorithm

## File Structure

```
src/
├── App.js          # Main component with search logic
├── text.txt        # Dictionary file (one word per line)
└── components/     # UI components
```

## Customization

- Replace `src/text.txt` with your own word list
- Change result count in `App.js` (currently shows top 15)

## License

MIT
