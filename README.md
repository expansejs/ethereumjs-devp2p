# expansejs-devp2p
[![NPM Package](https://img.shields.io/npm/v/expansejs-devp2p.svg?style=flat-square)](https://www.npmjs.org/package/expansejs-devp2p)
[![Build Status](https://img.shields.io/travis/expansejs/expansejs-devp2p.svg?branch=master&style=flat-square)](https://travis-ci.org/expansejs/expansejs-devp2p)
[![Coverage Status](https://img.shields.io/coveralls/expansejs/expansejs-devp2p.svg?style=flat-square)](https://coveralls.io/r/expansejs/expansejs-devp2p)
[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

An node.js implementation of

- devp2p's Distrubuted Peer Table
- RLPx transport protocol
- Ethereum wire protocol
- Tailored for Expanse

Forked from [ethereumjs/ethereumjs-devp2p](https://github.com/ethereumjs/node-devp2p).
Based on [ethereumjs/node-devp2p](https://github.com/ethereumjs/node-devp2p).

# Example

  - [bootstrap](examples/bootstrap.js) Run DPT node
  - [inv](examples/inv.js) Print all new Tx and Block hashes

for example: `node -r babel-register ./examples/inv.js`

# Reference

- [RLPx Node Discovery Protocol](https://github.com/ethereum/go-ethereum/wiki/RLPx-----Node-Discovery-Protocol) (outdated)
- [Node discovery protocol](https://github.com/ethereum/wiki/wiki/Node-discovery-protocol)
- [RLPx: Cryptographic Network & Transport Protocol](https://github.com/ethereum/devp2p/blob/master/rlpx.md)
- [devp2p wire protocol](https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol)
- [Ethereum wire protocol](https://github.com/ethereum/wiki/wiki/Ethereum-Wire-Protocol)

# License

MIT
