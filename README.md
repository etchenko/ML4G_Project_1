# ML4G_Project_1
Repo for the Machine Learning for Genomics  Project 1

## Setup

### 1. Get the data
Download the competition data from the [Kaggle competition's Data tab](https://www.kaggle.com/competitions/ml-4-g-project-1/data) and put the `.zip` files, unextracted, in `data/input/`:

```
data/
└── input/
    ├── CAGE-train.zip
    ├── DNase-bed.zip
    ├── DNase-bigwig.zip
    └── ...
```

You don't need to unzip anything. The notebook extracts the archives into `data/working/extracted/` the first time it runs. Everything under `data/` is gitignored, so none of it gets committed.

### 2. Create the Python environment
From the repo root:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

If you install a new package, add it to `requirements.txt`.

### 3. Run the notebook
Open `project-1-solution-template-notebook.ipynb` and run all cells. It writes the submission to `data/working/submission.csv`.
