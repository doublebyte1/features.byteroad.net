# README

## Install Docker

```
./install_docker.sh
```

(open another shell)

## Install SSl Certificates

Follow [these](https://certbot.eff.org/instructions?ws=other&os=ubuntufocal) instructions to install certbot.

```
certbot certonly --standalone -d features.byteroad.net
certbot certonly --standalone -d ivaucher.byteroad.net
```

## Start the docker composition

(in the background)

```
docker-compose up -d
```