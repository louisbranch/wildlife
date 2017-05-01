# Wildlife Care

## Setup

Install [go](https://golang.org/doc/install)

### Proxy

    go get github.com/mholt/caddy/caddy
    go install github.com/mholt/caddy/caddy
    sudo setcap 'cap_net_bind_service=+ep' $GOPATH/bin/caddy

Enable localhost https on Chrome:

    chrome://flags/#allow-insecure-localhost

## Run

    make

Access [https://localhost](https://localhost)
