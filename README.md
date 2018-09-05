# guld-git-config-cli

[![source](https://img.shields.io/badge/source-bitbucket-blue.svg)](https://bitbucket.org/guld/tech-js-node_modules-guld-git-config-cli) [![issues](https://img.shields.io/badge/issues-bitbucket-yellow.svg)](https://bitbucket.org/guld/tech-js-node_modules-guld-git-config-cli/issues) [![documentation](https://img.shields.io/badge/docs-guld.tech-green.svg)](https://guld.tech/cli/guld-git-config-cli.html)

[![node package manager](https://img.shields.io/npm/v/guld-git-config-cli.svg)](https://www.npmjs.com/package/guld-git-config-cli) [![travis-ci](https://travis-ci.org/guldcoin/tech-js-node_modules-guld-git-config-cli.svg)](https://travis-ci.org/guldcoin/tech-js-node_modules-guld-git-config-cli?branch=guld) [![lgtm](https://img.shields.io/lgtm/grade/javascript/b/guld/tech-js-node_modules-guld-git-config-cli.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/b/guld/tech-js-node_modules-guld-git-config-cli/context:javascript) [![david-dm](https://david-dm.org/guldcoin/tech-js-node_modules-guld-git-config-cli/status.svg)](https://david-dm.org/guldcoin/tech-js-node_modules-guld-git-config-cli) [![david-dm](https://david-dm.org/guldcoin/tech-js-node_modules-guld-git-config-cli/dev-status.svg)](https://david-dm.org/guldcoin/tech-js-node_modules-guld-git-config-cli?type=dev)

Guld configuration helper manages git config files.

### Install

##### Node

```sh
npm i -g guld-git-config-cli
```

### Usage

##### CLI

```sh
guld-git-config --help

  Usage: guld-git-config <key> [value] Get or set a config key depending on pressence of value argument.

  Guld configuration helper manages git config files.

  Options:

    -V, --version             output the version number
    --global                  Use the global config file
    --local                   Use the local config file
    --system                  Use the system config file.
    -f, --file <config-file>  Use the given config file.
    -h, --help                output usage information

  Commands:

    name                      Get the guld name of the current user.
    get <key>                 Get a config by key.
    set <key> <value>         Set a config key to the given value.
    unset                     Unset a config key.
    list                      List all config key/value pairs.

```

### License

MIT Copyright isysd
