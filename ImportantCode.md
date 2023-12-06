# IMPORTANT CODES
# compile.sh

```
#!/bin/bash -ex

mvn -q -e clean
mvn -q -e compile
```
```
javac -d bin -p $JAVAFX_HOME/lib --add-modules javafx.controls src/main/java/cs1302/api/PokemonBattleSimulator.java
```
# run.sh

```
#!/bin/bash -ex 

./compile.sh
mvn -q -e -Dprism.order=sw -Dexec.cleanupDaemonThreads=false exec:java
```
```
java -cp bin -Dprism.order=sw -p $JAVAFX_HOME/lib --add-modules javafx.controls cs1302.api.PokemonBattleSimulator
```
