# elixir-node

    docker build . -t elixir-validator --build-arg ADDRESS= --build-arg PRIVATE_KEY= --pull
### update private and address.

    
    docker run -d --restart unless-stopped  --name elixir elixir-validator
## Check 
    https://metrics.elixir.finance/
