# MyBit Fork
[![CircleCI](https://circleci.com/gh/MyBitFoundation/MyBit-Payroll.tech.svg?style=shield)](https://circleci.com/gh/MyBitFoundation/MyBit-Payroll.tech) [![Coverage Status](https://coveralls.io/repos/github/MyBitFoundation/MyBit-Payroll.tech/badge.svg?branch=feature%2Fcoverage)](https://coveralls.io/github/MyBitFoundation/MyBit-Payroll.tech?branch=feature%2Fcoverage)

:moneybag: Fork Dapp powered by the MyBit Platform™

MyBit Fork is a tool to make it easy to split bills


## Setup

Install dependencies.

`yarn`

## Testing

Bootstrap [Ganache](https://truffleframework.com/ganache)

`yarn blockchain`

Run tests

`yarn test`

✏️ All contracts are written in [Solidity](https://solidity.readthedocs.io/en/v0.4.24/) version 0.4.24.


## Code Coverage

Download solidity-coverage locally

`npm install --save-dev solidity-coverage`

Run solidity-coverage

`./node_modules/.bin/solidity-coverage`

Coverage reports can be accessed at 'coverage/index.html'


## Compiling 
Navigate to the project root and run the truffle compiler

`truffle compile` 

### Dependencies 

* bignumber.js   

`npm install bignumber.js`

* solidity-docgen 

 `npm install solidity-docgen`

## Documentation

```
cd docs/website
yarn build
```

To publish to GitHub Pages

```
cd docs/website
GIT_USER=<GIT_USER> \
  USE_SSH=true \
  yarn run publish-gh-pages
```

### ⚠️ Warning
This application is unstable and has not undergone any rigorous security audits. Use at your own risk.
