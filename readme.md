# Hyperledger Testing Network

## Description
Set up the hyperleger network with docker-compose
 ⋅⋅⋅Solved the issue of failing to pull the hyperledger/fabric-peer:lastest image by refering to specific version

##Usage:
single peer:
- docker-compose -f single-peer-ca-yaml up  (start)
- docker-compose -f single-peer-ca-yaml stop (stop)

four peers:
- docker-compose -f four-peer-ca-yaml up  (start)
- docker-compose -f four-peer-ca-yaml stop (stop)
