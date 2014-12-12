# Dockito development box

Image builder for the ultimate development box.

[Docker](http://docker.io/)(through [CoreOS](http://coreos.com/)) + [Fig](http://fig.sh/) + [Nginx](https://github.com/dockito/proxy).

## Usage

This is just an image, for more information on how to use this projet, check [dockito/devbox](https://github.com/dockito/devbox).

## Build

You will need Packer.io installed and VMWare Fusion.

```bash
packer build devbox.json
```

## Caveats

* It only supports synced folders through [RSync](https://docs.vagrantup.com/v2/synced-folders/rsync.html) and [NFS](https://docs.vagrantup.com/v2/synced-folders/nfs.html).
