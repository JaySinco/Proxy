## Introduction
A tiny proxy server written in golang, mean to be logic simple and memory efficient.

## Install
```bash
go get -u github.com/jaysinco/proxy
```

## Usage
```bash
proxy -h
Usage: proxy [protocol] [ip:port]
  current support protocol
  - http: can handle both http and https(through tunnel) connection
  - socks5
```