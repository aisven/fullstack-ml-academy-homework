# Fullstack ML Academy - Homework

This project contains some Jupyter Notebooks and other code as part of homework.

Topics include:

* Exploratory Data Analysis
* Correlation vs. Causation
* Confusion Matrix, Sensitivity & Specificity, ...
* Dimensionality Reduction, Principal Component Analysis
* t-distributed Stochastic Neighbor Embedding (t-SNE)
* Auto Encoders & Embeddings
* Gradient Descent
* Loss Functions
* Optimizers
* Perceptron
* Artificial Neural Networks (FFNN, CNN, RNN, ...)
* Classification
* Regression
* Hyperparameter Optimization
* Time Series Forecasting using LSTM RNN

## Disclaimer regarding the code

The code has been written in a relatively verbose free style for studying purposes. It is not production-ready and it is not to be regarded as research-related or blog-article code. Inline comments have been written to verbosely describe aspects that came up during coding. Assertions have been added to confirm certain conditions along the way.

## Setup

This section describes the usual setup procedures as conceived by the academy. However, this project can be setup and used in different ways if desired.

### Visual Studio Code

This repository is optimized for [Visual Studio Code](https://code.visualstudio.com/) which is a great code editor for many languages like Python and Javascript. The [introduction videos](https://code.visualstudio.com/docs/getstarted/introvideos) explain how to work with VS Code. The [Python tutorial](https://code.visualstudio.com/docs/python/python-tutorial) provides an introduction about common topics like code editing, linting, debugging and testing in Python. There is also a section about [Python virtual environments](https://code.visualstudio.com/docs/python/environments) which you will need in development. There is also a [Data Science](https://code.visualstudio.com/docs/datascience/overview) section showing how to work with Jupyter Notebooks and common Machine Learning libraries.

The `.vscode` directory contains configurations for useful extensions like [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens0) and [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python). When opening the repository, VS Code will open a prompt to install the recommended extensions.

### Development Setup

Open the [integrated terminal](https://code.visualstudio.com/docs/editor/integrated-terminal) and run the setup script for your OS (see below). This will install a [Python virtual environment](https://docs.python.org/3/library/venv.html) with all packages specified in `requirements.txt`.

#### Linux and Mac Users

1. run the setup script: `./setup.sh` or `sh setup.sh`
2. activate the python environment: `source .venv/bin/activate`
3. run example code: `python src/hello.py`
4. install new dependency: `pip install sklearn`
5. save current installed dependencies back to requirements.txt: `pip freeze > requirements.txt`

#### Windows Users

1. run the setup script `.\setup.ps1`
2. activate the python environment: `.\.venv\Scripts\Activate.ps1`
3. run example code: `python src/hello.py`
4. install new dependency: `pip install sklearn`
5. save current installed dependencies back to requirements.txt: `pip freeze > requirements.txt`

#### Troubleshooting

- If your system does not allow to run powershell scripts, try to set the execution policy: `Set-ExecutionPolicy RemoteSigned`, see https://www.stanleyulili.com/powershell/solution-to-running-scripts-is-disabled-on-this-system-error-on-powershell/
- If you still cannot run the setup.ps1 script, open it and copy all the commands step by step in your terminal and execute each step

Windows users can follow the official microsoft tutorial to install python, git and vscode here:

- ​​https://docs.microsoft.com/en-us/windows/python/beginners
- German: https://docs.microsoft.com/de-de/windows/python/beginners
