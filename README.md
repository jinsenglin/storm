# QUICK START (local)

```
git clone -b v1.1.0 https://github.com/apache/storm.git
cd storm/examples/storm-starter
mvn clean install -DskipTests=true

# MODIFY src/jvm/org/apache/storm/starter/ExclamationTopology.java IF NEED

mvn package -DskipTests=true
storm jar target/storm-starter-1.1.0.jar org.apache.storm.starter.ExclamationTopology
```

# REFERENCE

* https://github.com/apache/storm/tree/v1.1.0/examples/storm-starter
