# elixir-node

    docker pull elixirprotocol/validator:testnet-2
### Update private and address. remove `0x` from private key if contain

    
    docker run -d --restart unless-stopped -e ADDRESS= -e PRIVATE_KEY= -e VALIDATOR_NAME= --name elixir elixirprotocol/validator:testnet-2
## Check 
    https://metrics.elixir.finance/

## Docs
[https://docs.elixir.finance/running-an-elixir-validator](https://docs.elixir.finance/running-an-elixir-validator)
