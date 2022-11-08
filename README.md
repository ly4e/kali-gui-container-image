# kali-gui-container-image
Graphical Containerized Kali instance

All credit, praise, and inspiration goes to https://github.com/qeeqbox/docker-images

This repo is just building upon their foundation with changes to allow for successful container builds to provide an updated base image of a Kali Container with a graphical interface.

## Example Usage
```bash
docker run --rm -it -p 6080:6080 ly4e/kali-gui-container-image
```