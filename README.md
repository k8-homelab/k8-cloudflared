# K8-cloudflared

## What it does
Creates a tunnel between cloudflared and K8 cluster.

## How to configure for you
Be sure to update your api secret token to [sealed-secret.yaml](helm/templates//sealed-secret.yaml)

Modify the files in [values.yaml](helm/values.yaml) to customize to your environment.  
``
namespace: your-custom-namespace
```

## Install
`skaffold deploy`