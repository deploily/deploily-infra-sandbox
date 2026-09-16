# Deploy sandbox deploily backend 


## Setup local domain name resolution


Add the following to `/etc/hosts`
```bash
127.0.0.1 deploily.local
localhost deploily.local

```


## Deploy

```bash
kubectl create ns deploily

```


## TODOs

-[ ] Add manifest for keycloak and related setup
-[ ] Add manifest for Redis and related setup 
-[ ] Add manifest for Rancher and related setup 

