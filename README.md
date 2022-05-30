# jsbox-cli

JSBox VSCode plug-in 'cli' versions.

![Travis](https://img.shields.io/travis/Dreamacro/jsbox-cli.svg?style=flat-square)
![NPM version](https://img.shields.io/npm/v/jsbox-cli.svg?style=flat-square)

## Installation

```
$ npm i jsbox-cli -g
```

## Getting Started

Set up the mobile terminal Host IP

```
$ jsbox set 192.168.1.1
```

View Current Host IP

```
$ jsbox host
```

Monitor a Directory or File

```
# Monitor the current directory
$ jsbox watch

# Listen to the specified directory
$ jsbox watch ./dist

# **Listen to the specified file**
$ jsbox watch ./index.js
```

Build JSBox Application

```
# Build the current directory, default to '.output' 
$ jsbox build

# Build the specified directory
$ jsbox build ./dist

# Custom output path
$ jsbox build ./dist -o ./dist/output.box
```
