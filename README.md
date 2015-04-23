# Dockito DevBox Image

Image builder for the ultimate development box using [CoreOS](http://coreos.com/).

It packs a bunch of cool stuff to easy the development of [Docker](http://docker.io/) applications:

* [Docker compose](https://github.com/docker/compose);
* [Fig](http://fig.sh/) (for legacy applications);
* [Nginx proxy](https://github.com/dockito/proxy);
* [Dockito vault](https://github.com/dockito/vault);
* And a local DNS server.

## Usage

This is just an image, for more information on how to use this projet, check [dockito/devbox](https://github.com/dockito/devbox).

## Build

You will need Packer.io installed, VMWare Fusion and/or VirtualBox.

```bash
packer build devbox.json
```

## Caveats

* It only supports synced folders through [RSync](https://docs.vagrantup.com/v2/synced-folders/rsync.html) and [NFS](https://docs.vagrantup.com/v2/synced-folders/nfs.html).
