```bash
docker build --tag cexiolabs/freeton-node --file docker/alpine/Dockerfile --build-arg TON_ARCH=native . && docker run --tty --interactive --rm cexiolabs/freeton-node
```

* Source of patches/0001-Fix-for-neighbours-unreliability.patch: https://github.com/tonlabs/main.ton.dev/blob/6e4c842aceb2c52229730cab0fd394a4ae944e84/patches/0001-Fix-for-neighbours-unreliability.patch
* Source of support/share/freeton-mainnet-global.config.json: https://github.com/tonlabs/main.ton.dev/blob/f796da157d9741a12ec7ee2ca929fe2c18e46a73/configs/ton-global.config.json
* Source of support/share/freeton-testnet-global.config.json: https://github.com/tonlabs/net.ton.dev/blob/5e0fc9790cc337a390e469d3267a02b141ef177d/configs/ton-global.config.json
