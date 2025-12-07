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
