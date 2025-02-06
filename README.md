# unws [![npm](https://img.shields.io/npm/v/unws.svg)](https://npmjs.com/package/unws)

[![Unit Test](https://github.com/sxzz/unws/actions/workflows/unit-test.yml/badge.svg)](https://github.com/sxzz/unws/actions/workflows/unit-test.yml)

Unified WebSocket API for Node.js, Bun and [modern browsers](https://caniuse.com/websockets).

## Install

```bash
npm i unws
```

## Usage

```ts
import { WebSocket } from 'unws'

const ws = new WebSocket('ws://localhost:8080')
```

> [!TIP]
> For Node.js v20.10.0 and above, the `WebSocket` global object is directly accessible without this package.
> See [here](https://nodejs.org/api/globals.html#websocket).

## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/sxzz/sponsors/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/sxzz/sponsors/sponsors.svg'/>
  </a>
</p>

## License

[MIT](./LICENSE) License © 2023-PRESENT [三咲智子](https://github.com/sxzz)
