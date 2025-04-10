
# PSO-Optimized Neural Network

This repository contains the implementation of a neural network optimized using Particle Swarm Optimization (PSO). The model is designed to optimize the hyperparameters of a neural network and compare the results with a traditionally optimized neural network.

## Requirements

Ensure you have the following installed:

- Python (version 3.7 or higher)
- Required Python Libraries:
    - numpy
    - pandas
    - tensorflow (or keras)
    - scikit-learn
    - pyswarm (for Particle Swarm Optimization)
    - matplotlib (for plotting)

You can install the required libraries using:

```bash
pip install numpy pandas tensorflow scikit-learn pyswarm matplotlib
```

## Run Instructions

| **Step**                            | **Description**                                                                                                                                              |
|-------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **1. Install Python and Libraries** | Ensure Python (version 3.7 or higher) is installed. Install required libraries using: <br> `pip install numpy pandas tensorflow scikit-learn pyswarm matplotlib` |
| **2. Clone the GitHub Repository**  | Clone the repository to your local machine: <br> `git clone https://github.com/your-username/your-repository.git`                                              |
| **3. Navigate to Project Directory**| Navigate to the project directory: <br> `cd your-repository`                                                                                                 |
| **4. Prepare Dataset**              | Download or use the dataset for training the neural network. Ensure the dataset is in the correct directory or update the file path in the script.            |
| **5. Run Python Script/Notebook**   | If using a Python script: <br> `python ps_nn_optimization.py` <br> If using Jupyter Notebook: <br> `jupyter notebook` and run all cells in `PSO_Neural_Network_Optimization.ipynb` |
| **6. Observe Results**              | The model will print the performance metrics (accuracy, precision, recall, F1-score) and display visualizations such as confusion matrix and accuracy/loss curves. |
| **7. Evaluate the Results**         | Analyze the printed results and visualizations to compare the performance of the PSO-optimized neural network against the traditional model.                    |

