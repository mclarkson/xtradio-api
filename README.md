# xtradio-api

[![Docker Repository on Quay](https://quay.io/repository/xtradio/xtradio-api/status "Docker Repository on Quay")](https://quay.io/repository/xtradio/xtradio-api)

XTRadio JSON Api to retrieve currently playing song
## Build instructions

Build using :
``` CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -o bin/xtradio-api . ```

## Golang tutorials

The following tutorials helped us build our code, we've started with no prior knowledge of golang, maybe they will be helpfull for others as well.

* [Creating restful API with golang](https://tutorialedge.net/post/golang/creating-restful-api-with-golang/)
