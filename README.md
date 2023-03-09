# HuggingFace Ship Detection Competition Baseline w/ YOLOv8

## Installation & Prequities to run the Notebook

### Download Dataset from HuggingFace

Step 1: Install huggingface-cli

Step 2: Authenticate ID through huggingface-cli with token.

Step 3: Download Data

```
git lfs install
git clone https://huggingface.co/datasets/datadrivenscience/ship-detection
# if you want to clone without large files – just their pointers
# prepend your git clone with the following env var:
GIT_LFS_SKIP_SMUDGE=1
```
Step 4: Extract folders in the same location as in notebook parameter {IMAGE_DIR}

Step 5: Use train.csv & adjust location in ```train_df = pd.read_csv('train.csv')``` 

Step 6: Install YOLOv8 ``` pip install ultralytics ``` 

Step 7: Run notebook...

### Good luck.
