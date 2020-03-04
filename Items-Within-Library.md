## Items Within Library
The NPSS Power Systems Library contains contains a set of power system and circuit components, a set of fundamental tools and classes designed to enable creating and analyzing power system models, and a suite of example models using the library tools. Refer to the following sections of this documentation for more information about these items:
* [Fundamental Classes and Components](Fundamental-Classes-and-Components)
* [Power System Components](Power-System-Components)
* [Examples](Examples)

## File Structure
The file structure of the library is as follows
* include
    * Files to be included, such as performance maps, design scaler initial guesses, etc
* model
    * NPSS model definition files to be used with the examples
* output
    * Folder where viewer output and comma separated value (CSV) files are written by the examples
* run
    * Example model entry points, each representing a study performed on a given model
* src
    * Source code for power system, circuit, thermal management, and other components
* utils
    * Various NPSS and Python software utilities, including printing and plotting functions
* view
    * NPSS viewer source files, with features designed for the power system components in this library
