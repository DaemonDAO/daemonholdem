# Multiplayer Texas Hold 'Em - with a Daemonic twist
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/ptwu/distributed-texasholdem/blob/master/LICENSE)
![1.0.0](https://img.shields.io/badge/version-1.0.0-blue.svg)
![CI](https://github.com/ptwu/distributed-texasholdem/workflows/CI/badge.svg)

Forked from https://github.com/ptwu/distributed-texasholdem

Using `socket.io`, `Node.js`, and `express` to make a distributed poker game. Allows for multiple
gameplay rooms simultaneously across different devices.

## To Do
- Understand `socket.io`, `Node.js`, and `express` framework - perform rigorous testing
- use we3.js to tie connected web3 wallet to user account
- smart contract to handle buy-in and winnings distribution
- smart contract to manage subscriptions



## Commands
`yarn install` installs all the dependencies required to run the webapp.

`yarn dev` starts the game with hot reloading provided by `nodemon`.
  - The game will be viewable by navigating to `localhost:3000`.

`yarn start` runs the Node server without hot reloading. Intended for deployment use.

`yarn test` evaluates the unit tests located in test/classes/

