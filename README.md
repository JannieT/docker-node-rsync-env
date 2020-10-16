# docker-node-rsync-env

Deploy pipe container with:

* node js (via the [official node container](https://hub.docker.com/_/node/) to build web assets)
* envsubst (via gettext to replace environment secrets)
* rsync (to deliver built assets)
