# Parameterizing Network Graph Heterogeneity using a Modified Weibull Distribution

This repository contains the implementation of essential formulas and figures from the paper "Parameterizing network graph heterogeneity using a modified Weibull distribution." The code is organized into two Jupyter Notebook files, each focusing on different aspects of the research. Additionally, the repository includes the original paper for reference.

## Repository Structure

### Files

- **Parameterizing network graph.ipynb**
  - Implements most of the key formulas and generates the significant figures presented in the paper.
  - Includes custom implementations such as calculating the Gini index, generating and refining scale-free graphs, and comparing degree distributions.

- **Graph Configuration.ipynb**
  - Implements an alternative method for graph configuration that achieves similar results to the paper's proposed method.
  - While not identical to the approach described in the paper, the model is robust and aligns well with the intended outcomes.

- **Paper**
  - The original paper is included for reference, providing the theoretical background and context for the implemented methods.

## Key Features

### Gini Index Calculation
A method to compute the Gini index of a graph's degree distribution, offering insights into network heterogeneity.

### Scale-Free Graph Generation and Refinement
- **Barabási-Albert Graphs:** Utilized as the base structure for scale-free networks.
- **Degree Distribution Refinement:** Ensures that the generated graph matches a target degree distribution using statistical methods like the Kolmogorov-Smirnov (KS) test.

### Degree Distribution Comparison
Visualizes and compares the degree distributions of the generated graph and the target sequence using log-log scale histograms.

### Network Visualization
Visualizes the refined scale-free graph using a spring layout to represent the network structure.

## Sample Outputs

- **Graph Visualization:**
  - Displays the structure of the refined scale-free network.
- **Degree Distribution Plots:**
  - Compares the original degree sequence with the graph's degree distribution.
- **Gini Index and KS Test Results:**
  - Quantifies network heterogeneity and evaluates the similarity between degree distributions.

## Prerequisites

- Python 3.8+
- Required Libraries:
  - `numpy`
  - `networkx`
  - `matplotlib`
  - `scipy`

If you're using a virtual environment (e.g., `venv`) with Jupyter Notebook, ensure the necessary libraries are installed within the environment. Activate your `venv` and install the required libraries using:
```bash
pip install numpy networkx matplotlib scipy
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/hghaemi/Parameterizing-Network-Graph-Paper.git
   cd Parameterizing-Network-Graph-Paper
   ```

2. Open the desired Jupyter Notebook:
   ```bash
   jupyter notebook Parameterizing network graph.ipynb
   ```

3. Execute the cells to reproduce the figures and results from the paper.

## Notes

- The method implemented in `Graph Configuration.ipynb` differs slightly from the paper's proposed configuration model but serves as a robust alternative.
- Ensure that all dependencies are installed before running the notebooks.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

If you have any questions, feel free to email me at [h.ghaemi.2003@gmail.com] or open a discussion thread in the repository. I'm happy to help clarify any aspects of the code or methodology.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

