# algo-efficiency-mini-project-AnshikaGoyal

## Project Overview

This project explores classical algorithms including Fibonacci sequence calculations (naive recursive and dynamic programming), several sorting techniques (Merge Sort, Quick Sort, Insertion Sort, Bubble Sort, Selection Sort), and Binary Search. The primary focus is on analyzing and visualizing their time and space complexities through practical profiling and execution time measurement.

## Technologies Used

- Python 3
- Libraries:
  - `numpy`
  - `matplotlib`
  - `memory_profiler`
  - `time`

## Project Structure

- `algo_analysis_notebook.ipynb`: The main interactive notebook containing all implementations, tests, profiling code, and visualizations.
- `README.md`: This documentation file.
- `requirements.txt`: Lists all dependencies necessary to run the project.
- `.gitignore`: Specifies files and folders to be ignored by Git.
- `images/`: Folder containing any images used for documentation or notebook illustrations.

## Getting Started

### Prerequisites

Install Python 3 and then install dependencies using:


### Running the Notebook

1. Clone this repository:


2. Open and run the notebook:

- Locally via Jupyter:


- Or upload and execute in [Google Colab](https://colab.research.google.com).

3. Execute the notebook cells sequentially to reproduce all results and visualizations.

   ## Trade-Offs and Sustainability

### Trade-Offs

In algorithm design and implementation, there are important trade-offs between time complexity, space complexity, and simplicity:

- **Time vs Space:**  
  Many algorithms achieve faster performance by using additional memory (e.g., dynamic programming for Fibonacci uses memoization to reduce time at the cost of extra space).

- **Efficiency vs Simplicity:**  
  Simple algorithms like Bubble Sort are easy to understand but inefficient for large datasets. In contrast, algorithms like Quick Sort are faster but more complex to implement and analyze.

- **Worst-case vs Average-case:**  
  Some algorithms (e.g., Quick Sort) perform exceptionally well on average but have poor worst-case scenarios, requiring careful implementation to mitigate risks.

- **Recursion Depth Risks:**  
  Recursive algorithms can suffer from stack overflow for large inputs, which must be managed by switching to iterative approaches or using memoization.

### Sustainability

Sustainable algorithm design considers:

- **Scalability:**  
  Algorithms should maintain performance as data sizes grow, making efficient algorithms like Merge Sort and Binary Search preferred for large datasets.

- **Maintainability:**  
  Clear, well-commented code ensures algorithms can be updated and improved over time.

- **Adaptability:**  
  Algorithms that balance efficiency with readability and flexibility are easier to adapt to evolving problem requirements.

- **Resource Awareness:**  
  Efficient use of memory and processing preserves system resources, supporting sustainable computing especially in large-scale or embedded systems.

By evaluating these trade-offs and focusing on sustainable practices, algorithm implementations become robust, efficient, and suitable for practical, long-term use.


## Key Learnings

- Recursive Fibonacci is highly inefficient for large inputs, whereas memoized dynamic programming significantly improves performance.
- Sorting algorithms vary from simple \(O(n^2)\) sorts to efficient \(O(n \log n)\) methods; real-world performance differences are demonstrated.
- Binary search efficiently performs \(O(\log n)\) search on sorted data.
- Profiling with execution time and memory usage solidifies understanding of algorithmic complexity.


---

Thank you for exploring algorithm complexities with this project!
