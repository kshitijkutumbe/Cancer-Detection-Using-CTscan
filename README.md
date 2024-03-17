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

> Connect your repository on github with dagshub
> Click on the remote button 
> copy and export the credentials given on experiments tab to your system
> once everything is executed , on experiments tab itself, you can see "go to mlflow UI",click on it for visualization

```bash
MLFLOW_TRACKING_URI= get from dagshub
MLFLOW_TRACKING_USERNAME= get from dagshub
MLFLOW_TRACKING_PASSWORD= get from dagshub

python script.py
```


### RUN from bash terminal

```bash
export MLFLOW_TRACKING_URI=get from dagshub

export MLFLOW_TRACKING_USERNAME=get from dagshub

export MLFLOW_TRACKING_PASSWORD=get from dagshub


```



### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag