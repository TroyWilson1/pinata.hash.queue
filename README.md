# Pinata Hash Queue

This script takes a IPFS hash as input, along with a file name and adds it to Pinata.Cloud pin for pinning. If the pinning fails then it adds the hash to the Pinata.Cloud pin Queue for later pinning. 

## USAGE:
### Add Single File:
```
./pinata.hash.queue.py -i QmW9mfth68Fme8uTDrETUeLJizuxhiW -n photo.jpg
Hash Queued for Pin: QmW9mfth68Fme8uTDrETUeLJizuxhiW
File Name: photo.jpg
```
## Help:
```
usage: pinata.hash.queue.py [-h] [-i INPUT] [-n NAME]

Copy Hash to Pinata.Cloud 

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT, --input INPUT
                        Hash to add to Pinata.Cloud
  -n NAME, --name NAME  Name of hash added to Pinata.Cloud
```
