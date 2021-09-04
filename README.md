# geth-container

docker pull ethereum/client-go:latest

docker run -it -v /Users/jasonallen/Library/Ethereum/:/root/.ethereum -p 8545:8545 ethereum/client-go --syncmode fast --ropsten --http --http.addr "0.0.0.0" --http.corsdomain 'http://localhost:3000'
