# Dockito development box

Image builder for the ultimate development box.

Docker + Fig + Nginx.

## Build

You will need Packer.io installed and VMWare Fusion.

```bash
packer build devbox.json
```

## Caveats

* It only supports synced folders through [RSync](https://docs.vagrantup.com/v2/synced-folders/rsync.html) and [NFS](https://docs.vagrantup.com/v2/synced-folders/nfs.html).
