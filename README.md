# end-to-end-chest-cancer-classification-using-mlflow-and-dvc



## Workflows
1. Update config.yaml
2. Update secrets.yaml (optional)
3. Update params.yaml
4. Update the entity
5. Update the config manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml

''' cmd
set MLFLOW_TRACKING_URI=https://dagshub.com/deepsuchak/end-to-end-chest-classification-using-mlflow-and-dvc.mlflow 
set MLFLOW_TRACKING_USERNAME=deepsuchak 
set MLFLOW_TRACKING_PASSWORD=1bae85f3cea917e576bbd13345890a218661c7ce 
'''
- before running make sure to remove artifacts,dvc.lock and .dvc
- just keep dvc.yaml