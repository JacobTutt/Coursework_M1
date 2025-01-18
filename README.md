# MNIST Machine Learning Classification

This repository implements and presents the accuracy of various machine learning approaches. Specifically in the classification of a dataset generated from MNIST images, where two digits are vertically stacked (56x28) and labeled by the sum of the constituent digits. It first evaluates the performance of a fully connected neural network before comparing it to the alternative methods, each with relative strengths and weaknesses in handling the highly-dimensional dataset.

---

## Installation Instructions

To run the notebooks, please follow these steps:

### 1. Clone the Repository

Clone the repository from the remote repository to your local machine.

```bash
git clone https://github.com/JacobTutt/ML_mnist.git
```

### 2. Create a Fresh Virtual Environment
Use a clean virtual environment to avoid dependency conflicts.
```bash
python -m venv env
source env/bin/activate   # For macOS/Linux
env\Scripts\activate      # For Windows
```

### 3. Install the dependencies
Navigate to the repository’s root directory and install the package dependencies:
```bash
pip install -r requirements.txt
```

### 4. Set Up a Jupyter Notebook Kernel
To ensure the virtual environment is recognised within Jupyter notebooks, set up a kernel:
```bash
python -m ipykernel install --user --name=env --display-name "MNIST ML"
```

### 5. Run the Notebooks
Open the notebooks and select the created kernel **(MNIST ML)** to run the code.

---

### Saved results
Results for the built models are saved in the `Results` directory for reproducability of results

### Report
Please find a report analysing and justifying each approaches preformance in the `report` directory

