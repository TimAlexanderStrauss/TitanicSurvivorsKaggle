# Data

Place the Titanic competition CSV files in this directory:

- `train.csv` — training set with ground-truth survival labels
- `test.csv` — test set (no labels; used for Kaggle submission)
- `gender_submission.csv` — example submission file

## Download via Kaggle CLI

```bash
pip install kaggle
kaggle competitions download -c titanic -p data/
unzip data/titanic.zip -d data/
```

> **Note:** You must have a valid `~/.kaggle/kaggle.json` API token.  
> See https://www.kaggle.com/docs/api for setup instructions.
