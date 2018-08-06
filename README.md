# flinkTest1

## Step 1.

  run org.univalle.parser.Sparql2Flink. This will generate the org.univalle.flink.Query.java file.

## Step 2.

  mvn clean compile package
  
# Step 3. 
  Submit new Job in Apache Flink JobManager. If you want to see the example output add the parameter ''--output queryout.txt''
  Then, you can find the file inside the JobManager host at  /opt/flink/queryout.txt
