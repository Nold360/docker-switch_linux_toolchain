### Nintendo Switch - Linux Toolchain 
In a Docker container

This Container can be used as base-image for other project, or to compile linux sourcecode on the host.

### Usage
Run docker in your sourcecode-directory like this:
```
docker run -ti --rm -v $(pwd):/source nold360/switch_linux_toolchain bash
```
