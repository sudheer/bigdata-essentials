### Hadoop
- RDBMS VS Hadoop
- Explain how hadoop is different from other tools ?
- What are the different modes of hadoop can run ?

### HDFS

- Best way to copy files between HDFS clusters ?
- Explain the process of DistCp in Hadoop ?

### MapReduce
- Explain how mapreduce works ?
- What are the jobs of Jobtracker ?
- How a job is executed in mapreduce ?
- What is speculative execution ?
- What is the use of combiners and when do you use ?
- What is partitioner in mapreduce ?
- How do you write a custom partitioner ?
- What is InputSplit in mapreduce ?
- InputSplit vs Block in MR ?
- Explain how JobTracker schedules a task ?
- What is sequence file input format ?
- Explain what is a sequence file in hadoop ?
- What are different input formats in hadoop and when do you use them ?
- What are the most common input formats you have used ?
- List out few of mapreduce configuration files ?
- Which file controls reporting in hadoop ?
- What daemons run on master nodes in hadoop ?
- What daemons run on slave nodes in hadoop ?
- What is the use of a context object ?
- What will text input format class do in MR ?
- Explain about distributed cache in MapReduce ?
- How many times a map method is called in mapreduce ?
- How many times a reduce method is called for each task ?
- How many times a setup method is called in a mapper ?
- How many times a cleanup method is called in a reducer ?
- Explain about shuffle and sort phase in mapreduce ?
- What is the sorting alogirthm used in shuffle and sort phase ?
- How do you sort a Huge file using MapReduce program ?
- How many times a combiner is called in mapreduce program ?
- What is the criteria for using a combiner in a mapreduce program ?
- What is a mapside join ? How it is done ?
- What is a reduce side join ? How it is done ?
- What are the performance tuning you have done in a mapreduce program ?

### Sqoop
- target-dir vs warehouse-dir in sqoop ?
- How to import subset of rows into HDFS ?
- How do you compress sqoop output file ?
- How to control parallelism in sqoop ?
- What is sqoop metastore ?
- What are the different output data formats you can import data into HDFS ?
- How to control mapping between sql data types and java data types ?
- How do you group records in DB's that are read by mappers in sqoop ?
- How to run a sqoop job using oozie ?
- How to import data which is result of join of 2 tables in sqoop ?
- How to avoid giving password on the command line in sqoop ?
- Does sqoop1 have a reduce phase ?

### Hive

- How Hive is different from RDBMS ?
- When do you use hive vs pig ?
- How many different ways you can connect to Hive ?
- What is the importance of Hive Server ?
- What is hive metastore ?
- Hive CLI vs Beeline ?
- Different ways of executing hive ?
- Difference between managed and external table ?
- what is default location where hive stores data ?
- What are the different modes hive can be run ?
- Explain about complex data types in Hive ?
- What is partitioning and why do we use it ?
- What is bucketing and why do we use it ?
- How bucketing is different from partitioning ?
- What is Serde and why it is used ?
- Why is InputFormat used in Hive ?
- What is the difference in role of Serde and Inputformat ?
- Sort by vs Order by in Hive ?
- How many reducers are executed when you execute order by in hive ?
- Is the total data file sorted if you use sort by ?
- How to sort an entire data file using Hive ?
- How do you write an UDF in hive ?
- How to add an UDF to classpath ?
- How to add Hive UDf to oozie classpath ?
- UDF vs UDAF vs UDTF ?
- What is map join in hive ?
- Can we load data into a view in Hive ?
- Can we index hive tables ?
- What is Hcatalog and why do you use it in Hive ?
- How can you connect to hive from Sql IDE's ?
- Explain about locks on Hive tables ? When Shared vs Exclusive locks takes place ?

### Pig

- Pig vs MR vs Hive. when do you use them ?
- Modes of execution in pig ?
- Complex data types in pig ?
- Tuple vs Bag ?
- Explain about foreach in piglatin ?
- Group vs CoGroup ?
- What does FLATTEN do ?
- How do you write a UDF ?
- How to do a map join in pig ?
- How to add UDF jar to classpath in pig ?
- Different ways of executing pig ?
- How to execute pig from oozie ?

### Spark

- Why spark faster than mapreduce ?
- What does spark ecosystem consists of ?
- Explain about different types of cluster managers in spark ?
- What is an RDD ?
- What is a PairRDD ?
- How do you define spark context ?
- Different ways of configuring spark properties to the job ?
- Is it possible to have multiple spark context inside single JVM ?
- can RDD be shared betweeen spark context ?
- Scheduler used by spark context by default ?
- How do you change memory allocated to executor ?
- How to control number of partitions in an RDD ?
- Narrow transformations vs Wide transformations in spark ?
- How can you distribute jars to workers in spark ?
- Explain about transformations and actions ?
- Various Storage/persistance levels in spark ?
- Need for broadcast variables ?
- What are accumulators and why do we use them ?
- Difference between persist() and cache() ?
- GroupByKey vs ReduceByKey ?
- What is meant by CheckPointing ?
- Explain about spark streaming ?
- What is a DStream ?
- What are different transformations on DStreams ?
- Explain about stateful operations in spark streaming ?
- What is catalyst optimizer ?
- What are datasets in spark ?
- Explain window functions in Spark SQL ?
- Explain about DataFrames used in spark ?
- How do you write unit tests for spark ?
- How do you sort the data in spark ?

### Hbase

- Why Hbase faster than hdfs ?
- What are key components of hbase ?
- What is the role of ZooKeeper in hbase ?
- Explain the master-slave architecture of hbase ?
- Different types of filters used in Hbase ?
- Explains steps of file write from Client to Hbase ?
- What are different compactions in Hbase ? Explain ?
- What is TTL in Hbase ?
- What is a HFile & memstore ?
- Does Hbase support table joins ?
- What are rowkey, column family, column qualifier, cell, version in hbase ?
- Different ways of accessing data from Hbase ?
- Explain different block cache in hbase ?
- How do you prevent hotspotting in hbase ?
- What is namespace in hbase ?
- Explain operational commands in hbase like scan, put etc ?
- WAL in hbase ?
- Hbase vs RDBMS ?
- How to execute sql on top of hbase ?
- Should the region servers be run on same nodes as datanodes ?
- How to access a disabled table using Hbase Scan ?
- How can you run MapReduce on top of data in Hbase ?
- Can you create a Hive table on data in Hbase ?
- Can you sqoop directly into Hbase from RDBMS ?

### Cassandra

- How cassandra stores data ?
- What is column family in cassandra ?
- Explain about keyspace ?
- How do you compare Cassandra VS Hbase ?
- What are different composite keys in cassandra ?
- Explain about consistentcy in cassandra ?
- What is the use of memtable ?
- How does cassandra delete data ?
- What is the role of thrift in cassandra cluster ?
- What are secondary indexes ?
- How High Availability is achieved in cassandra ?
- What happens if you update a deleted record ?

### Kafka

- What is difference between Kafka and RabbitMQ ?
- How kafka is different from Flume ?
- Benefits of kafka over traditional messaging services ?
- Explain about various components of kafka ?
- Explain about offset and its significance in kafka ?
- What is a consumer group ?
- What is the zookepers role in kafka ?
- Is it possible to use kafka without zookeeper ?
- What is broker in kafka ?
- Max size of message kafka server can receive ?
- What is partition key ?

### Storm

- Why apache storm is used ?
- Explain how data flows in storm ?
- Difference between apache storm and apache kafka ?
- components of storm ?
- topology in storm ?

<<<<<<< HEAD
<<<<<<< HEAD:interview-questions/hadoop.md
=======
### Core Java

- Why Java is statically typed language ?
- Difference between JRE, JDK and JVM ?
- Explain about classloaders ?
- Difference between Path and Classpath ?
- Does constructor return anything in Java ?
- can a constructor be final ?
- Can you use super() and this() in a constructor ?
- Where and how we use a private constructor ?
- Why main method is static ?
- Explain about static block ?
- Shallow copy vs Deep copy ?
- Explain about object cloning ?
- Can you overload main method ?
- Can you override a static method ?
- Can we reduce the visibility of the inherited or overridden method ?
- How can you initialize a blank final variable ?
- Static binding vs Dynamic binding ?
- Can an interface be final ?
- Do you need to import java.lang package ?
- Explain about static imports ?
- Can you access Non Static variable in a static context ?
- Can we override static methods ?
- What is the difference between inner class and nested class?
- Why do we implement inner classes where we can work with outer classes ?
- Checked vs Unchecked exceptions ?
- Base class for Error and Exception ?
- Difference between throw and throws ?
- Difference between ClassNotFoundException & NoClassDefFoundError ?
- Why String is immutable in Java ?
- Why String class is made final in Java ?
- Does Declaring an object "final" makes it immutable ?
- Difference between creating string in new() vs String literal ?
- StringBuilder vs StringBuffer ?
- Why do we use toString() in java ?
- Why 1000 == 1000 Returns False, but 100 == 100 Returns True in Java?
- What's the difference between "a == b" and "a.equals(b)"?
- Can two equal object have the different hash code?
- Can a class have an interface with in it ?
- Can a class declared as private be accessed outside it's package?
- Explain about garbage collection in java ?
- Does garbage collection guarantee that a program will not run out of memory?
- What is the purpose of finalize() method ?
- What is Serialization and DeSerialization ?
- Explain about transient keyword ?
- What is Reflection and why do we use it ?
- Can we access private method from outside a class ?
- What is a native method ?
- Explain about singleton class ?
- What is a JavaBean and purpose of it ?
- What is synchronization in threading ?
- Why do you use a volatile keyword ?
- Difference between ArrayList and LinkedList ?
- What are the couple of ways that you could sort a collection?
- How HashSet works internally in Java? 
- What will happen if you place a key in hashcode if its already there ?
- Comparable vs Comparator ?
- Can we override compareTo method for Enumerations ?
- Why Enums cannot be declared final ?
- Explain the improtance of equals and hashcode ?
- Statement vs PreparedStatement in JDBC ?
- What is the use of DriverManager class in JDBC ?
- What is a database deadlock ? How can we avoid it ?
- Explain about lambda expressions ?
- What are the new features of Java8 ?
- What is RMI ?

### Data Warehousing

- what are Facts and Dimensions ?
- Explain about why a surrogate key is used ?
- What are Slowly Changing Dimensions ?

