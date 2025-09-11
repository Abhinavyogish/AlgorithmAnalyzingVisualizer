[README.md](https://github.com/user-attachments/files/22267413/README.md)
# Advanced Algorithm Visualizer

A **React-based** web application for interactively visualizing and learning key algorithms with on‑demand AI explanations powered by the Gemini API.

---

## 🚀 Features

- **Custom & Random Arrays**: Enter your own sequence or generate random numbers
- **Array Size Control**: Resize the dataset with a slider for more or fewer elements
- **Speed Adjustment**: Fine‑tune animation delay via slider or dropdown
- **Algorithm Selector**: Choose from dropdown menus for each module
- **Interactive Visuals**:

  - **Sorting**
  - **Searching**
  - **Graph**
  - **MST**

- **AI Chat Assistant**: Ask questions and receive step‑by‑step algorithm explanations during runtime
- **Controls**: Start, Reset, and Generate New Data or Graph buttons for each module

---

## 🔢 Algorithms Implemented

### Sorting

- Bubble Sort
- Selection Sort
- Insertion Sort
- Merge Sort
- Heap Sort

### Searching

- Linear Search
- Binary Search
- Jump Search
- Exponential Search
- Interpolation Search
- Fibonacci Search

### Graph Traversal & Pathfinding

- Breadth‑First Search (BFS)
- Depth‑First Search (DFS)
- Dijkstra’s Algorithm

### Minimum Spanning Tree

- Prim’s Algorithm
- Kruskal’s Algorithm

---

## 🛠 Prerequisites

- **Node.js** v14+
- **npm** v6+ (or **yarn**)
- **Gemini API Key** (set as `REACT_APP_GEMINI_API_KEY` in `.env`)

---

## ⚙️ Installation & Setup

1. **Clone** your project repo:

   ```bash
   git clone https://github.com/Akshith-desu/algo-visualizer.git
   cd advanced-algo-visualizer
   ```

2. **Add environment variable**:

   ```bash
   echo "REACT_APP_GEMINI_API_KEY=your_api_key" > .env
   ```

3. **Install dependencies**:

   ```bash
   npm install
   # or yarn install
   ```

4. **Run** in development mode:

   ```bash
   npm start
   ```

5. Open `http://localhost:3000` in your browser.

---

## 📖 Usage

1. **Select** a module (Sorting, Searching, Graph, or MST).
2. **Configure** data parameters (size, array, nodes, speed).
3. **Choose** the desired algorithm from the dropdown.
4. Click **Start** to begin visualization.
5. **Interact** with the AI assistant panel for explanations or hints.
6. Use **Reset** or **Generate New** buttons to restart or refresh data.

---

## 🤝 Contributing

Contributions and feedback are welcome:

1. Fork the repo
2. Create branch: `git checkout -b feature/YourFeature`
3. Commit changes: \`git commit -m "Add YourFeature"
4. Push to branch: `git push origin feature/YourFeature`
5. Open a Pull Request
