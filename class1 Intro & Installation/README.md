# Saylani Python Programming (9:00pm to 11:00pm)

## class1 - Project Setup Guide

This guide explains how to set up the development environment using Anaconda, Visual Studio Code (VS Code), Python & Gitbash for Version Controlling.

### Prerequisites

- [Anaconda](https://www.anaconda.com/products/individual#Downloads)
- [GitBash](https://git-scm.com/downloads)

### Installation Guide

- [Anaconda Installation Guide](https://github.com/aiwithqasim/Saylani_Python_911/blob/dev/docs/Anaconda%26%20JupyterNotebook%20Installation.pdf)
- [GitBash Installation Guide](https://github.com/aiwithqasim/Saylani_Python_911/blob/dev/docs/GtiBash%20Installation.pdf)

---

## TABLE OF CONTENT

1. [Running a "Hello World" Program](#running-a-hello-world-program)
2. [Setting Up a Virtual/Conda Environment](#setting-up-a-virtual-environment)

## Running a "Hello World" Program

You can run a simple "Hello World" program to ensure that your python setup is working as expected.

### Using Command Prompt on Windows

1. Open Command prompt (CLI)
2. Validate Conda & Pythonn are successfully installed.

    ```bash
    conda --version 
    python --version
    ```

3. Open Python Environment on Command Prompt (CLI)

    ```bash
    python [Hit enter you will be in Python Enviornment of CLI]
    ```

4. Run the following Python command:

    ```bash
    print("Hello Saylani...!!!")
    ```

### Using Jupyter Notebook (.ipynb file)

1. Goto any specified folder you want eg:`/Documents/Python912`
2. From the address bar of that folder open Command prompt (CLI)
3. Type `jupyter notebook` to open Jupyter Notebook
4. create a new Jupyter Notebook called `class1.ipynb`.
5. Insert the following Python code into a new cell:

    ```python
    print("Hello world")
    ```

3. Click on the Run button (SHIFT+ENTER) to execute the cell.

---

## Setting Up a Virtual Environment

### Creating a New Environment

1. Run the following command to create a new Conda environment:

    ```bash
    conda create --name <env_name> 
    # Example: conda create --name python912 
    ```

2. Activate your newly created environment:

    ```bash
    conda activate <env_name>
    # Example: conda activate python912
    ```

3. Check names of your already created environments lists

    ```bash
    conda env list
    ```

### Installing Required Packages

1. Create a `requirements.txt` file with the following content:

    ```
    numpy
    ```

2. Run the following command to install the required packages:

    ```bash
    pip install -r requirements.txt
    ```
3. For more relevant commands following are the suitable links

    - [Managing conda environments](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment)
    - [Virtual Environment Creation - conda/venv](https://github.com/aiwithqasim/Saylani-AI-Batch2/blob/main/03%20Python/README.md)
---





