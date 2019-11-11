# Swapper

Swapper is a wrap command of swapon and swapoff.

## Get

```
# example: /usr/local/bin
$ curl -L https://raw.githubusercontent.com/shoma07/swapper/master/swapper > /usr/local/bin/swapper
$ chmod +x /usr/local/bin/swapper
```

## Usage

```
# create 1G swapfile
$ sudo swapper on -c 1024 /swapfile
# remove swapfile
$ sudo swapper off /swapfile
```

## Auther

shoma07
