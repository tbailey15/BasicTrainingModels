# Basic Training Models

This project uses a small made-up table to predict `y` from `x`. The notebook splits the rows, tries gradient descent and a few polynomial models, picks one model with the validation rows, and checks that choice once on the test rows.

## Files

- `BasicTrainingModelsDemo.ipynb` — the notebook with each step
- `training_models_demo.csv` — the data, with columns `x` and `y`
- `requirements.txt` — the Python packages the notebook needs

## Install

```bash
python -m pip install -r requirements.txt
```

## Run

Open `BasicTrainingModelsDemo.ipynb` in VS Code or Jupyter. Choose the Python kernel where those packages are installed. Run the cells from top to bottom. Keep the CSV in the same folder as the notebook.

## What I learned

I learned to split the data before exploring it, how a gradient step updates the weights, and why a model that fits the training rows can still have the wrong shape. I used validation scores to pick a model, then looked at the test score only once.
