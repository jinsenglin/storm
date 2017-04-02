# QUICK START (local)

```
http://apache.stu.edu.tw/storm/apache-storm-1.1.0/apache-storm-1.1.0.tar.gz
tar -zxf apache-storm-1.1.0.tar.gz

git clone -b v1.1.0 https://github.com/apache/storm.git
cd storm/examples/storm-starter
mvn clean install -DskipTests=true

# MODIFY src/jvm/org/apache/storm/starter/ExclamationTopology.java IF NEED
# e.g., change topology name from 'test' to 'orz'

mvn package -DskipTests=true
../../../apache-storm-1.1.0/bin/storm jar target/storm-starter-1.1.0.jar org.apache.storm.starter.ExclamationTopology
```

# REFERENCE

* https://github.com/apache/storm/tree/v1.1.0/examples/storm-starter
