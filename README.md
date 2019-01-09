# Let’s Build the Tiniest Blockchain

## URLs
- [Let’s Build the Tiniest Blockchain](https://medium.com/crypto-currently/lets-build-the-tiniest-blockchain-e70965a248b)
- [Let’s Make the Tiniest Blockchain Bigger](https://medium.com/crypto-currently/lets-make-the-tiniest-blockchain-bigger-ac360a328f4d)

## GithubGist
- https://gist.github.com/aunyks/47d157f8bc7d1829a729c2a6a919c173

## Requirements
- python 3.6.1
- flask==1.0.2

## Run
```
python snakecoin_server_full_code.py
```

## Commands
### Create a transaction
```
curl "localhost:5000/txion" \
     -H "Content-Type: application/json" \
     -d '{"from": "akjflw", "to":"fjlakdj", "amount": 3}'
```

### Mine a new block
```
curl localhost:5000/mine
```

### Get blocks
```
curl localhost:500/blocks
``` 

