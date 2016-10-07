Python on Tiny Core Linux
=========================

This provides a small but a fully functional [Python](https://www.python.org/) runtime environment. This image is based on [Tiny Core Linux Docker image](https://hub.docker.com/r/aksaramaya/tc).

## Supported tags and respective `Dockerfile` links

- [`2.7` (2.7/Dockerfile)](https://github.com/aksaramaya/docker-tc-python/blob/master/2.7/Dockerfile)
- [`2.7-onbuild` (2.7/onbuild/Dockerfile)](https://github.com/aksaramaya/docker-tc-python/blob/master/2.7/onbuild/Dockerfile)
- [`3.4` (3.4/Dockerfile)](https://github.com/aksaramaya/docker-tc-python/blob/master/3.4/Dockerfile)
- [`3.4-onbuild` (3.4/onbuild/Dockerfile)](https://github.com/aksaramaya/docker-tc-python/blob/master/3.4/onbuild/Dockerfile)
- [`3.5`, `latest` (3.5/Dockerfile)][Latest Dockerfile]
- [`3.5-onbuild` (3.5/onbuild/Dockerfile)](https://github.com/aksaramaya/docker-tc-python/blob/master/3.5/onbuild/Dockerfile)

## How to use this image

This can be used in the same way as [Official Python Image](https://hub.docker.com/_/python/). Please see "How to use this image" section of it with replacing the image name with this one.

## How to install C extension etc.

This doesn't contain a compiler, a linker and headers etc. so if you'd like to add a something C extension for Python, first you need to install them by `tce-load` command. Please refer this image's [Dockerfile][Latest Dockerfile] which is a good example of installing those packages.
