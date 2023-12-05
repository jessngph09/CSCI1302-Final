# IMPORTANT CODES
# compile.sh

```
#!/bin/bash -ex

mvn -q -e clean
mvn -q -e compile
```

# run.sh

```
#!/bin/bash -ex 

./compile.sh
mvn -q -e -Dprism.order=sw -Dexec.cleanupDaemonThreads=false exec:java
```
