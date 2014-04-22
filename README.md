Garbage-Collector
=================

The entire garbage collector is shown here. As explained, the garbage collector works by creating a new pointer type  that provides built-in support for garbage collection based on reference counting. The garbage collector is  single-threaded, which means that it is quite portable and does not rely upon (or make assumptions about) the  execution environment. This code should be stored in a file called gc.h.
