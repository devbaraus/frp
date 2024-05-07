# Dockerfile and docker-compose for `fatedier/frp`

## Usage

```bash
# frpc
cp config/frpc.sample.toml config/frpc.toml
emacs -nw config/frpc.toml
docker-compose up -d frpc

# frps
cp config/frps.sample.toml config/frps.toml
emacs -nw config/frps.toml
docker-compose up -d frps
```

> Also check [ `docker-compose.yml` ](docker-compose.yml) for ports settings.

## SEEALSO

- [fatedier/frp](https://github.com/fatedier/frp)
