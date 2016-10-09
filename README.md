markdown-toc-docker
===================

This is a docker container containing an installation of [markdown-toc](https://github.com/jonschlinkert/markdown-toc#cli).

It's purpose is to provide a convenient way to use markdown-toc without having
to install node.js or npm.

Basic Usage
-----------

Run markdown-toc on `./README.md`, replacing `<!-- toc -->` with a table of contents:

    $ docker run -v `pwd`:/src quay.io/getpantheon/markdown-toc -i /src/README.md


