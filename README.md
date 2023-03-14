# elixir-node

    docker build . -t elixir-validator --pull
### update private and address.

    
    docker run -d --restart unless-stopped -e ADDRESS= -e PRIVATE_KEY= --name elixir elixir-validator
## Check 
    https://metrics.elixir.finance/
