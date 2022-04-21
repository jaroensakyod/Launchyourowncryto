# Launch your own cryto

### Library

`cargo install spl-token-cli`
----------
### Generating a new keypair

`solana-keygen new --force`
----------
### Keygen

`solana-keygen pubkey`
----------
### Requesting airdrop of 2 SOL

`solana airdrop 2 --url devnet`
----------
### Creating token

`spl-token create-token --url devnet`


Creating token address <tokenAdderss>

----------
### Mint your token

`spl-token create-account <tokenAdderss> --url devnet`

Creating my token account <MyTokenAddress>

----------
### Chack token balace 

`spl-token balance <tokenAdderss> --url devnet`
----------

### Mint token

`spl-token mint <tokenAdderss> 1000 --url devnet`

----------
# Limit the total supply of your token and burn your token
----------

### Chack supply

 `spl-token supply <tokenAdderss> --url devnet`
----------

### Limit supply token
`spl-token authorize <tokenAdderss> mint --disable --url devnet`

----------
### Burn

`spl-token burn <MyTokenAddress> 100 --url devnet`

---------
### Transfer
`spl-token transfer <tokenAdderss> 100 <OtherWalletAddress> --url devnet --allow-unfunded-recipient`
