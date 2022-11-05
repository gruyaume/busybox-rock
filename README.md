# Busybox Rock

Distroless OCI image for [Busybox](https://busybox.net/) built using [rockcraft](https://github.com/canonical/rockcraft). 

## Usage

```bash
docker pull ghcr.io/gruyaume/busybox:1.34.1
docker run -it ghcr.io/gruyaume/busybox:1.34.1
```

From the container, you can run all busybox commands prefixed by `busybox`:

```bash
busybox ls
busybox ip addr
```
