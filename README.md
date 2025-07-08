# Cosmos Data Analysis

This repository is an example of strucutre for a basic data analysis.

## Project Structure
``` 
project/ 
├── data/
│   ├── cleaned/
│   ├── processed/
│   └── raw/
├── models/
├── notebooks/
├── results/
│   └── figures/
├── .gitignore
├── environment.yml
└── README.md
```

- `data`: Folder for all data files. It's a good practice to organize it into `raw`, `cleaned`, and `processed` subfolders.
- `models`: Stores trained model files.
- `notebooks`: Contains Jupyter notebooks used for data exploration, analysis, and modeling.
- `results`: Saves results including `figures`.
- `.gitignore`: Specifies files and directories to exclude from version control. Will be discussed later.
- `environment.yml`: Defines the Conda environment with required dependencies.
- `README.md`: Provides an overview and documentation for the project.

## Instructions
#### Fork
Only one group member should do these steps.
1. Sign in with **group** Github account.
2. Click the "Fork" button (top-right).
3. Choose the **group** Github account as the owner.
4. Name your repository (e.g. `TheOptimizer`) and set it to **Private**.
5. Go to **Settings**->**Collaborators**, and add other team members.

#### Clone
All the group members should do these steps.
1. Sign in with **personal** Github account.
2. Go to the repository.
3. Click the green "Code" button and copy the HTTPS URL.
4. Open terminal and type `cd Desktop` and press enter.
5. Type `git clone <URL>` and press enter. (Press `Cmd + V` or `Ctrl+V` to paste the URL)

After this, there should be two directories on your Desktop (or anywhere you want). Note that `cosmos` directory is for class activity, and this directory is for your project.
