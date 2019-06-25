# Deterministic Builds with [Gitian](https://gitian.org)

### Running build

```sh
export USE_DOCKER=1
./run-gitian -b windws_build_update_fc -m 16000 -j 6
```

### First time setup
```sh
export USE_DOCKER=1
vendor/gitian-builder/bin/make-base-vm --docker --suite bionic
```

> `bitshares` repository is checked out in `vendor/gitian-builder/inputs/`