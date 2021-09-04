# geth-container

docker pull ethereum/client-go:latest

docker run -it -p 8545:8545 ethereum/client-go --syncmode fast --ropsten --http --httpaddr "0.0.0.0" --http.corsdomain 'http://localhost:3000'
