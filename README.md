# 🌷 Grow me a Garden — Interactive DSA Learning Game

An interactive, browser-based Data Structures and Algorithms (DSA) educational simulator built with HTML5, Tailwind CSS, Pyodide (WebAssembly Python), and Lucide Icons.

The application combines a visual garden management simulation with an embedded **Student Code Editor**. Players execute real Python implementations of core DSA concepts to unlock tools, game mechanics, and strategic triggers in real time.

---

## 📸 Key Features & Gameplay Mechanics

- **Client-Side WebAssembly Python (Pyodide):** Runs real Python code directly inside the browser with bidirectional JS–Python bindings.
- **5×9 Matrix Garden Grid:** Plant, water, fertilize, shield, and harvest crops directly mapped onto dynamic spatial data structures.
- **Interactive Student Code Editor:** Pre-loaded with 11 core DSA topic templates featuring block-by-block code comments.
- **Undo Engine & Action History:** LIFO Stack implementation for tracking player actions and rolling back state changes.
- **Climate Hazard Queue:** FIFO Queue processing real-time atmospheric hazards (Typhoons, Tornadoes, Ashfall, Frost).
- **Aklat ng Halaman (Plant Library):** Search plants via Binary Search Trees (BST), Hash Tables, and Hierarchical Taxonomy Trees.
- **Strategic Game Triggers:**
  - **Group Care (Graph Adjacency Matrix):** Multi-tile care actions applied to 3x3 neighbor grids.
  - **Irrigation Pathfinding:** Greedy heuristic route optimization for needy crops.
  - **Golden Plan-ter:** Unbounded Knapsack Dynamic Programming solver for optimal crop profit yield.

---

## 📚 Covered DSA Topics

| Topic | Title | Unlocked Feature / Mechanism |
| :--- | :--- | :--- |
| **Topic 1** | Python OOP + Big O + Stacks | Resource Storage & Action History Stack |
| **Topic 2** | Queues & Deques (FIFO Elements) | *Ulat Panahon* Climate Queue & Seed Bag |
| **Topic 3** | Static/Dynamic Arrays, 2D Lists, & Memory Structures | 2D Garden Matrix Mapping (5×9 Grid) |
| **Topic 4** | Hierarchical Trees & Traversals | Plant Family Taxonomy Tree View |
| **Topic 5** | Binary Search Trees (BST) & Node Mutation | BST Price Search & Deep Undo Engine |
| **Topic 6** | Hash Tables, Collisions, & Rehashing | Quick Plant Lookup (Hash Table) |
| **Topic 7** | Graph Foundations, Adjacency Matrices/Lists, & DFS/BFS | Group Care 3×3 Area Action Trigger |
| **Topic 8** | Sorting Algorithms (Bubble, Insertion, Selection, Quick, & Merge) | Quicksort Flower Vase Payout Sorting |
| **Topic 9** | Searching Algorithms (Linear Search vs. Binary Search) | Action History Linear Search |
| **Topic 10** | Advanced Strategic Paradigms (Dijkstra's & Greedy Patterns) | Greedy Irrigation Route Pathfinding |
| **Topic 11** | Dynamic Programming (DP), Memoization, & Divide-and-Conquer | Golden Plan-ter Knapsack Optimization |

---

## 🚀 Getting Started

### Prerequisites
No backend server, Node.js, or local Python installation is required. The simulator runs entirely in the web browser.

### Installation & Execution
1. Clone or download the repository.
2. Save the code into an `index.html` file.
3. Open `index.html` directly in any modern web browser (Google Chrome, Firefox, Safari, or Edge).

> **Note:** An active internet connection is required on the initial load to fetch CDN dependencies (Tailwind CSS, Pyodide WebAssembly engine, Google Fonts, and Lucide Icons).

---

## 🛠️ Tech Stack & Dependencies

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via CDN), Google Fonts (*Baloo 2*, *Fredoka*, *Sacramento*, *Inter*, *JetBrains Mono*)
- **Icons:** [Lucide Icons](https://lucide.dev/)
- **Python Execution Engine:** [Pyodide v0.26.4](https://pyodide.org/) (WebAssembly Python)

---

## 🎮 How to Play

1. **Launch the Application:** Wait for Pyodide to finish initializing the WebAssembly Python environment.
2. **Open the Student Code Editor:** Switch to the **Student Code Editor** tab.
3. **Run Code to Unlock Features:** Select a topic (starting with **Topic 1**) and click **Run Python Code & Unlock Feature**.
4. **Manage Your Garden:** Return to the **Interactive Garden Game** tab to plant crops, manage water/sunlight/nutrients, defend against random climate hazards, and harvest mature flowers for profit.