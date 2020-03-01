---
layout: post
published: false
title: ''
---
This is one of my most recent in-class projects. It is a real-world example of a Simulation and is a very actual example of how object-oriented programming incorporates with real-world cases.

It reads in incoming data, can be thorugh a file or otherwise, and process events as they would happen in time.

In the assembly line, a partially assembled product moves along the line to different stations and parts are added at each step. Here I create a discrete event simulation of an assembly line. The simulation will involve assembling three parts to construct a finished product. The parts that are used to assemble the finished product arrive at different times to the two stations in the assembly line. The simulation will be supplied with a list of events corresponding to the arrival of the parts to the stations. The simulation will rely on a global clock that keeps track of time for the simulation.

This assembly line consists of two stations (the main station and the finishing station), each of which requires a certain amount of time to assemble two parts, as shown in the diagram below. These times for assembly will vary and will be specified in the input file. The transportation time between stations is assumed to be zero in this simulation.

This can be extended to other purposes too, because the event-driven algorithms will all follow a similar pattern.

This was written in C++ and is a very good fit for this purpose.

You can take a look at the entire code [here](https://github.com/ShahzaibP/sim.h).
