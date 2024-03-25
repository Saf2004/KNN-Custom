## Project Title: K-Nearest Neighbors Classifier Comparison

### Overview:
This project explores the implementation and comparison of K-Nearest Neighbors (KNN) classification algorithm on the Iris dataset. It compares the performance of standard KNN classifier with custom implementations using different scaling techniques.

### Requirements:
- Python 3.x

### Installation and Setup:
1. Clone the repository or download the project files.
2. Navigate to the project directory.
3. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv_name
    source venv_name/bin/activate  # For Linux/Mac
    venv_name\Scripts\activate.bat  # For Windows
    ```
4. Install the required libraries using the provided `requirements.txt` file:
    ```bash
    pip install -r requirements.txt
    ```

### Usage:
1. After activating the virtual environment, run the `main.py` file:
    ```bash
    python main.py
    ```

### Code Structure:
- `main.py`: Main script containing the implementation of KNN classifier and its comparison.
- `README.md`: This file providing an overview of the project.
- `requirements.txt`: File containing the list of required libraries.

### Code Explanation:
The code performs the following steps:
1. Imports necessary libraries and modules.
2. Loads the Iris dataset.
3. Performs Principal Component Analysis (PCA) for dimensionality reduction.
4. Splits the dataset into training and testing sets.
5. Implements custom functions for KNN algorithm: distance calculation, finding nearest neighbors, and voting.
6. Compares the performance of KNN with different values of K (3, 5, 7) using standard and custom implementations.
7. Prints the accuracy scores for each variation.

### Results:
The script prints out the accuracy scores of KNN classifiers with different configurations including:
- Standard KNN with different values of K.
- Custom KNN with different scaling techniques (StandardScaler and Normalizer) and different values of K.

### License:
This project is licensed under the MIT License - see the `LICENSE` file for details.

