# redim
Redis image buffer and transferring

![Alt text](static/screenshot.png?raw=true "example output")

Set an image to Redis as buffer and display it separately. This script can be modified to use as an image transfer and bufferring.

## Prerequisite
A Redis server is required. Or just run an instance container:
```bash
docker run -d --name=redis --network=host redis
```
<br />

## Installation
1. Clone this repo and change directory:
```bash
git clone https://github.com/geeksloth/redim.git && cd redim
```
2. Configure ```config.json``` file:
```bash
nano config.json
```
replace ```redis -> host``` and others as needed, then save by press ```ctrl + x``` and hit ```y``` and ```enter```
<br />

## Run
1. To run the scrip:
```bash
docker compose up
```

2. Type ```http://ip:port``` to access the Setter and Getter
