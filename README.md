<h> Requirements </h>

- CMAKE 3.0
- gcc-8 g++-8
- Supporting g++-7: Add the following lines after line 1 of CMakeLists.txt
  - `set(CMAKE_C_COMPILER "gcc-7")`
  - `set(CMAKE_CXX_COMPILER "g++-7")`

<h> How to run </h>

- `mkdir build`
- `cd build`
- `cmake ..`
- `make`

<h> Test run </h>

- `./RelComp -i test_graph.txt -d ./ -s test_sourcetarget.txt -m 2`
