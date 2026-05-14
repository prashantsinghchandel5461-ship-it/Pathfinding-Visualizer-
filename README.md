# Pathfinding-Visualizer-
# Path Finding Visualizer

A visual and interactive Path Finding Visualizer built using modern web technologies to demonstrate how popular pathfinding algorithms work in real time.

This project helps users understand graph traversal and shortest-path algorithms through animated grid-based visualization.

---

## Features

* Interactive grid system
* Real-time pathfinding visualization
* Wall and obstacle creation
* Animated algorithm execution
* Start and target node selection
* Shortest path highlighting
* Responsive UI design
* Multiple pathfinding algorithms support
* Adjustable visualization speed

---

## Supported Algorithms

* Dijkstra’s Algorithm
* Breadth-First Search (BFS)
* Depth-First Search (DFS)
* A* Search Algorithm
* Greedy Best-First Search

---

## Tech Stack

### Frontend

* React
* TypeScript / JavaScript
* Vite
* Tailwind CSS
* HTML5
* CSS3

### Visualization & Logic

* Graph traversal algorithms
* Grid-based animation system
* State management for node updates

---

## Project Structure

```bash
patth-finding-main/
│
├── src/
│   ├── algorithms/          # Pathfinding algorithm implementations
│   ├── components/          # Reusable UI components
│   ├── styles/              # CSS/Tailwind styles
│   ├── utils/               # Helper functions
│   ├── App.js / App.tsx     # Main application
│   └── main.js / main.tsx   # Entry point
│
├── public/                  # Static assets
├── package.json             # Project dependencies
├── vite.config.js           # Vite configuration
└── README.md
```

---

## How It Works

1. The user selects a pathfinding algorithm.
2. A grid is generated containing nodes.
3. Users place walls or obstacles.
4. The algorithm explores neighboring nodes.
5. The shortest path is calculated and animated.
6. The final path is highlighted visually.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/pathfinding-visualizer.git
cd patth-finding-main
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

The application will run on:

```text
http://localhost:5173
```

---

## Available Scripts

| Command           | Description              |
| ----------------- | ------------------------ |
| `npm run dev`     | Start development server |
| `npm run build`   | Build for production     |
| `npm run preview` | Preview production build |
| `npm run lint`    | Run ESLint               |

---

## Visualization Flow

```text
Create Grid
     │
     ▼
Select Algorithm
     │
     ▼
Add Walls / Obstacles
     │
     ▼
Run Visualization
     │
     ▼
Explore Nodes
     │
     ▼
Highlight Shortest Path
```

---

## Key Concepts Demonstrated

### Graph Traversal

* Node exploration
* Neighbor checking
* Queue and stack operations
* Weighted vs unweighted traversal

### Pathfinding

* Heuristic-based searching
* Shortest path computation
* Efficient node visiting strategies

### Data Structures

* Queues
* Stacks
* Priority queues
* Graph representations

---

## UI Features

* Click-and-drag wall generation
* Animated node transitions
* Color-coded visited nodes
* Shortest path visualization
* Responsive layout for desktop and mobile

---

## Future Improvements

* Maze generation algorithms
* Weighted nodes support
* Bidirectional search visualization
* Recursive division mazes
* Diagonal movement support
* Dark/light theme toggle
* Touch support for mobile devices
* Performance optimizations for larger grids

---

## Screenshots

Add screenshots here:

```text
/public/screenshots/
```

Suggested screenshots:

* Main grid interface
* Running algorithm animation
* Final shortest path
* Obstacle placement

---

## Deployment

You can deploy this project using:

* Vercel
* Netlify
* GitHub Pages
* Render

### Production Build

```bash
npm run build
```

---

## Educational Purpose

This project is ideal for:

* Learning graph algorithms
* Understanding shortest path problems
* Data structure visualization
* Computer science demonstrations
* Interview preparation

---

## Contributing

Contributions are welcome.

### Steps

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a pull request

---

## License

This project is licensed under the MIT License.

---

## Author

Developed with ❤️ for learning and visualizing pathfinding algorithms.
