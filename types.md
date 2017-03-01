---
layout: default
title: Data types in GNU Radio
---

> You can find more about the data types available in GNU Radio in the [Doxygen documentation](http://gnuradio.org/doc/doxygen/gnuradio-runtime_2include_2gnuradio_2types_8h.html). 

In GNU Radio Companion, data types are distinguished with colors on the ports:

![Port types](images/types.png)

A full list of colors is available from the menu: **Help > Types**

![Port colors](images/types-window.png)

You can only connect two ports with the same type:

![Same type ports can be connected](images/ports-connect.png)

In general, complex signals have double bandwidth compared to real signals (but also need twice as much bytes to store with the same precision):

![Complex vs Float](images/complex-vs-float-graph.png)

![Complex vs Float](images/complex-vs-float-run.png)





