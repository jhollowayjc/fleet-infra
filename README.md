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


### deploy mgmt profile

```
k apply -k ./profiles/mgmt
```
