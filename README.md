# docker-gcl - a Docker container having Common Lisp (GCL)

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-gcl/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-gcl:latest gcl --version
GCL (GNU Common Lisp)  2.6.10 CLtL1    Apr  2 2014 14:22:53
Source License: LGPL(gcl,gmp), GPL(unexec,bfd,xgcl)
Binary License:  GPL due to GPL'ed components: (XGCL READLINE UNEXEC)
Modifications of this banner must retain notice of a compatible license
Dedicated to the memory of W. Schelter

Use (help) to get some basic information on how to use GCL.
Temporary directory for compiler files set to /tmp/

>
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
* [editorconfig-cli](https://github.com/amyboyd/editorconfig-cli) (e.g. `go get github.com/amyboyd/editorconfig-cli`)
* [flcl](https://github.com/mcandre/flcl) (e.g. `go get github.com/mcandre/flcl/...`)
