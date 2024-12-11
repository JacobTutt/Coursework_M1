# M1 Coursework Repository
This repository contains notebooks for each part of the coursework.

---

## Installation Instructions

To run the notebooks, please follow these steps:

### 1. Clone the Repository

Clone the repository from the remote repository (GitLab) to your local machine. Replace `<URL>` with the actual repository URL:

```bash
git clone <URL>
```

### 2. Create a Fresh Virtual Environment
Use a clean virtual environment to avoid dependency conflicts.
```bash
python -m venv env
source env/bin/activate   # For macOS/Linux
env\Scripts\activate      # For Windows
```

### 3. Install the Package and Dependencies
Navigate to the repository’s root directory and install the package along with its dependencies:
```bash
pip install .
```

### 4. Set Up a Jupyter Notebook Kernel
To ensure the virtual environment is recognised within Jupyter notebooks, set up a kernel:
```bash
python -m ipykernel install --user --name=env --display-name "Python (M1 Coursework)"
```

### 5. Run the Notebooks
Open the notebooks and select the created kernel **(Python(M1 Coursework))** to run the code.

### 6. Saved results
Results for the built models are saved in the `Results` directory for reproducability of results
