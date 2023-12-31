# Blelloch scan to inclusive scan

This repository contains:
* An implementation of the Blelloch scan algorithm, accompanied by a left-shift stage designed to transform the output into an inclusive scan result.
* A novel proposal for an inclusive scan implementation using Blelloch's algorithm. This proposal introduces a rewritten second stage, delivering the inclusive scan result without the need for a separate left-shift operation. The file `inclusiveScan.cpp` contains the implementation of the algorithm for the cases of n = 2^i, while `genInclusiveScan.cpp` can handle any size of the array.

There is a separate branch for benchmarks.
