# containerd-c
An open container runtime similar to containerd written by c.

An experimental and full of bugs implementation of the containerd
(https://github.com/containerd/containerd) in C language, run at your own
risk.

It's just a personal project, just for fun.

Why another implementation?
==========

While most of the tools used in the Linux containers ecosystem are
written in Go (runc\containerd\docker and so on), but i believe C 
is a better fit for such a lower level tool.

Containerd-c aims to implement all the functions like containerd,
and provides similar grpc interfaces.

BUILD
==========

```
$ ./autogen.sh && ./configure
$ make

```
