## Dry Run Install Helm Chart
```
helm install --name RELEASE_NAME . --dry-run --debug
```

## Install Helm Chart  
```
helm install --name RELEASE_NAME .
```

## Delete Helm Chart Release  
```
helm delete RELEASE_NAME --purge
```

## List Releases
```
helm list
```

## Show status of a named release
```
helm status RELEASE_NAME
```
