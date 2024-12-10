# Balld
Balld is a simple recursive build system based on bash functions.

## How to use
To use balld, simply put it to /usr/bin/ or other place in $PATH.\
Then, create a `ball` file in your project.
```bash
#!/usr/bin/bash
. /usr/bin/balld

build_state "Name" "src/name/";
build_state "Test" "src/test/";
completed_state;
```
Then, add a `build` file in every directory and write the compiler commands. Done.

