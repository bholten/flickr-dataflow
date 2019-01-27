# dataflow-engine
This is a simple reference example of a dataflow engine using
Clojure's core/async library. It uses the Flickr api to fetch images,
load, resize, and finally write them to disk. It does this using most
of the core features of core/async including pipeline-blocking, go
blocks, transducers, etc.

This example is taken from Timothy Baldridge @ Cognitech for a
tutorial given on core/async.

I'm saving this basically as a minimal example for my own reference.