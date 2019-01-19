## @dexon-foundation/sol-coverage

A Solidity code coverage tool.

### Read the [Documentation](https://0xproject.com/docs/sol-coverage).

## Installation

```bash
yarn add @dexon-foundation/sol-coverage
```

**Import**

```javascript
import { CoverageSubprovider } from '@dexon-foundation/sol-coverage';
```

or

```javascript
var CoverageSubprovider = require('@dexon-foundation/sol-coverage').CoverageSubprovider;
```

## Contributing

We welcome improvements and fixes from the wider community! To report bugs within this package, please create an issue in this repository.

Please read our [contribution guidelines](../../CONTRIBUTING.md) before getting started.

### Install dependencies

If you don't have yarn workspaces enabled (Yarn < v1.0) - enable them:

```bash
yarn config set workspaces-experimental true
```

Then install dependencies

```bash
yarn install
```

### Build

To build this package and all other monorepo packages that it depends on, run the following from the monorepo root directory:

```bash
PKG=@dexon-foundation/sol-coverage yarn build
```

Or continuously rebuild on change:

```bash
PKG=@dexon-foundation/sol-coverage yarn watch
```

### Clean

```bash
yarn clean
```

### Lint

```bash
yarn lint
```

### Run Tests

```bash
yarn test
```
