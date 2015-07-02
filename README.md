# seedmeopenmm
The `SeedMeStateDataReporter` is an adapation of the OpenMM `StateDataReporter` such that it functions in the same way, outputting information about the simulation, but reports the information in the form of tickers in a new collection on SeedMe.
## How to use 
Perform the the SeedMe command line [setup](https://github.com/paesanilab/seedmeopenmm/blob/master/seedme.py) ...

The `SeedMeStateDataReporter` is used in the same way as the `StateDataReporter`.  Create a SeedMeStateDataReporter, then add it to the Simulation's list of reporters.  The set of data to write is configurable using boolean flags passed to the constructor.  By default the data is written in comma-separated-value (CSV) format, but you can specify a different separator to use.


