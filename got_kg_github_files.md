# Game of Thrones Knowledge Graph - GitHub Project Files

## Project Structure
```
got-knowledge-graph/
├── README.md
├── LICENSE
├── package.json
├── .gitignore
├── public/
│   └── index.html
├── src/
│   ├── App.jsx
│   ├── index.js
│   ├── index.css
│   └── components/
│       └── KnowledgeGraph.jsx
└── screenshots/
    └── demo.png
```

---

## 📄 README.md

```markdown
# ⚔️ Game of Thrones Knowledge Graph

An interactive, visual knowledge graph exploring character relationships and royal houses from Game of Thrones. Built with React and HTML Canvas, featuring a bold Neubrutalism design aesthetic.

![Game of Thrones Knowledge Graph Demo](./screenshots/demo.png)

## ✨ Features

### 🎯 Interactive Knowledge Graph
- **24+ Characters** from major houses (Stark, Lannister, Targaryen, Baratheon, and more)
- **9 Relationship Types**: parent, sibling, married, romance, killed, mentor, advisor, rivalry, enemy
- **Visual Connections**: Color-coded relationship lines with directional arrows

### 🔗 Multi-Select & Filtering
- **Multi-Select Mode**: Select multiple characters simultaneously
- **Quick House Selection**: Select entire families with one click
- **Smart Highlighting**: Focus mode dims unconnected characters
- **House Filtering**: View specific houses in isolation

### 🎨 Modern Design
- **Neubrutalism Aesthetic**: Bold borders, flat colors, high contrast
- **Responsive Layout**: Works on mobile, tablet, and desktop
- **High-DPI Support**: Crisp rendering on Retina displays
- **Smooth Interactions**: Pan, zoom, and explore the graph

### 📊 Knowledge Graph Principles
Built following best practices for knowledge graph development:
- Clear domain modeling with entities and relationships
- Semantic data structure (subject-predicate-object)
- Iterative validation and testing
- Intuitive visualization

## 🚀 Getting Started

### Prerequisites
- Node.js 16+ and npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/got-knowledge-graph.git
cd got-knowledge-graph
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Build for Production

```bash
npm run build
```

## 🎮 How to Use

1. **Select Characters**: Click on any character node to view their details
2. **Multi-Select**: Toggle "Multi-Select" mode to select multiple characters
3. **View Connections**: Enable "Focus" to highlight relationships between selected characters
4. **Quick Select**: Use house buttons to select entire families at once
5. **Navigate**: 
   - Drag to pan the canvas
   - Use +/− buttons to zoom
   - Click "Reset" to return to default view
6. **Filter**: Use the dropdown to view specific houses
7. **Search**: Type character names to find them quickly

## 🏗️ Technical Architecture

### Tech Stack
- **React 18**: Component-based UI
- **HTML5 Canvas**: High-performance rendering
- **Tailwind CSS**: Utility-first styling
- **Lucide React**: Icon library

### Key Components
- `KnowledgeGraph.jsx`: Main graph component with canvas rendering
- High-DPI canvas scaling for crisp visuals
- Responsive design with mobile-first approach
- State management for selections and interactions

### Data Structure
```javascript
// Character nodes
{ id, name, house, title, status, x, y }

// Relationships
{ from, to, type, label }

// Houses
{ name, color, sigil, seat }
```

## 📚 Knowledge Graph Methodology

This project follows established knowledge graph principles:

1. **Define Clear Goals**: Visualize character relationships and house connections
2. **Domain Modeling**: Entities (characters, houses) and relationships (family, political, conflict)
3. **Semantic Structure**: RDF-style triplets (character → relationship → character)
4. **Iterative Development**: Started with core families, expanded to complex relationships
5. **Validation**: Testing with real-world queries and relationship verification

## 🎨 Design Philosophy

### Neubrutalism Aesthetic
- **Bold Typography**: Uppercase, monospace font
- **Thick Borders**: 4px black borders on all elements
- **Flat Colors**: High contrast, vibrant house colors
- **Box Shadows**: Brutalist depth effects
- **No Rounded Corners**: Sharp, geometric design

### Color System
- **Stark**: Blue (#60A5FA) - Winter, North, Honor
- **Lannister**: Gold (#FBBF24) - Wealth, Power
- **Targaryen**: Red (#EF4444) - Fire, Dragons
- **Baratheon**: Yellow (#FCD34D) - Storm, Strength
- **Tyrell**: Green (#34D399) - Growth, Highgarden
- **Greyjoy**: Indigo (#6366F1) - Sea, Iron Islands
- **Martell**: Orange (#F97316) - Sun, Dorne

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Ideas for Contributions
- Add more characters and relationships
- Implement graph layout algorithms (force-directed, hierarchical)
- Add filtering by relationship type
- Export graph data to JSON
- Add character detail modal
- Implement search with autocomplete
- Add timeline feature for events

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Game of Thrones universe created by George R.R. Martin
- Inspired by knowledge graph research and best practices
- Built with modern web technologies

## 📧 Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter)

Project Link: [https://github.com/yourusername/got-knowledge-graph](https://github.com/yourusername/got-knowledge-graph)

---

⚔️ **Winter is Coming** 🐺
```

---

## 📄 package.json

```json
{
  "name": "got-knowledge-graph",
  "version": "1.0.0",
  "description": "Interactive knowledge graph of Game of Thrones characters and relationships",
  "private": true,
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1",
    "lucide-react": "^0.263.1"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
  "eslintConfig": {
    "extends": [
      "react-app"
    ]
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  },
  "keywords": [
    "game-of-thrones",
    "knowledge-graph",
    "data-visualization",
    "react",
    "canvas",
    "neubrutalism"
  ],
  "author": "Your Name",
  "license": "MIT"
}
```

---

## 📄 .gitignore

```
# Dependencies
node_modules/
/.pnp
.pnp.js

# Testing
/coverage

# Production
/build

# Misc
.DS_Store
.env.local
.env.development.local
.env.test.local
.env.production.local

npm-debug.log*
yarn-debug.log*
yarn-error.log*

# IDE
.vscode/
.idea/
*.swp
*.swo
*~
```

---

## 📄 LICENSE

```
MIT License

Copyright (c) 2024 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 📄 public/index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#000000" />
    <meta
      name="description"
      content="Interactive knowledge graph exploring Game of Thrones character relationships and royal houses"
    />
    <title>⚔️ Game of Thrones Knowledge Graph</title>
  </head>
  <body>
    <noscript>You need to enable JavaScript to run this app.</noscript>
    <div id="root"></div>
  </body>
</html>
```

---

## 📄 src/index.js

```javascript
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);
```

---

## 📄 src/index.css

```css
@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap');

@tailwind base;
@tailwind components;
@tailwind utilities;

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Space Mono', monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  overflow: hidden;
}

#root {
  width: 100vw;
  height: 100vh;
}
```

---

## 📄 src/App.jsx

```jsx
import React from 'react';
import KnowledgeGraph from './components/KnowledgeGraph';

function App() {
  return <KnowledgeGraph />;
}

export default App;
```

---

## 📄 src/components/KnowledgeGraph.jsx

```jsx
// Paste the complete KnowledgeGraph component code here
// (The full component from the artifact above)
```

---

## 📄 tailwind.config.js

```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {
      fontFamily: {
        mono: ['Space Mono', 'monospace'],
      },
    },
  },
  plugins: [],
}
```

---

## 📄 postcss.config.js

```javascript
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
}
```

---

## 🚀 Deployment Instructions

### GitHub Pages
1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add to package.json:
```json
"homepage": "https://yourusername.github.io/got-knowledge-graph",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```
3. Deploy: `npm run deploy`

### Vercel
1. Push to GitHub
2. Import project on Vercel
3. Deploy automatically

### Netlify
1. Drag and drop `build` folder
2. Or connect GitHub repository

---

## 📸 Screenshots Directory

Create a `screenshots/` folder and add a demo image showing:
- The full interface
- Multi-select in action
- Highlighted connections
- Different houses selected

---

## Setup Instructions

1. Create a new directory: `mkdir got-knowledge-graph && cd got-knowledge-graph`
2. Copy all files to their respective locations
3. Run `npm install`
4. Add Tailwind: `npm install -D tailwindcss postcss autoprefixer`
5. Initialize Tailwind: `npx tailwindcss init -p`
6. Start development: `npm start`

Your project is now ready to be pushed to GitHub! 🎉
```
