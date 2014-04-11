d3-nde
======

This project implements a network diagram editor with and for the d3 visualization library.  It originates from a [discussion at the d3.unconf](http://bl.ocks.org/StewartNoyce/9962365) in SF, March 29, 2014.

### Overview

d3.nde intends to enable data-driven network diagrams, a document made of elements that are linked / indexed to real world data.  Where d3 visualizations typically expose underlying structure within collected data, a diagram conforms the data to a structure as defined by the viewer.  

### Why?

Humans add value to data, and d3 visualizations help us by providing insight into the structure of data.  Structure imposed through an editor allows application of that insight in a finished infographic or a dashboard.  This project will give a data investigator the ability to build visualizations that combine edited diagrams with algorithmically generated layout.

### How?  

For an application, create a network diagram with nodes and edges specific to its domain (e.g. biology or network management).  Give the nodes and edges unique identifiers that match those that identify data objects captured and stored in a repository.  Define a precise layout, or fix certain elements and allow automated layout of the diagram around them. 
