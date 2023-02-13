# elixir-node

    wget https://testnet-1-files.elixir.finance/Dockerfile
    
    nano Dockerfile 
### update private and address.
    docker build . -f Dockerfile -t elixir-validator 
    
    docker run -d --restart unless-stopped  --name elixir elixir-validator
## Check 
    https://metrics.elixir.finance/
