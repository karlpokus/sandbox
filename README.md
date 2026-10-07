# sandbox
A sandbox tools lab

# firecracker

- [x] Boot example. Download prebuilt guest kernel and rootfs from https://github.com/firecracker-microvm/firecracker/blob/main/docs/getting-started.md to an `artifacts` dir.

````sh
$ path/to/firecracker --no-api --config-file firecracker.json
````

- [x] pick another kernel and fs like BusyBox v1.36.1, linux 6.12.58

````sh
$ path/to/firecracker --no-api --config-file firecracker-custom.json
````

- [ ] vsock (initial tests on local branch cf/vsock)
- [ ] try jailer
- [ ] use --api-sock and --enable-pci

# k8s sandbox

See k8s dir.