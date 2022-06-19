# Installing PostgREST on Raspberry Pi

[PostgREST](postgrest.org) is a standalone web server that turns your PostgreSQL database directly into a RESTful API. This page explains how to install it on a [Raspberry Pi](https://www.raspberrypi.org/).

## Install Raspberry OS on Raspberry Pi

Follow these [instructions](installing-raspberry-pi-os) first.

Log into the server:
`ssh user@pi`
```
sudo apt-get update
sudo apt-get upgrade -y
sudo apt-get install postgresql -y
sudo apt-get install libpq-dev -y
sudo apt-get install libnuma-dev -y
wget https://github.com/PostgREST/postgrest/releases/download/v9.0.1/postgrest-v9.0.1-ubuntu-aarch64.tar.xz
tar xJf postgrest-v9.0.1-ubuntu-aarch64.tar.xz
sudo cp postgrest /usr/local/bin
```
