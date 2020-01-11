# docker-argonone

Container for running the [Argon One](https://www.argon40.com/catalog/product/view/id/52/s/argon-one-raspberry-pi-4-case/) Raspberry Pi 4 case daemon.

This is useful if you are running a distro other than Raspbian and want to run the Argon One daemon.

## Usage 

To enable argononed

```
docker run --privileged -dit jmercha/argononed --name=argononed --restart=always 
```
