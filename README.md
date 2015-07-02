# seedmeopenmm
The `SeedMeStateDataReporter` is an adaptation of the OpenMM `StateDataReporter` such that it functions in the same way, outputting information about the simulation, but reports the information in the form of tickers in a new collection on SeedMe.
## How to use 
Perform the SeedMe Command Line setup (https://www.seedme.org/help/seedme-client-cli-guide/set-up)

Add `from seedmestatedataeporter import SeedMeStateDataReporter` to your OpenMM python script.

The `SeedMeStateDataReporter` is used in the same way as the `StateDataReporter`.  Create a SeedMeStateDataReporter, then add it to the Simulation's list of reporters.  The set of data to write is configurable using boolean flags passed to the constructor.  By default the data is written in comma-separated-value (CSV) format, but you can specify a different separator to use.

Link to example output (https://www.seedme.org/node/40083)
