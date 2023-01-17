# TIA_Portal_Template
template project structure for TIA Portal Projects managed via github

## Directory Structure:
  * .git - created by github's process
  * archives - put tia portal archives here
  * plc_src - latest work copy of project should go here. avoid multiple projects in this directory and use archives to manage versions.
  * src - source files. e.g. xml or .scl files for plc project source files, python scripts for automation, and/or C# scripts for openess integration
  
## Implements a Stack to Solve a Match Pair Grouping problem for an assembly station.
  * station recieves one of six parts:
    * a, b, c, d, e, f
  * pairs matched as follows:
    * a to b, c to d, e to f
  * ids assigned to:
    * a, c, and e
  * parts added to buffer as user receives
  * if match to last part is received:
    * operator assembles
    * id applied to assembly
    * buffer is cleared of matched pair
