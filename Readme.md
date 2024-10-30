
## RUN
Commands to run KOTLIN in native - GRAALVM 
```
mvn clean install

native-image.cmd --no-fallback -cp ./target/alfred-1.0-jar-with-dependencies.jar -H:Class=alfred.MainKt -o alfred 

./alfred.exe
```