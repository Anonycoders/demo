# demo
cross-platform demo for text-mining.ir APIs


## How to deploy on [Fandogh](https://fandogh.cloud)

### One time steps

- Install [Fandogh CLI](https://docs.fandogh.cloud/docs/getting-started.html)
- Run `fandogh image init --name text_miner`

### Publish image

```fandogh image publish --version IMAGE_VERSION```

### Deploy Service
```fandogh service apply -f service_manifest.yml -p IMAGE_VERSION=YOUR_IMAGE_VERSION```
