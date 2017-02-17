[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/hola_nicholas.svg)](https://hub.docker.com/r/rubygem/hola_nicholas/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/hola_nicholas.svg)](https://hub.docker.com/r/rubygem/hola_nicholas/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/hola_nicholas.svg)](https://hub.docker.com/r/rubygem/hola_nicholas/)
[![Gem Downloads](https://img.shields.io/gem/dt/hola_nicholas.svg)](https://rubygems.org/gems/hola_nicholas/)
# hola_nicholas

Auto-Generated Docker image for hola_nicholas to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/hola_nicholas`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/hola_nicholas`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/hola_nicholas`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/hola_nicholas/)
