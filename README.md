# bitclimb-parity

Heavily based on [parity/api](https://github.com/parity-js/api) with some minor changes to meet the needs of bitclimb.

## Changes

- Remove `window` references on `src/transport/ws/ws.js`
- Remove unneeded polyfill

## TODO

- Enable IPC for nodejs environment
- Use bitclimb-ipc module
- Remove other references to window/electron