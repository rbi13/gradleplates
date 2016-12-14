# Scala Gradle template

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
# runs you scala program from the compiled classes
gradle run

# builds jar and runs inside a docker image
gradle dockerRun

# builds jar (and dumps dependencies) to build/libs, 
# then runs a docker build based on a local Dockerfile
gradle dockerBuild
# TODO: consider including default Dockerfile template in script
```
