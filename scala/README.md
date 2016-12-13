# Scala gradle template

Inputs
```groovy
// (build.gradle)
version = 0.0.0 // software version
mainClass = io.rbi.tmpl8.Main //class with main function or 'extends App' (see Scala getting started)
...
```

Commands
```sh
# shell
gradle run # runs you scala program from the compiled classes
# OR
gradle runDocker # builds jar and runs inside a scala docker container
# NOTE: runDocker needs to be modified to include class path (dependencies)
```
