# Info-Collectro-Linux-Tool
CLI Linux tool for collect info about your system. 

The tool can mine:
* CPU
* Network usage (Network board)
* Memory
* Disk


## Install tool
1. Clone Repo
```
$ git clone https://github.com/Bernal-R/Info-Collectro-Linux-Tool.git
```

2. Copy compiled file in /bin/
```
$ sudo cp install/miner /bin/
```

## Troubleshooting
Is possible that you get error: *Pemisson denied*

For fix that, you need run:

```
$ chmod +x miner
```

## Usage 
```
$ miner args
```
The tool expected arguments, that can be:

Argument | Mean
------------ | -------------
c | CPU miner
m | Memory miner
d | Disk miner
n | Network miner


Usage example:
```
$ miner c n m d
```
