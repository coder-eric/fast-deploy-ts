fastdeploy
==========

fast deploy..

[![Version](https://img.shields.io/npm/v/fastdeploy.svg)](https://npmjs.org/package/fastdeploy)
[![CircleCI](https://circleci.com/gh/dmoosocool/fast-deploy-ts/tree/master.svg?style=shield)](https://circleci.com/gh/dmoosocool/fast-deploy-ts/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/dmoosocool/fast-deploy-ts?branch=master&svg=true)](https://ci.appveyor.com/project/dmoosocool/fast-deploy-ts/branch/master)
[![Codecov](https://codecov.io/gh/dmoosocool/fast-deploy-ts/branch/master/graph/badge.svg)](https://codecov.io/gh/dmoosocool/fast-deploy-ts)
[![Downloads/week](https://img.shields.io/npm/dw/fastdeploy.svg)](https://npmjs.org/package/fastdeploy)
[![License](https://img.shields.io/npm/l/fastdeploy.svg)](https://github.com/dmoosocool/fast-deploy-ts/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g fastdeploy
$ fastdeploy COMMAND
running command...
$ fastdeploy (-v|--version|version)
fastdeploy/0.0.0 darwin-x64 node-v9.7.1
$ fastdeploy --help [COMMAND]
USAGE
  $ fastdeploy COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`fastdeploy hello [FILE]`](#fastdeploy-hello-file)
* [`fastdeploy help [COMMAND]`](#fastdeploy-help-command)

## `fastdeploy hello [FILE]`

describe the command here

```
USAGE
  $ fastdeploy hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ fastdeploy hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/dmoosocool/fast-deploy-ts/blob/v0.0.0/src/commands/hello.ts)_

## `fastdeploy help [COMMAND]`

display help for fastdeploy

```
USAGE
  $ fastdeploy help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v1.2.4/src/commands/help.ts)_
<!-- commandsstop -->
