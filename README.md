# elixir-node

    docker pull elixirprotocol/validator:testnet-2
### update private and address.

    
    docker run -d --restart unless-stopped -e ADDRESS= -e PRIVATE_KEY=  --name elixir elixirprotocol/validator:testnet-2
## Check 
    https://metrics.elixir.finance/
