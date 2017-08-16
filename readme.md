# Hyperledger Local Testing Network

## Description
Set up the hyperleger network with docker-compose.
- Solved the issue of failing to pull the hyperledger/fabric-peer:lastest image by refering to ibmblockchian respository.

## Usage:
### Single peer:
- docker-compose -f single-peer-ca-yaml up  (start)
- docker-compose -f single-peer-ca-yaml stop (stop)

### Four peers:
- docker-compose -f four-peer-ca-yaml up  (start)
- docker-compose -f four-peer-ca-yaml stop (stop)
