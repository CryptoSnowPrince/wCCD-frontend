# wCCD web application

The example project included in this repository serves as a working example of how to integrate with smart contracts on the Concordium blockchain. This web app interacts with the wCCD protocol on testnet. The connected account can invoke the wrap/unwrap functions to observe the wCCD balance change of its account.

## Prerequisites

-   Browser wallet extension must be installed in google chrome and configured with testnet JSON-RPC, in order to view smart contract details or submit transactions.

## Running the wCCD example in Windows
On ubuntu, because line ending issue, it was fail.
This is working on Windows 10

```
yarn
yarn start
```

Open http://127.0.0.1:8080 in your browser.

## Deploy on hosting server
```
firebase init
select dist folder to upload
firebase deploy
```