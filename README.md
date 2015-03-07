DataMining-gSpan
==============

Based on [gSpan](http://www.cs.ucsb.edu/~xyan/software/gSpan.htm) algorithm in data mining

###Features:

1. Support basic sub-structure mining.
2. Multi-thread. (200% speed-up than gSpan-64 provided by Yan)
3. Minimized memory consumption.

###Usage:

    ./gspan -file [file_name] -support [support: float] &> log
**example**
	./gspan -file test.data -support 0.2
**results**
	results will be saved in .fp file
	for example test.data.fp

###Progress:

1. MPI
2. Optimize the sequential version.
3. Detailed parallelism

12/4/2014

1. Reduce memory consumption.
2. Rearrange the gSpan class code.
3. Profling.
4. Multi-thread.
