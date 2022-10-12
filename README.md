# hardhat-yul

[![npm](https://img.shields.io/npm/v/@tovarishfin/hardhat-yul.svg)](https://www.npmjs.com/package/@tovarishfin/hardhat-yul) [![hardhat](https://hardhat.org/buidler-plugin-badge.svg?1)](https://hardhat.org)

[Hardhat](https://hardhat.org) plugin to develop smart contracts with Yul and/or Yul+.

## What

This plugin adds support for Yul and Yul+ to Hardhat. Once installed, Yul contracts can be compiled by running the `compile` task.

The Yul compiler is run using the [official solc compiler](https://github.com/ethereum/solc-js#readme).

The Yul+ compiler is run using the [Yul+ transpiler from FuelLabs](https://github.com/FuelLabs/yulp) before being passed to the Yul compiler.

## Installation

First, you need to install the plugin by running

```bash
npm install --save-dev @tovarishfin/hardhat-yul
```

And add the following statement to your `hardhat.config.js`:

```js
require("@tovarishfin/hardhat-yul");
```

Or, if you are using TypeScript, add this to your `hardhat.config.ts`:

```ts
import "@tovarishfin/hardhat-yul";
```

## Required plugins

No plugins dependencies.

## Tasks

This plugin creates no additional tasks.

## Environment extensions

This plugin does not extend the Hardhat Runtime Environment.

## Configuration

At the time, there are no configuration options. This might change in the future.

## Usage

There are no additional steps you need to take for this plugin to work.

### Additional notes

This is mainly working because of TovarishFin and his fork. I merged his work upstream so that the working plugin shows up because of SEO, but if you encounter issues with this plugin please defer to there
