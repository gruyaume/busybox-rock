# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:busybox_1.34.1_amd64.rock docker-daemon:busybox:1.34.1
docker run busybox:1.34.1
```
