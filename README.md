# unws

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Unit Test][unit-test-src]][unit-test-href]

Unified WebSocket API for Node.js, Bun and [modern browsers](https://caniuse.com/websockets).

> [!WARNING]
> For Node.js v20.10.0 and later, the [`WebSocket` global object](https://nodejs.org/api/globals.html#class-websocket) is directly accessible without requiring this package. As a result, this package is no longer maintained.

## Install

```bash
npm i unws
```

## Usage

```ts
import { WebSocket } from 'unws'

const ws = new WebSocket('ws://localhost:8080')
```

## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/sxzz/sponsors/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/sxzz/sponsors/sponsors.svg'/>
  </a>
</p>

## License

[MIT](./LICENSE) License © 2023-PRESENT [Kevin Deng](https://github.com/sxzz)

<!-- Badges -->

[npm-version-src]: https://img.shields.io/npm/v/unws.svg
[npm-version-href]: https://npmjs.com/package/unws
[npm-downloads-src]: https://img.shields.io/npm/dm/unws
[npm-downloads-href]: https://www.npmcharts.com/compare/unws?interval=30
[unit-test-src]: https://github.com/sxzz/unws/actions/workflows/unit-test.yml/badge.svg
[unit-test-href]: https://github.com/sxzz/unws/actions/workflows/unit-test.yml
