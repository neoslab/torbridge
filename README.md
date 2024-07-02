# Torbridge

Script to redirect all traffic through Tor network including DNS queries for anonymizing entire system

* * *

## Installation

```shell
cd /tmp/
git clone https://github.com/neoslab/torbridge
chmod +x /tmp/torbridge/torbridge
sudo mv /tmp/torbridge/torbridge /usr/local/bin/
```

* * *

## Usage

```shell
$ sudo torbridge --help

Usage: torbridge [-h|--help] [--start] [--stop] [--status] [--restart] [--showip] [--switchid] [--changemac] [--revertmac] [--version]

Options:
 -h, --help           show this help
 --start              start redirecting all traffic through Tor
 --stop               stop redirecting all traffic through Tor
 --status             check Tor service status
 --restart            restart Tor and traffic rules
 --showip             display Tor IP address
 --switchid           switch Tor identity
 --changemac          change mac addresses of all interfaces
 --version            display current version of TorBridge
```