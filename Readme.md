# My WordCount MapReduce program for Hadoop

To run:
```sh
hadoop jar target/j11sample-1.0-SNAPSHOT.jar com.armo.WordCount /input/wordcount.txt /output
```

To put input file to dfs
```sh
hdfs dfs -put input.txt /input/wordcount.txt
```

To read the results
```sh
hdfs dfs -cat /output/part-r-00000
```