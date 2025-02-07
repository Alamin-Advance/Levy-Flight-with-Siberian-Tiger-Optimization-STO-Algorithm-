
# Levy Flight with Siberian Tiger Optimization (STO) Algorithm

![Python](https://img.shields.io/badge/Python-3.7%2B-blue) 
![NumPy](https://img.shields.io/badge/NumPy-1.20%2B-green) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.0%2B-orange)

This project implements a hybrid optimization algorithm combining **Levy Flight** with the **Siberian Tiger Optimization (STO)** algorithm. The STO algorithm is inspired by the hunting behavior of Siberian tigers, while Levy Flight introduces random walk patterns to enhance exploration and avoid local optima. This hybrid approach is designed to solve complex optimization problems efficiently.his version incorporates multiple Levy Flight techniques to improve its performance, particularly in escaping local optima and exploring solution spaces effectively. The algorithm is especially suitable for high-dimensional and nonlinear optimization tasks.

---

## Features

- **Siberian Tiger Optimization (STO)**: Mimics the hunting strategies of Siberian tigers for global optimization.
- **Levy Flight Integration**: Enhances exploration capabilities using Levy Flight's random walk patterns.
- **Flexible Implementation**: Can be applied to various optimization problems (e.g., function optimization, engineering design, machine learning hyperparameter tuning).
- **Visualization**: Includes tools to visualize the optimization process and convergence.

---

## Requirements

To run this project, you need the following dependencies:

- Python 3.7 or higher
- NumPy
- Matplotlib (for visualization)

You can install the required libraries using:

```bash
pip install numpy matplotlib
```

---

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/levy-flight-sto.git
   cd levy-flight-sto
   ```

2. **Run the Algorithm**:
   - Execute the main script to run the Levy Flight with STO algorithm:
     ```bash
     python levy_flight_sto.py
     ```

3. **Customize the Problem**:
   - Modify the `objective_function` in the script to solve your specific optimization problem.
   - Adjust algorithm parameters (e.g., population size, maximum iterations, Levy Flight parameters) for better performance.

4. **Visualize Results**:
   - The script includes visualization tools to plot the convergence curve and search space exploration.

---

## How It Works

1. **Siberian Tiger Optimization (STO)**:
   - The algorithm simulates the hunting behavior of Siberian tigers, including strategies like stalking, chasing, and capturing prey.
   - Tigers (solutions) move toward the best solution (prey) while avoiding local optima.

2. **Levy Flight**:
   - Levy Flight introduces random walk patterns with heavy-tailed step lengths, allowing the algorithm to explore the search space more effectively.
   - This helps in escaping local optima and improving global search capabilities.

3. **Hybrid Approach**:
   - The combination of STO and Levy Flight balances exploration and exploitation, leading to faster convergence and better solutions.

---

## Project Structure

```
levy-flight-sto/
├── levy_flight_sto.py       # Main script implementing the hybrid algorithm
├── README.md                # Project documentation
├── requirements.txt         # List of dependencies
└── results/                 # Folder to store output plots and results
```

---

## Results

- **Convergence Plot**:
  ![Convergence Plot](results/convergence_plot.png)

- **Search Space Exploration**:
  ![Search Space](results/search_space.png)

---

## Contributing

Contributions are welcome! If you'd like to improve this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- The Siberian Tiger Optimization (STO) algorithm is inspired by the hunting behavior of Siberian tigers.
- Levy Flight is a well-known random walk strategy used in optimization algorithms.
- Special thanks to the open-source community for providing tools and libraries that made this project possible.

---

## Contact

For any questions or further information, please reach out or open an issue.
