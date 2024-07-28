# Support_vector_Iris


```markdown
# SVM Classification on the Iris Dataset

This project demonstrates the use of Support Vector Machines (SVM) for classification on the Iris dataset using different kernels. The code explores the classification results and visualizes the decision boundaries for linear and radial basis function (RBF) kernels.

## Project Description

The Iris dataset is a classic dataset used for machine learning and statistics. It contains 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width. The target variable is the species of the iris flower, which can be one of three classes: Setosa, Versicolour, or Virginica.

In this project, we use the first two features (sepal length and sepal width) to train SVM classifiers with different kernels and visualize the decision boundaries.

### Code Overview

1. **Data Loading and Preparation**
   - The Iris dataset is loaded using `sklearn.datasets`.
   - Only the first two features (sepal length and sepal width) are used for visualization purposes.

2. **SVM Classifier with Linear Kernel**
   - An SVM classifier with a linear kernel is trained on the dataset.
   - A mesh is created to plot the decision boundary.
   - The decision boundary and data points are plotted using `matplotlib`.

3. **SVM Classifier with RBF Kernel (`gamma='auto'`)**
   - An SVM classifier with an RBF kernel and `gamma='auto'` is trained.
   - The decision boundary and data points are plotted using `matplotlib`.

4. **SVM Classifier with RBF Kernel (`gamma=1000`)**
   - An SVM classifier with an RBF kernel and `gamma=1000` is trained.
   - The decision boundary and data points are plotted using `matplotlib`.

### Accuracy

The SVM classifiers achieve an accuracy of **98.16%** on the Iris dataset.

### Visualization

The decision boundaries for the different kernels are visualized in 2D plots, showing how the classifiers separate the different classes of iris flowers based on sepal length and sepal width.

## Getting Started

### Prerequisites

- Python 3.x
- `numpy`
- `matplotlib`
- `scikit-learn`

### Running the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. Install the required libraries:
   ```bash
   pip install numpy matplotlib scikit-learn
   ```

3. Run the code:
   ```bash
   python your-script.py
   ```

### Project Structure

```
.
├── your-script.py      # The main script for SVM classification and visualization
└── README.md           # Project description and instructions
```

## Output 


![image](https://github.com/user-attachments/assets/4523afaf-00e7-4c69-84a6-3867a892e351)




## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Scikit-learn](https://scikit-learn.org/) for providing the Iris dataset and SVM implementation.
- [Matplotlib](https://matplotlib.org/) for data visualization.

```
