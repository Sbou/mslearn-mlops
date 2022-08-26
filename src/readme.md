# create datastore

```bash
az ml data create -f src/datastore.yml --resource-group dp-090-learning --workspace-name aml-ws
```

# execute job

```bash
az ml job create -f src/job.yml --resource-group dp-090-learning --workspace-name aml-ws
```