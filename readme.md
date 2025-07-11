# PCOS Experiment

## Overview
The workflow includes:

1. **Data Preprocessing**: Process raw data from `dataset/` into `PCOS_processed.csv`.
2. **Causal Graph Construction**: Generate a causal graph using `pycausal_PCOS.ipynb`, saved as `test.gv` and `test.gv.png`.
3. **Causal Inference and ML Validation**: Perform CIDW (Causal Inference with Direct Weights) `InferWith_parameter.ipynb` and CIMW (Causal Inference with Matching Weights) in `InferWithout_parameter.ipynb`.

## Dependencies
Install required Python libraries:
```bash
pip install pandas numpy scikit-learn pycausal graphviz jupyter statsmodels matplotlib seaborn argparse pathlib
```

## Usage
### 1. Data Preprocessing
```bash
jupyter notebook pcos-prediction-and-analysis.ipynb  # run some cells
```

### 2. Causal Graph Construction
```bash
jupyter notebook pycausal_PCOS.ipynb
```

### 3. Causal Inference & ML Experiment
```bash
jupyter notebook InferWith_parameter.ipynb
jupyter notebook InferWithout_parameter.ipynb
```


