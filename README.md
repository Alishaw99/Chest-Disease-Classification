# Chest-Disease-Classification-from-Chest-CT-Scan-Image

 - [Data link](https://drive.google.com/file/d/1z0mreUtRmR-P-magILsDR3T7M6IkGXtY/view?usp=sharing)

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 



## Live matarials docs

[link](https://docs.google.com/document/d/1UFiHnyKRqgx8Lodsvdzu58LbVjdWHNf-uab2WmhE0A4/edit?usp=sharing)


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
MLFLOW_TRACKING_URI=https://dagshub.com/tariqham/Mlflow-Experiment-demo.mlflow \
MLFLOW_TRACKING_USERNAME=tariqham \
MLFLOW_TRACKING_PASSWORD=67b5006e1ee61a2915cacd824b1d9bf9246749c2   \
python script.py
```


### RUN from bash terminal

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/MLflow-Expriement-demo.mlflow

export MLFLOW_TRACKING_USERNAME=entbappy 

export MLFLOW_TRACKING_PASSWORD=67b5006e1ee61a2915cacd824b1d9bf9246749c2 

```