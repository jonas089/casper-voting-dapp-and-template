# Voting Dapp built on Casper - a reusable React template
This template is a great starting point for Dapp development on Casper using the React framework with functional components.

## High-level Mindmap
![Mindmap](https://github.com/jonas089/casper-voting-dapp-and-template/blob/master/mindmap.png)

## Setup
The `server` folder contains a node.js backend to deploy and query a Casper network and the `service` folder houses a component to interact with and monitor the state of the Casper Wallet plugin. The `controller` constructs and forwards deploys and queries to the backend `server`.

Additionally, Tailwind is imported and components can be used out of the box. A Tailwind Navbar can be found in `components` and routes can easily be added.

**Requirement: Casper Wallet chrome plugin & funded Casper account**

## Host this Dapp locally
```
npm install 
cd server && npm install
./start_local.sh
```

-> navigate to localhost:3000


