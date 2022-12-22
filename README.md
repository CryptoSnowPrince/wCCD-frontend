# wCCD web application

The example project included in this repository serves as a working example of how to integrate with smart contracts on the Concordium blockchain. This web app interacts with the wCCD protocol on testnet. The connected account can invoke the wrap/unwrap functions to observe the wCCD balance change of its account.

## Prerequisites

-   Browser wallet extension must be installed in google chrome and configured with testnet JSON-RPC, in order to view smart contract details or submit transactions.

## Issue
On Windows, it can't build because something went wrong.
On Ubuntu, because line ending issue, it was fail.
On Ubuntu, it will build.
On Windows, it is working.

## Build on Ubuntu 20.04

```
yarn
yarn build
yarn watch
```

## Running the wCCD example on Windows

```
yarn
yarn start
```

Open http://127.0.0.1:8080 in your browser.

## Deploy on hosting server on Windows or Ubuntu 20.04
```
firebase init
select dist folder to upload
firebase deploy
```