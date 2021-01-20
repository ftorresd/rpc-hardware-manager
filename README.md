### Development Env

#### Build

```
docker build -t rpc-hardware-manager_dev_env docker/dev_env
```

#### Run

```
docker run -v `pwd`:/rpc-hardware-manager -it --rm rpc-hardware-manager_dev_env
```