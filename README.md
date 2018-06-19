# WS-Attacker
WS-Attacker is a modular framework for web services penetration testing. It is developed by the Chair of Network and Data Security

# dependent
build from https://github.com/RUB-NDS/WS-Attacker

# build
```
cd $HOME/.m2/repository/it/cnr/imaa/essi/lablib-checkboxtree/3.3/
wget https://github.com/nroduit/mvn-repo/raw/master/it/cnr/imaa/essi/lablib-checkboxtree/3.3/lablib-checkboxtree-3.3.jar
wget https://github.com/nroduit/mvn-repo/raw/master/it/cnr/imaa/essi/lablib-checkboxtree/3.3/lablib-checkboxtree-3.3.pom
cd -
cd $HOME/.m2/repository/uk/ac/shef/wit/simmetrics/1.6.2/
wget https://dev-iesl.cs.umass.edu/nexus/content/repositories/releases/uk/ac/shef/wit/simmetrics/1.6.2/simmetrics-1.6.2.jar
wget https://repo.nds.rub.de/repository/libs/uk/ac/shef/wit/simmetrics/1.6.2/simmetrics-1.6.2.pom
cd -
mvn clean package -DskipTests -e
```

# run
```
chmod 555 run.bat
./run.bat
```

# sample
![exploit](https://github.com/hktalent/WS-Attacker/blob/master/sample.jpg?raw=true)
