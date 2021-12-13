# Learn [Ray](https://docs.ray.io/en/master/index.html)

## Get the total number of available cluster nodes

```Python
len(ray.nodes())
```

## Get the total number of available CPU cores

```Python
ray.cluster_resources()[“CPU”]  # CPU: cores
```
