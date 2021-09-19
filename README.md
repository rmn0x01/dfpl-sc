# NFT Series Implementation

## Instructions

`yarn && yarn test:deploy`

#### Pre-reqs

Rust, cargo, near-cli, etc...
Everything should work if you have NEAR development env for Rust contracts set up.

[Contract](contract/src/lib.rs)

## Example Call

### Deploy
```
near deploy --accountId contract_account.testnet
```

### NFT init
```
near call --accountId contract_account.testnet contract_account.testnet new_default_meta '{"owner_id":"owner_account.testnet"}'
```