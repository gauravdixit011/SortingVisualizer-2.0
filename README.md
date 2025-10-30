# Sorting Algorithm Visualizer - Hacker Terminal Theme

![Hacker Terminal](https://img.shields.io/badge/Theme-Hacker%20Terminal-green)
![License](https://img.shields.io/badge/License-MIT-blue)
![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen)

A visually stunning, terminal-inspired sorting algorithm visualizer with a dark hacker aesthetic that helps understand how different sorting algorithms work through animated visualizations.

## 🚀 Live Demo

[View Live Project](https://gauravdixit011.github.io/SortingVisualizer-2.0) <!-- Replace with your actual deployment link -->

## 📋 Table of Contents

- [Features](#features)
- [Algorithms Implemented](#algorithms-implemented)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technical Details](#technical-details)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## ✨ Features

### 🎨 Visual Design
- **Hacker Terminal Theme**: Dark interface with green matrix-style visuals
- **Matrix Background**: Animated falling code rain effect
- **Glitch Effects**: Authentic terminal glitch animations
- **Terminal Interface**: Realistic command-line interface with blinking cursor
- **Color-coded Visualization**: Different colors for comparing, swapping, sorted elements

### 🔧 Interactive Controls
- **Algorithm Selection**: Choose from 5 different sorting algorithms
- **Adjustable Array Size**: Slider from 10 to 100 elements
- **Speed Control**: Variable animation speed (1-10)
- **Command Line**: Type commands directly for advanced control
- **Real-time Status**: Live updates during sorting process

### 📊 Educational Features
- **Algorithm Information**: Detailed descriptions of each algorithm
- **Time Complexity**: Best, average, and worst case analysis
- **Step-by-step Visualization**: See exactly how each algorithm works
- **Color Legend**: Understand what each visualization color represents

## 🧮 Algorithms Implemented

| Algorithm | Best Case | Average Case | Worst Case | Features |
|-----------|-----------|--------------|------------|----------|
| **Bubble Sort** | O(n) | O(n²) | O(n²) | Simple, educational, shows adjacent comparisons |
| **Selection Sort** | O(n²) | O(n²) | O(n²) | Minimum element selection, builds sorted section |
| **Insertion Sort** | O(n) | O(n²) | O(n²) | Efficient for small datasets, builds sorted array |
| **Merge Sort** | O(n log n) | O(n log n) | O(n log n) | Divide and conquer, stable sorting |
| **Quick Sort** | O(n log n) | O(n log n) | O(n²) | Pivot-based, efficient for large datasets |

## 🛠️ Installation

### Prerequisites
- Modern web browser with JavaScript enabled
- No additional dependencies required

### Local Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/gauravdixit011/SortingVisualizer-2.0.git
   cd SortingVisualizer-2.0
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser
   - Or use a local server for better performance:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the application**
   - Open your browser and navigate to `http://localhost:8000`

## 🎮 Usage

### Basic Controls
1. **Select Algorithm**: Choose from dropdown menu
2. **Set Array Size**: Use slider (10-100 elements)
3. **Adjust Speed**: Control animation speed (1-10)
4. **Generate New Array**: Create random array
5. **Start Sorting**: Execute selected algorithm

### Terminal Commands
Type commands in the terminal input for advanced control:
```
help        - Show available commands
clear       - Clear terminal status
run         - Start sorting algorithm
stop        - Stop current process (demo)
reset       - Generate new array
list        - Show available algorithms
size [n]    - Set array size (10-100)
speed [1-10] - Set animation speed
[algorithm] - Set algorithm (bubble, selection, insertion, merge, quick)
```

### Visualization Colors
- **Green**: Normal elements
- **Yellow**: Elements being compared
- **Red**: Elements being swapped
- **Bright Green**: Sorted elements
- **Purple**: Pivot element (Quick Sort)

## 📁 Project Structure

```
sorting-visualizer/
│
├── index.html              # Main application file
├── README.md               # Project documentation
│
├── 📁 assets/              # (Optional) Additional assets
│   ├── images/             # Screenshots and logos
│   └── sounds/             # Sound effects (future)
│
└── 📁 docs/                # Documentation files
    ├── algorithm-explanations.md
    └── implementation-details.md
```

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Structure and semantic markup
- **CSS3**: Advanced animations, gradients, and responsive design
- **Vanilla JavaScript**: Algorithm implementations and DOM manipulation

### Key JavaScript Functions
- `init()`: Application initialization
- `generateNewArray()`: Creates random array for visualization
- Sorting algorithms with animation recording:
  - `bubbleSort()`, `selectionSort()`, `insertionSort()`
  - `mergeSort()`, `quickSort()`
- `playAnimations()`: Controls visualization playback
- `processCommand()`: Handles terminal commands

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 🤝 Contributing

We welcome contributions to improve this project! Here's how you can help:

### Reporting Issues
1. Check existing issues to avoid duplicates
2. Use the issue template with clear description
3. Include browser and OS information

### Feature Requests
1. Describe the proposed feature
2. Explain the benefits and use cases
3. Consider implementation complexity

### Pull Requests
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines
- Follow existing code style
- Add comments for complex logic
- Test across different browsers
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Gaurav Dixit**

- GitHub: [@gauravdixit](https://github.com/gauravdixit)
- LinkedIn: [Gaurav Dixit](https://linkedin.com/in/gauravdixit)
- Portfolio: [gauravdixit.dev](https://gauravdixit.dev) <!-- Replace with your actual portfolio -->
- Email: gaurav.dixit@example.com <!-- Replace with your actual email -->

### 🙏 Acknowledgments

- Inspired by various computer science educational resources
- Matrix effect inspired by classic terminal animations
- Algorithm implementations based on standard computer science literature

### 📞 Support

If you have any questions or need help with the project, feel free to:
1. Open an issue on GitHub
2. Contact the author directly
3. Check the documentation in the `/docs` folder

---

<div align="center">

**⭐ Don't forget to star this repository if you find it helpful!**

*"Understanding algorithms through visualization"*

</div>
