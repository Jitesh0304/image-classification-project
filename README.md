# image-classification-project
Deployment



Update config.yaml
Update secrets.yaml [Optional]
Update params.yaml
Update the entity
Update the configuration manager in src config
Update the components
Update the pipeline
Update the main.py
Update the dvc.yaml



tensorboard --logdir artifacts/prepare_callbacks/tensorboard_log_dir



dvc init         ## Run this command after completing the dvc.yaml file code ....initialize dvc command ... 
dvc repro           ## irun this command to exicute your code what ever you have written in dvc.yaml
dvc dag         ## it will show you which stage of your code is dependent on which stage
