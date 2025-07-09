# 📊 Recherche Opérationnelle - Graph Algorithms Application

A comprehensive desktop application for visualizing and implementing various graph algorithms, designed for educational purposes in Operations Research.

## 🎯 Features

### Graph Algorithms Implemented:
- **Graph Coloring**: Welsh-Powell algorithm for graph coloring problem
- **Shortest Path**: 
  - Dijkstra's algorithm for weighted graphs
  - Bellman-Ford algorithm for graphs with negative weights
- **Minimum Spanning Tree**: Kruskal's algorithm
- **Project Scheduling**: Potentiel-Metra (PERT) method
- **Transportation Problems**: 
  - Least Cost method (Moindre Coût)
  - North-West Corner method (Nord-Ouest)
  - Stepping Stone method for optimization
- **Network Flow**: Ford-Fulkerson algorithm for maximum flow problems

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Required packages (install via pip):
  ```bash
  pip install tkinter pillow numpy networkx matplotlib
  ```

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/graph-algorithms-app.git
   cd graph-algorithms-app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
   ```

## 📖 Usage

1. **Launch the application** - Run the main script to open the GUI
2. **Select an algorithm** - Click "Ouvrir le menu des algorithmes" to see available algorithms
3. **Input parameters** - Enter required parameters (number of nodes, edges, etc.)
4. **View results** - See algorithm results in both text format and graphical visualization

### Example Usage:
- **Welsh-Powell**: Enter number of vertices and edges, get optimal graph coloring
- **Dijkstra**: Find shortest paths from a source vertex to all other vertices
- **Kruskal**: Find minimum spanning tree with total weight calculation
- **PERT**: Project scheduling with critical path analysis

## 🖼️ Screenshots

The application features:
- Clean, modern GUI with light theme
- Interactive algorithm selection menu
- Real-time graph visualization using matplotlib
- Detailed result displays with step-by-step explanations

## 📁 Project Structure

```
graph-algorithms-app/
├── main.py                 # Main application file
├── requirements.txt        # Python dependencies
├── assets/
│   └── logo.png           # Application logo
└── README.md              # This file
```

## 🔧 Technical Details

### Built with:
- **tkinter** - GUI framework
- **NetworkX** - Graph creation and manipulation
- **matplotlib** - Graph visualization
- **NumPy** - Mathematical operations
- **PIL (Pillow)** - Image processing

### Features:
- Random graph generation for testing
- Interactive parameter input
- Real-time algorithm visualization
- Detailed result analysis
- Step-by-step algorithm explanation

## 🎓 Educational Purpose

This application was developed as part of an Operations Research course to demonstrate:
- Graph theory concepts
- Algorithm implementation
- Visual learning of complex algorithms
- Practical application of theoretical concepts

## 👥 Contributors

- **Hajar Afdel Semlali** - Developer
- **Mme. EL MKHALLET Mouna** - Supervisor

## 📝 Algorithm Details

### 1. Welsh-Powell Algorithm
- **Purpose**: Graph coloring problem
- **Input**: Number of vertices and edges
- **Output**: Minimum number of colors needed and vertex coloring

### 2. Dijkstra's Algorithm
- **Purpose**: Shortest path in weighted graphs
- **Input**: Graph with positive weights
- **Output**: Shortest distances and paths from source

### 3. Kruskal's Algorithm
- **Purpose**: Minimum spanning tree
- **Input**: Weighted connected graph
- **Output**: MST with minimum total weight

### 4. Bellman-Ford Algorithm
- **Purpose**: Shortest path (handles negative weights)
- **Input**: Weighted directed graph
- **Output**: Shortest paths or negative cycle detection

### 5. Potentiel-Metra (PERT)
- **Purpose**: Project scheduling
- **Input**: Tasks with dependencies and durations
- **Output**: Critical path and project timeline

### 6. Transportation Algorithms
- **Purpose**: Optimize transportation costs
- **Input**: Supply, demand, and cost matrices
- **Output**: Optimal allocation and minimum cost

### 7. Ford-Fulkerson Algorithm
- **Purpose**: Maximum flow in networks
- **Input**: Flow network with capacities
- **Output**: Maximum flow value and flow distribution

## 🚀 Future Enhancements

- [ ] Add more graph algorithms (A*, Floyd-Warshall, etc.)
- [ ] Export results to PDF/Excel
- [ ] Save/load graph configurations
- [ ] Interactive graph editing
- [ ] Performance benchmarking
- [ ] Multi-language support

## 🐛 Bug Reports

If you find any bugs or have suggestions for improvements, please open an issue on GitHub.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- NetworkX documentation and community
- Matplotlib for excellent visualization capabilities
- Operations Research textbooks for algorithm references

---

**Note**: This application is designed for educational purposes and may not be optimized for large-scale production use.
