# Chest-Disease-Classification-from-Chest-CT-Scan-Image


## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 




## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

### Mlflow dagshub connection uri

```bash
MLFLOW_TRACKING_URI=https://dagshub.com/kshitijkutumbe/ml-flow-demo.mlflow \
MLFLOW_TRACKING_USERNAME=kshitijkutumbe \
MLFLOW_TRACKING_PASSWORD=5c36301c94d7da5ec5c441347a77cb08f3b531eb \
python script.py
```


### RUN from bash terminal

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/Chest-Disease-Classification-from-Chest-CT-Scan-Image.mlflow

export MLFLOW_TRACKING_USERNAME=entbappy 

export MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0

```



### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag