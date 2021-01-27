# carti-default
A collection of the default cartesi machine bundles. This allows you to install global defaults that are compatible with machine init.

## Usage
These are easily installed via
```sh
# adds the bundles.json from the repo
carti repo add https://github.com/createdreamtech/carti-default
# installs all of the bundles into the global bundles, so every project has access to the defaults
carti machine install -g https://raw.githubusercontent.com/createdreamtech/carti-default/main/carti-machine-package.json --nobundle --nobuild
```
### Updates will happen but will be additive to the bundles.json
