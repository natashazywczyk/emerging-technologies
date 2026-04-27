# Emerging Technologies
This repository demonstrates and explains the difference between classical and quantum computation through the perspective of the Deutsch and Deutch-Jozsa algorithms. The main focus is to explore the advantage of using quantum algorithms over classical.

## Project Overview
The `problems.ipynb` notebooks covers five problems:
1. Generating random constant and balanced Boolean functions.
    - `f(x) = 0`
    - `f(x) = 1`
    - `f(x) = x` 
    - `f(x) = ¬x`

2. Classically determine if a function is constant or balanced.

3. Build quantum oracles for each single input Boolean function.

4. Implement Deutch's algorithm using Qiskit.

5. Scale to the Deutsch-Jozsa algorithm for 4-bit inputs.

## Project Structure
`problems.ipynb`
- Covers all problems set out in overview.

`requirements.txt`
- Includes all required dependencies and packages for the project problems.

## Setup Instructions
### Prerequisites
- Python 3.12+
- NumPy
- Qiskit
- JupyterLab/Jupyter Notebook (installation below)


### 1. Clone the repository:

```bash
git clone https://github.com/natashazywczyk/emerging-technologies.git
```

### 2. Go into the cloned repository:

```bash
cd emerging-technologies
```

### 3. Install required dependencies:

```bash
pip install -r requirements.txt
```

### 4. Start up the Jupyter Notebook:

```bash
jupyter notebook problems.ipynb
```

- If Jupyter is not already installed:

    ```bash
    pip install jupyter
    ```

## Running the Code

- All code is provided in `problems.ipynb`
- Either **Run All** or run each cell individually
- Run from the top
- No external files necessary

## Reference
The main reference used throughout the `problems.ipynb` notebook is the [IBM Quantum Platform](https://quantum.cloud.ibm.com/learning/en).