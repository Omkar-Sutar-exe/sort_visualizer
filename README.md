# Sorting Visualizer

## Project Overview

This project is a dynamic and interactive web application designed to visually demonstrate the mechanics of various sorting algorithms. It serves as an educational tool, allowing users to observe the step-by-step execution of sorting algorithms on a given set of data. By visualizing the comparisons and swaps, users can gain a deeper understanding of how each algorithm works, its efficiency, and its behavior under different conditions.

## Features

*   **Comprehensive Algorithm Support:**
    *   **Bubble Sort:** A simple comparison-based algorithm.
    *   **Insertion Sort:** Builds the final sorted array one item at a time.
    *   **Selection Sort:** Divides the input list into two parts: a sorted sublist and the remaining unsorted sublist.
    *   **Merge Sort:** A divide-and-conquer algorithm that recursively divides an array into halves until it has individual elements, then merges them back in sorted order.
    *   **Quick Sort:** Another efficient, comparison-based, divide-and-conquer sorting algorithm.
    *   **Heap Sort:** A comparison-based sorting technique based on binary heap data structure.
*   **Interactive Visualization Controls:**
    *   **Play/Pause:** Start, pause, and resume the visualization at any point.
    *   **Speed Control:** Adjust the animation speed to slow down for detailed observation or speed up for quick overviews.
    *   **Array Generation:** Generate new random arrays with customizable sizes to test algorithms on different data sets.
*   **Clear Visual Representation:** Uses color-coding and bar height changes to clearly illustrate element comparisons, swaps, and their positions within the array.

## Technologies Used

*   **HTML5:** Provides the fundamental structure and content of the web pages.
*   **CSS3 (SCSS):** Utilized for advanced styling, responsive design, and maintaining a clean, modular stylesheet architecture. The SCSS is compiled into standard CSS for browser compatibility.
*   **JavaScript (ES6+):** Powers the core logic of the application, including:
    *   Implementation of all sorting algorithms.
    *   Dynamic manipulation of the DOM to render the visualizations.
    *   Event handling for user interactions (e.g., button clicks, slider changes).
    *   Management of visualization state and animation frames.

## Getting Started

To set up and run this project on your local machine, follow these instructions:

### Prerequisites

You only need a modern web browser (e.g., Chrome, Firefox, Edge, Safari) to run this application. No server-side setup or complex build tools are strictly required for basic usage, as it's a client-side web application.

### Installation

1.  **Clone the repository:**
    If this project is hosted on a version control system like GitHub, you would typically clone it using Git:
    ```bash
    git clone <repository_url_here>
    ```
    (Please replace `<repository_url_here>` with the actual URL of your repository if it's hosted online.)

    If you have downloaded a ZIP file, simply extract its contents.

2.  **Navigate to the project directory:**
    Open your terminal or command prompt and change your current directory to the project's root:
    ```bash
    cd "f:\New folder\sort visualizer\Sorting_Visualizer-master\Sorting_Visualizer-master"
    ```

3.  **Open in Browser:**
    Locate the `index.html` file within the `f:\New folder\sort visualizer\Sorting_Visualizer-master\Sorting_Visualizer-master` directory and open it with your preferred web browser. You can usually do this by double-clicking the file or by right-clicking and selecting "Open with...".

## Project Structure

The project is organized into the following directories and files:
├── css/
│   ├── style.css         # Compiled CSS from style.scss
│   └── style.css.map     # Source map for debugging compiled CSS
├── scripts/
│   ├── bubble_sort.js    # Implementation of Bubble Sort algorithm
│   ├── heap_sort.js      # Implementation of Heap Sort algorithm
│   ├── insertion_sort.js # Implementation of Insertion Sort algorithm
│   ├── main.js           # Main application logic, orchestrating visualizations and controls
│   ├── merge_sort.js     # Implementation of Merge Sort algorithm
│   ├── quick_sort.js     # Implementation of Quick Sort algorithm
│   ├── selection_sort.js # Implementation of Selection Sort algorithm
│   └── visualizations.js # Utility functions for rendering and animating the array bars
├── VS_Sorting_Visualizer.code-workspace # Visual Studio Code workspace configuration
├── index.html            # The main HTML file, serving as the entry point of the application
├── package-lock.json     # Records the exact dependency tree (if Node.js packages are used for development/build)
└── style.scss            # Source SCSS file for all styling, compiled into css/style.css

## How to Use the Visualizer

1.  **Load the Application:** Open `index.html` in your web browser.
2.  **Generate Array:** Use the controls (if available) to generate a new array of numbers. You might be able to specify the size or randomize the values.
3.  **Select Algorithm:** Choose a sorting algorithm from the dropdown or button options provided in the UI.
4.  **Start Visualization:** Click the "Sort" or "Visualize" button to begin the animation.
5.  **Control Playback:** Use the speed slider or play/pause buttons to control the visualization flow.
6.  **Observe:** Watch how the elements move and change positions as the algorithm progresses towards a sorted state.

## Contributing

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/YourFeature`).
6.  Open a Pull Request.

## License

This project is open-source and distributed under the [MIT License](LICENSE). See the `LICENSE` file (if present) for more details.

## Author

Omkar Sutar