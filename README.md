# D3: Visualizations & Engage

[D3: Visualizations & Engage](https://github.com/Data-Git-Hub/D3-Visualizations)

## Introduction

In this notebook, I begin exploring core principles of data visualization using Python within a Jupyter Notebook environment. Visualizations play a critical role in transforming raw data into meaningful insights, allowing analysts and stakeholders to interpret trends, relationships, and anomalies quickly and effectively. By integrating tools such as matplotlib, I demonstrate the foundational skills needed to generate plots and prepare data for visual storytelling. This assignment also serves as a technical check to ensure all necessary packages are installed and that my development environment is properly configured.

## Windows Setup Instructions

Open a PowerShell terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
When asked to use the new .venv click yes. 

Important: Install from requirements first with scikit-learn commented out. 
Then remove the leading hashmark (around line 187) and re-run the command to install scikit-learn.
See requirements.txt for more information. 


```shell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```
### Remove "#" TBD. from requirements.txt

```shell
py -m pip install -r requirements.txt
```

---

## macOS/Linux Setup Instructions

Open a default terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
Important: Install from requirements first with scikit-learn commented out. 
Then remove the leading hashmark (around line 187) and re-run the command to install scikit-learn.
See requirements.txt for more information. 

```zsh
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

### Remove "#" TBD. from requirements.txt

```zsh
py -m pip install -r requirements.txt
```

---

## Tell VS Code to use .venv

Open the Command Palette: Press Ctrl + Shift + P (Windows) or Cmd + Shift + P (Mac/Linux)
Then type: Python: Select Interpreter
Press Enter.

Look for the interpreter with .venv in the path.
Click on that interpreter to select it.
Confirm it's selected: You should see the Python version and .venv path in the lower-left status bar of VS Code.

---

## Working on the Project

Open the .ipynb Jupyter notebook file in VS Code. 
Run the entire notebook before you start to edit. 
As you make progress, use Git to add, commit, and push your work to your GitHub repo.

```shell
git add .
git commit -m "describe the change here"
git push -u origin main
```

---

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

---

## Version History
- D2 Init - 0.0 - Create D3-Visualizations.ipynb, requirements.txt; Modify README.md