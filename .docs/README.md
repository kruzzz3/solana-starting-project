## Wallet
similar pottery enroll refuse abstract sunny retire ostrich lazy mercy employ engage



## Start local Solana cluster
This example connects to a local Solana cluster by default.

### Start a local Solana cluster:
````
solana-test-validator
````

### Listen to transaction logs:
````
solana logs
````


## On-chain program

### Build
````
npm run build:program-rust
````

### Deploy
````
solana program deploy dist/program/helloworld.so
````


## Client program

### Run the JavaScript client
````
npm run start
````

cargo test -- --nocapture

solana config set --url https://api.devnet.solana.com


Program Id: 4pdZEGKuFV23Wwp41oLmoxBKRxorHBhd1LoF7h1rvLHR