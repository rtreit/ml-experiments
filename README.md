# ml-experiments
Random machine learning experiments.

# Environment

```text
conda create --name mlexp python=3.10
conda activate mlexp
conda install jupyter notebook --yes
conda install -c anaconda pandas --yes
conda install -c conda-forge seaborn --yes
conda install -c conda-forge hvplot --yes
conda install -c conda-forge scikit-learn --yes
conda install -c conda-forge xgboost --yes
conda install -c conda-forge lightgbm --yes
conda install -c conda-forge catboost --yes
```

Or:

```text
conda deactivate
conda create -y --name mlexp python=3.10
conda install --force-reinstall -y -q --name mlexp -c conda-forge --file requirements.txt
conda activate mlexp
```