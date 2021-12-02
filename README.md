# Olive utilities

<p align="center">
  <a href="https://aave.com/" rel="noopener" target="_blank"><img width="150" src="https://olive.cash/logo.png" alt="Aave logo"></a></p>

<h1 align="center">Olive utilities</h1>

## Installation

Aave utilities are available as npm
packages[¹](https://www.npmjs.com/package/@olive-dev/contract-helpers)[²](https://www.npmjs.com/package/@olive-dev/math-utils).

```sh
// with npm
npm install @olive-dev/contract-helpers @olive-dev/math-utils
// with yarn
yarn add @olive-dev/contract-helpers @olive-dev/math-utils
```

## Usage

Here is a quick example to get you started:

```ts
import { PermissionManager } from '@olive-dev/contract-helpers';

const instance = new PermissionManager({
  provider: rpcProvider,
  permissionManagerAddress: permissionManagerAddress,
});
const permissions = await instance.getHumanizedUserPermissions(walletAddress);
```

## Examples

Are you looking for an example project to get started? Check out repositories
relying on this library:

- [The open source aave ui](https://github.com/olive-cash/aave-ui)
- [Aave info](https://github.com/sakulstra/info.aave)
