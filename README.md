# 📐 Geometric Algorithm Visualizer

An interactive **Geometric Algorithm Simulator** that animates and visualizes various convex hull algorithms in real time using **Matplotlib** and **NumPy**. Designed to aid understanding through visual learning, each algorithm executes step-by-step with delays for better clarity.

---

## 🧠 Algorithms Implemented

| Algorithm              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Graham Scan**        | Sorts points by angle and builds convex hull using a stack (O(n log n))     |
| **Andrew’s Monotone**  | A variant of Graham Scan that constructs upper and lower hulls separately   |
| **Jarvis March**       | Also known as the Gift Wrapping algorithm (O(nh))                           |
| **Brute Force**        | Tests every pair of points to see if it forms a convex hull edge (O(n³))    |
| **Elimination Method** | Removes points that cannot be on the convex hull based on geometric rules   |

---

## 🎥 Live Visualization

- ⌛ **Step-by-step execution** with delays
- 📈 Real-time drawing using `matplotlib`
- 🌀 Color-coded transitions between algorithm states
- 🎯 Optional annotation of intermediate points and edges

---

## 🛠️ Built With

- Python 3.x
- [`matplotlib`](https://matplotlib.org/) for visualization
- [`numpy`](https://numpy.org/) for numerical operations
- Optional: `time.sleep()` for pacing the animations

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/YourUsername/geometric-algorithm-visualizer.git
cd geometric-algorithm-visualizer
