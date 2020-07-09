# Kitchen-ansible test playground #

## Prerequisites ##

`libvirt` and `vagrant-libvirt` are required.

Be sure to tell vagrant to use `libvirt`:

```bash
export VAGRANT_DEFAULT_PROVIDER=libvirt
```

## Installation ##

git clone this repo

```bash
bundle
```

## Testing ##

`bundle exec kitchen test`

_caveat: only freebsd working correctly right now_

## Tweaks ##

Edit the `Vagrantfile` to change cpu/memory parameters to your liking.
