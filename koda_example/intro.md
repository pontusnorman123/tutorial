

export CR_PAT=YOUR_TOKEN
echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
# Pull the latest version
docker pull ghcr.io/mlflow/mlflow 
```{{exec}}

