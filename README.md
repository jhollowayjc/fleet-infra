#

## local dev

### create kind cluster

```bash
kind create cluster
```

### bootstrap

```bash
k apply -f ./bootstrap
```


### deploy cluster configuration

```
k apply -f ./clusters/kind-mgmt
```
