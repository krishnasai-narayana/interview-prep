# Hadoop
+ [What are the main components of a Hadoop Application?](#What-are-the-main-components-of-a-Hadoop-Application)
+ [What is the core concept behind Apache Hadoop framework?](#What-is-the-core-concept-behind-Apache-Hadoop-framework)
+ [What is Hadoop Streaming?](#What-is-Hadoop-Streaming)
+ [What is BigQuery, and how does it fit into the data engineering ecosystem?](#What-is-BigQuery-and-how-does-it-fit-into-the-data-engineering-ecosystem)
+ [How does BigQuery handle data storage and processing?](#How-does-BigQuery-handle-data-storage-and-processing)
+ [What are the key advantages of using BigQuery?](What-are-the-key-advantages-of-using-BigQuery)
+ [What are the default port numbers on which  Nodes run in Hadoop?](#What-are-the-default-port-numbers-on-which-Nodes-run-in-Hadoop)
+ [How will you disable a Block Scanner on HDFS DataNode?](#How-will-you-disable-a-Block-Scanner-on-HDFS-DataNode)
+ [How will you get the distance between two nodes in Apache Hadoop?](#How-will-you-get-the-distance-between-two-nodes-in-Apache-Hadoop)
+ [Why do we use commodity hardware in Hadoop?](#Why-do-we-use-commodity-hardware-in-Hadoop)
+ [How does inter cluster data copying works in Hadoop?](#How-does-inter-cluster-data-copying-works-in-Hadoop)
+ [How can we update a file at an arbitrary location in HDFS?](#How-can-we-update-a-file-at-an-arbitrary-location-in-HDFS)
+ [What is Replication factor in HDFS?](#What-is-Replication-factor-in-HDFS)
+ [What is the difference between NAS and DAS in Hadoop cluster?](#What-is-the-difference-between-NAS-and-DAS-in-Hadoop-cluster)
+ [What are the two messages that NameNode receives from DataNode?](#What-are-the-two-messages-that-NameNode-receives-from-DataNode)
+ [How does indexing work in Hadoop?](#How-does-indexing-work-in-Hadoop)
+ [What data is stored in a HDFS NameNode?](#What-data-is-stored-in-a-HDFS-NameNode)
+ [What would happen if NameNode crashes in a HDFS cluster?](#What-would-happen-if-NameNode-crashes-in-a-HDFS-cluster)
+ [What are the main functions of Secondary NameNode?](#What-are-the-main-functions-of-Secondary-NameNode)
+ [What happens if HDFS file is set with replication factor of 1 and DataNode crashes?](#What-happens-if-HDFS-file-is-set-with-replication-factor-of-1-and-DataNode-crashes)
+ [What is the meaning of Rack Awareness in Hadoop?](#What-is-the-meaning-of-Rack-Awareness-in-Hadoop)
+ [How will you check if a file exists in HDFS?](#How-will-you-check-if-a-file-exists-in-HDFS)
+ [Why do we use fsck command in HDFS?](#Why-do-we-use-fsck-command-in-HDFS)
+ [What will happen when NameNode is down and a user submits a new job?](#What-will-happen-when-NameNode-is-down-and-a-user-submits-a-new-job)
+ [What are the core methods of a Reducer in Hadoop?](#What-are-the-core-methods-of-a-Reducer-in-Hadoop)
+ [What are the primary phases of a Reducer in Hadoop?](#What-are-the-primary-phases-of-a-Reducer-in-Hadoop)
+ [What is the use of Context object in Hadoop?](#What-is-the-use-of-Context-object-in-Hadoop)
+ [How does partitioning work in Hadoop?](#How-does-partitioning-work-in-Hadoop)
+ [What is a Combiner in Hadoop?](#What-is-a-Combiner-in-Hadoop)
+ [What is the default replication factor in HDFS?](#What-is-the-default-replication-factor-in-HDFS)
+ [How much storage is allocated by HDFS for storing a file of 25 MB size?](#How-much-storage-is-allocated-by-HDFS-for-storing-a-file-of-25-MB-size)
+ [Why does HDFS store data in Block structure?](#Why-does-HDFS-store-data-in-Block-structure)
+ [How will you create a custom Partitioner in a Hadoop job?](#How-will-you-create-a-custom-Partitioner-in-a-Hadoop-job)
+ [What is a Checkpoint node in HDFS?](#What-is-a-Checkpoint-node-in-HDFS)
+ [What is a Backup Node in HDFS?](#What-is-a-Backup-Node-in-HDFS)
+ [What is the meaning of term Data Locality in Hadoop?](#What-is-the-meaning-of-term-Data-Locality-in-Hadoop)
+ [What is a Balancer in HDFS?](#What-is-a-Balancer-in-HDFS)
+ [What are the important points a NameNode considers before selecting the DataNode for placing a data block?](#What-are-the-important-points-a-NameNode-considers-before-selecting-the-DataNode-for-placing-a-data-block)
+ [How will you replace HDFS data volume before shutting down a DataNode?](#How-will-you-replace-HDFS-data-volume-before-shutting-down-a-DataNode)
+ [What are the important configuration files in Hadoop?](#What-are-the-important-configuration-files-in-Hadoop)
+ [How will you monitor memory used in a Hadoop cluster?](#How-will-you-monitor-memory-used-in-a-Hadoop-cluster)
+ [Why do we need Serialization in Hadoop map reduce methods?](#Why-do-we-need-Serialization-in-Hadoop-map-reduce-methods)
+ [What is the use of Distributed Cache in Hadoop?](#What-is-the-use-of-Distributed-Cache-in-Hadoop)
+ [How will you synchronize the changes made to a file in Distributed Cache in Hadoop?](#How-will-you-synchronize-the-changes-made-to-a-file-in-Distributed-Cache-in-Hadoop)
+ [Can you elaborate about Mapreduce Job](#Can-you-elaborate-about-Mapreduce-job)
+ [Why compute nodes and the storage nodes are the same?](#Why-compute-nodes-and-the-storage-nodes-are-the-same)
+ [What is the configuration object importance in Mapreduce?](#What-is-the-configuration-object-importance-in-Mapreduce)
+ [Where Mapreduce not recommended?](#Where-Mapreduce-not-recommended?)
+ [What is Namenode and it’s responsibilities?](#What-is-Namenode-and-it’s-responsibilities)
+ [What is Jobtracker’s responsibility?](#What-is-Jobtracker’s-responsibility)
+ [What are the Jobtracker and Tasktracker?](#What-are-the-Jobtracker-and-Tasktracker)
+ [What is Job scheduling importance in Hadoop Mapreduce?](#What-is-Job-scheduling-importance-in-Hadoop-Mapreduce)
+ [When used Reducer?](#When-used-Reducer)
+ [Where the Shuffle and Sort process does?](#Where-the-Shuffle-and-Sort-process-does)
+ [Java is mandatory to write Mapreduce Jobs?](#Java-is-mandatory-to-write-Mapreduce-Jobs)
+ [What methods can controle the Map And Reduce function’s output?](#What-methods-can-controle-the-Map-And-Reduce-function’s-output)
+ [What is the main difference between Mapper And Reducer?](#What-is-the-main-difference-between-Mapper-And-Reducer)
+ [Why compute Nodes and the Storage Nodes are same?](#Why-compute-Nodes-and-the-Storage-Nodes-are-same?)
+ [What is difference between mapside join and reduce side join?](#What-is-difference-between-mapside-join-and-reduce-side-join)
+ [What happen if number of Reducer is 0?](#What-happen-if-number-of-Reducer-is-0)
+ [When we are goes to Combiner? Why it is Recommendable?](#When-we-are-goes-to-Combiner)
+ [What is the main difference between Mapreduce Combiner and Reducer?](#What-is-the-main-difference-between-Mapreduce-Combiner-and-Reducer)
+ [What Is Partition?](#What-is-partition)
+ [When we goes to Partition?](#When-we-goes-to-Partition)
+ [What are the important steps when you are partitioning table?](#What-are-the-important-steps-when-you-are-partitioning-table)
+ [Can you elaborate Mapreduce Job architecture?](#Can-you-elaborate-Mapreduce-Job-architecture)
+ [Why task Tracker launch child Jvm?](#Why-task-Tracker-launch-child-Jvm)
+ [Why JobClient and Job Tracker submits job resources to file system?](#Why-Jobclient-and-Job-Tracker-submits-job-resources-to-file-system)
+ [How many Mappers and Reducers can run?](#How-many-Mappers-and-Reducers-can-run)
+ [What is InputSplit?](#What-is-Inputsplit)
+ [How to configure the split value?](#How-to-configure-the-split-value)
+ [How much ram required to process 64mb data?](#How-much-ram-required-to-process-64mb-data)
+ [What is difference between block And split?](#What-is-difference-between-block-And-split)
+ [Why Hadoop Framework reads a file parallel why not sequential?](#Why-Hadoop-Framework-reads-a-file-parallel-why-not-sequential)
+ [If I am change block size from 64 to 128?](#If-I-am-change-block-size-from-64-to-128)
+ [What is IsSplitable()?](#What-is-Issplitable())
+ [How much Hadoop allows maximum block size and minimum block size?](#How-much-Hadoop-allows-maximum-block-size-and-minimum-block-size)
+ [What are the Job Resource files?](#What-are-the-Job-Resource-files)
+ [What’s the Mapreduce Job consists?](#What’s-the-Mapreduce-Job-consists)
+ [What is the data locality?](#What-is-the-data-locality)
+ [What is speculative execution?](#What-is-speculative-execution)
+ [What is chain Mapper?](#What-is-chain-Mapper)
+ [How to do value level comparison?](#How-to-do-value-level-comparison)
+ [What is setup and clean up methods?](#What-is-setup-and-clean-up-methods)
+ [How many slots allocate for each task?](#How-many-slots-allocate-for-each-task)
+ [Why TaskTracker launch child Jvm to do a task? Why not use Existent Jvm?](#Why-Tasktracker-launch-child-Jvm-to-do-a-task)
+ [What main configuration parameters are specified in Mapreduce?](#What-main-configuration-parameters-are-specified-in-Mapreduce)
+ [What is identity Mapper?](#What-is-identity-Mapper)
+ [What is RecordReader in a MapReduce?](#What-is-RecordReader-in-a-MapReduce)
+ [What is OutputCommitter?](#What-is-OutputCommitter)
+ [What are the parameters of Mappers and Reducers?](#What-are-the-parameters-of-Mappers-and-Reducers)
+ [Explain JobConf in Mapreduce?](#Explain-Jobconf-in-Mapreduce)
+ [Explain Job scheduling through Jobtracker?](#Explain-Job-scheduling-through-Jobtracker)
+ [What is SequenceFileInputFormat?](#What-is-SequenceFileInputFormat)
+ [Explain how input and output data format of the Hadoop Framework?](#Explain-how-input-and-output-data-format-of-the-Hadoop-Framework)
+ [What are the restriction to the Key and Value Class ?](#What-are-the-restriction-to-the-Key-and-Value-Class)
+ [Explain the wordcount implementation via Hadoop Framework?](#Explain-the-wordcount-implementation-via-Hadoop-Framework)
+ [How Mapper is instantiated in a running Job?](#How-Mapper-is-instantiated-in-a-running-Job)
+ [Which are the methods in the Mapper Interface?](#Which-are-the-methods-in-the-Mapper-Interface)
+ [What happens if You don't Override the Mapper methods and keep them as it is?](#What-happens-if-You-don't-Override-the-Mapper-methods-and-keep-them-as-it-is)
+ [What is the use of context Object?](#What-is-the-use-of-context-Object)
+ [How can you Add the arbitrary Key-value pairs in your Mapper?](#How-can-you-Add-the-arbitrary-Key-value-pairs-in-your-Mapper)
+ [How Does Mapper's Run() Method Works?](#How-does-Mapper's-run-method-works)
+ [Which Object can be used to get the progress of a particular Job?](#Which-Object-can-be-used-to-get-the-progress-of-a-particular-Job)
+ [What is next step after Mapper Or Maptask?](#What-is-next-step-after-Mapper-Or-Maptask)
+ [How can we control particular Key should go in a specific Reducer?](#How-can-we-control-particular-Key-should-go-in-a-specific-Reducer)
+ [What is the use of Combiner?](#What-is-the-use-of-Combiner)
+ [How many Maps are there in a particular Job?](#How-many-Maps-are-there-in-a-particular-Job)
+ [What is the Reducer used for?](#What-is-the-Reducer-used-for)
+ [Explain the core methods of the Reducer?](#Explain-the-core-methods-of-the-Reducer)
+ [What are the primary phases of the Reducer?](#What-are-the-primary-phases-of-the-Reducer)
+ [Explain the Shuffle?](#Explain-the-Shuffle)
+ [Explain the Reducer's sort phase?](#Explain-the-Reducer's-sort-phase)
+ [Explain the Reducer's reduce phase?](#Explain-the-Reducer's-reduce-phase)
+ [How many Reducers should be configured?](#How-many-Reducers-should-be-configured)
+ [It can be possible that a Job has 0 Reducers?](#It-can-be-possible-that-a-Job-has-0-Reducers)
+ [What happens if number of Reducers are 0?](#What-happens-if-number-of-Reducers-are-0)
+ [How many instances of Jobtracker can run on a Hadoop Cluster?](#How-many-instances-of-Jobtracker-can-run-on-a-Hadoop-Cluster)
+ [What is the Jobtracker and what it performs in a Hadoop Cluster?](#What-is-the-Jobtracker-and-what-it-performs-in-a-Hadoop-Cluster)
+ [How a task is scheduled by a Jobtracker?](#How-a-task-is-scheduled-by-a-Jobtracker)
+ [How many instances of Tasktracker run on a Hadoop Cluster?](#How-many-instances-of-Tasktracker-run-on-a-Hadoop-Cluster)
+ [How many maximum Jvm can run on a Slave Node?](#How-many-maximum-Jvm-can-run-on-a-Slave-Node)
+ [What is Nas?](#What-is-Nas)
+ [How Hdfs differs with Nfs?](#How-Hdfs-differs-with-Nfs)
+ [How does a NameNode handle the failure of the Data Nodes?](#How-does-a-NameNode-handle-the-failure-of-the-Data-Nodes)
+ [Can Reducer talk with each other?](#Can-Reducer-talk-with-each-other)
+ [Where the Mapper's intermediate data will be stored?](#Where-the-Mapper's-intermediate-data-will-be-stored)
+ [What is the Hadoop Mapreduce api contract for a Key and Value Class?](#What-is-the-Hadoop-Mapreduce-api-contract-for-a-Key-and-Value-Class)
+ [What is a IdentityMapper and IdentityReducer in Mapreduce?](#What-is-a-IdentityMapper-and-IdentityReducer-in-Mapreduce)
+ [What is the meaning of Speculative Execution in Hadoop?](#What-is-the-meaning-of-Speculative-Execution-in-Hadoop)
+ [How Hdfs is different from traditional File Systems?](#How-Hdfs-is-different-from-traditional-File-Systems)
+ [What is Hdfs block size and how is it different from Traditional File System block size?](#What-is-Hdfs-block-size-and-how-is-it-different-from-Traditional-File-System-block-size)
+ [What is a NameNode and how many instances of NameNode run on a Hadoop Cluster?](#What-is-a-NameNode-and-how-many-instances-of-NameNode-run-on-a-Hadoop-Cluster)
+ [How the client communicates with Hdfs?](#How-the-client-communicates-with-Hdfs)
+ [How the Hdfs blocks are replicated?](#How-the-Hdfs-blocks-are-replicated)
+ [Can you give some examples of Big Data?](#Can-you-give-some-examples-of-Big-Data)
+ [What is the basic difference between traditional Rdbms and Hadoop?](#What-is-the-basic-difference-between-traditional-Rdbms-and-Hadoop)
+ [What is structured and unstructured Data?](#What-is-structured-and-unstructured-Data)
+ [Since the data is replicated thrice in Hdfs so does it mean that any calculation done on One Node will also be replicated on the other Two?](#Since-the-data-is-replicated-thrice-in-Hdfs-so-does-it-mean-that-any-calculation-done-on-One-Node-will-also-be-replicated-on-the-other-Two)
+ [What is throughput and how does Hdfs get a good throughput?](#What-is-throughput-and-how-does-Hdfs-get-a-good-throughput)
+ [What is streaming access?](#What-is-streaming-access)
+ [What is a Commodity Hardware so does Commodity Hardware include Ram?](#What-is-a-Commodity-Hardware-so-does-Commodity-Hardware-include-Ram)
+ [Is NameNode also a Commodity?](#Is-NameNode-also-a-Commodity)
+ [What is a Metadata?](#What-is-a-Metadata?)
+ [What is a Daemon?](#What-is-a-Daemon)
+ [What is a Heartbeat in Hdfs?](#What-is-a-Heartbeat-in-Hdfs)
+ [How indexing is done in Hdfs?](#How-indexing-is-done-in-Hdfs)
+ [If a Data Node is full how it's identified?](#If-a-Data-Node-is-full-how-it's-identified)
+ [If DataNodes increase then do we need to upgrade NameNode?](#If-DataNodes-increase-then-do-we-need-to-upgrade-NameNode)
+ [Are Job Tracker and Task Trackers present in separate machines?](#Are-Job-Tracker-and-Task-Trackers-present-in-separate-machines)
+ [On what basis NameNode will decide which DataNode to write on?](#On-what-basis-NameNode-will-decide-which-DataNode-to-write-on)
+ [Who is a user in Hdfs?](#Who-is-a-user-in-Hdfs)
+ [Is client the end user in Hdfs?](#Is-client-the-end-user-in-Hdfs)
+ [What is the Communication Channel between client and NameNode/DataNode?](#What-is-the-Communication-Channel-between-client-and-NameNode/DataNode)
+ [What is a Rack?](#What-is-a-Rack)
+ [On what basis Data will be stored on a Rack?](#On-what-basis-Data-will-be-stored-on-a-Rack)
+ [Do we need to place 2nd and 3rd Data in Rack 2 only?](#Do-we-need-to-place-2nd-and-3rd-Data-in-Rack-2-only)
+ [What if Rack 2 and DataNode fails?](#What-if-Rack-2-and-DataNode-fails)
+ [What is the difference between Gen1 and Gen2 Hadoop with regards to the NameNode?](#What-is-the-difference-between-Gen1-and-Gen2-Hadoop-with-regards-to-the-NameNode)
+ [Do we require two servers for the NameNode and the DataNodes?](#Do-we-require-two-servers-for-the-NameNode-and-the-DataNodes)
+ [Why are the number of splits equal to the number of Maps?](#Why-are-the-number-of-splits-equal-to-the-number-of-Maps)
+ [Is a Job split into maps?](#Is-a-Job-split-into-maps)
+ [Which are the two types of writes in Hdfs?](#Which-are-the-two-types-of-writes-In-Hdfs)
+ [Why reading is done in parallel and writing is not in Hdfs?](#Why-reading-is-done-in-parallel-and-writing-is-not-in-Hdfs)
+ [Can Hadoop be compared to Nosql Database like Cassandra?](#Can-Hadoop-be-compared-to-Nosql-Database-like-Cassandra)
+ [How JobTracker schedules a task?](#How-JobTracker-schedules-a-task)
+ [What is a Task Tracker in Hadoop and how many instances of Task Tracker run on a Hadoop Cluster?](#What-is-a-Task-Tracker-in-Hadoop-and-how-many-instances-of-Task-Tracker-run-on-a-Hadoop-Cluster)
+ [What is a task instance in Hadoop and where does it run?](#What-is-a-task-instance-in-Hadoop-and-where-does-it-run)
+ [What is configuration of a typical Slave Node on Hadoop Cluster and how many Jvms run on a Slave Node?](#What-is-configuration-of-a-typical-Slave-Node-on-Hadoop-Cluster-and-how-many-Jvms-run-on-a-Slave-Node)
+ [How NameNode handles DataNode failures?](#How-NameNode-handles-DataNode-failures)
+ [Does Mapreduce programming model provide a way for Reducers to communicate with each other and in a Mapreduce Job can a Reducer communicate with another Reducer?](#Does-Mapreduce-programming-model-provide-a-way-for-Reducers-to-communicate-with-each-other-and-in-a-Mapreduce-Job-can-a-Reducer-communicate-with-another-Reducer)
+ [Can I set the number of Reducers to Zero?](#Can-I-set-the-number-of-Reducers-to-Zero)
+ [Where is the Mapper Output intermediate Kay-value data stored?](#Where-is-the-Mapper-Output-intermediate-Kay-value-data-stored)
+ [If Reducers do not start before all Mappers finish then why does the progress on Mapreduce Job shows something like Map 50 percents Reduce 10 percents and why Reducers progress percentage is displayed when Mapper is not Finished yet?](#If-Reducers-do-not-start-before-all-Mappers-finish-then-why-does-the-progress-on-Mapreduce-Job-shows-something-like-Map-50-percents-Reduce-10-percents-and-why-Reducers-progress-percentage-is-displayed-when-Mapper-is-not-Finished-yet)
+ [Explain in brief the three Modes in which Hadoop can be run?](#Explain-in-brief-the-three-Modes-in-which-Hadoop-can-be-run)
+ [Explain what are the features of Standalone local Mode?](#Explain-what-are-the-features-of-Standalone-local-Mode)
+ [What are the features of fully distributed mode?](#What-are-the-features-of-fully-distributed-mode)
+ [Explain what are the main features Of pseudo mode?](#Explain-what-are-the-main-features-Of-pseudo-mode)
+ [What are the port numbers of NameNode and JobTracker and TaskTracker?](#What-are-the-port-numbers-of-NameNode-and-JobTracker-and-TaskTracker)
+ [Tell us what is a spill factor with respect to the ram?](#Tell-us-what-is-a-spill-factor-with-respect-to-the-ram)
+ [Is fs.mapr working for a single directory?](#Is-fs.mapr-working-for-a-single-directory)
+ [Which are the three main Hdfs-site.xml properties?](#Which-are-the-three-main-Hdfs-site.xml-properties)
+ [How can I restart NameNode?](#How-can-I-restart-Namenode)
+ [How can we check whether Namenode is working or not?](#How-can-we-check-whether-Namenode-is-working-or-not)
+ [At times you get a connection refused Java Exception when you run the file system check command Hadoop fsck?](#At-times-you-get-a-connection-refused-Java-Exception-when-you-run-the-file-system-check-command-Hadoop-fsck)
+ [What is the use of the command Mapred.job.tracker?](#What-is-the-use-of-the-command-Mapred.job.tracker)
+ [What does etc/init.d do?](#What-does-etc.init.d-do)
+ [How can we look for the Namenode in the browser?](#How-can-we-look-for-the-Namenode-in-the-browser)
+ [What do masters and slaves consist of?](#What-do-masters-and-slaves-consist-of)
+ [What is the function Of Hadoop-env.sh and where is it present?](#What-is-the-function-Of-Hadoop-env.sh-and-where-is-it-present)
+ [Can we have multiple entries in the master files?](#Can-we-have-multiple-entries-in-the-master-files)
+ [In Hadoop_pid_dir and what does pid stands for?](#In-Hadoop_pid_dir-and-what-does-pid-stands-for)
+ [What does Hadoop-metrics and properties file do?](#What-does-Hadoop-metrics-and-properties-file-do)
+ [What are the network requirements for hadoop?](#What-are-the-network-requirements-for-hadoop)
+ [Why do we need a password-less ssh in fully distributed environment?](#Why-do-we-need-a-passwordless-ssh-in-fully-distributed-environment)
+ [What will happen if a NameNode has no data?](#What-will-happen-if-a-NameNode-has-no-data)
+ [What happens to job tracker when NameNode is down?](#What-happens-to-job-tracker-when-NameNode-is-down)
+ [Explain what do you mean by formatting of the Dfs?](#Explain-what-do-you-mean-by-formatting-of-the-Dfs)
+ [We use Unix variants for hadoop and can we use Microsoft Windows for the same?](#We-use-Unix-variants-for-hadoop-and-can-we-use-Microsoft-Windows-for-the-same)
+ [Which one decides the input split hdfs client or NameNode?](#Which-one-decides-the-input-split-hdfs-client-or-NameNode)
+ [Can you tell me if we can create a hadoop cluster from scratch?](#Can-you-tell-me-if-we-can-create-a-hadoop-cluster-from-scratch)
+ [Explain the significance of ssh and what is the port on which port does ssh work and why do we need password in ssh local host?](#Explain-the-significance-of-ssh-and-what-is-the-port-on-which-port-does-ssh-work-and-why-do-we-need-password-in-ssh-local-host)
+ [What is ssh and explain in detail about ssh communication between masters and the slaves?](#What-is-ssh-and-explain-in-detail-about-ssh-communication-between-masters-and-the-slaves)
+ [Can You Tell Is What Will Happen To A NameNode and When Job Tracker Is Not Up And Running?](#Can-you-tell-is-what-will-happen-to-a-NameNode-and-when-Job-tracker-is-not-up-and-running)


## What are the main components of a Hadoop Application?
Over the time, there are various forms in which a Hadoop application is defined. But in most of the cases there are following four core components of Hadoop application:
+ HDFS: This is the file system in which Hadoop data is stored. It is a distributed file system with very high bandwidth.
+ Hadoop Common_: This is common set of libraries and utilities used by Hadoop. 
+ Hadoop MapReduce: This is based on MapReduce algorithm for providing large-scale data processing.
+ Hadoop YARN: This is used for resource management in a Hadoop cluster. It can also schedule tasks for users.

[Table of Contents](#HADOOP)

## What is the core concept behind Apache Hadoop framework?
Apache Hadoop is based on the concept of MapReduce algorithm. In MapReduce algorithm, Map and Reduce operations are used to process very large data set.
    In this concept, Map method does the filtering and sorting of data. Reduce method performs the summarizing of data.
    This is a concept from functional programming.
    The key points in this concept are scalability and fault tolerance. In Apache Hadoop these features are achieved by multi-threading and efficient implementation of MapReduce.

[Table of Contents](#HADOOP)

## What is Hadoop Streaming?
Hadoop distribution provides a Java utility called Hadoop Streaming. It is packaged in a jar file. With Hadoop Streaming, we can create and run Map Reduce jobs with an executable script.
    We can create executable scripts for Mapper and Reducer functions. These executable scripts are passed to Hadoop Streaming in a command.
    Hadoop Streaming utility creates Map and Reduce jobs and submits these to a cluster. We can also monitor these jobs with this utility.

[Table of Contents](#HADOOP)

## What is the difference between Nodes in HDFS?
The differences between NameNode, BackupNode and Checkpoint NameNode are as follows:
+ NameNode: NameNode is at the heart of the HDFS file system that manages the metadata i.e. the data of the files is not stored on the NameNode but rather it has the directory tree of all the files present in the HDFS file system on a Hadoop cluster. NameNode uses two files for the namespace:
    + fsimage file: This file keeps track of the latest checkpoint of the namespace.
    + edits file: This is a log of changes made to the namespace since checkpoint.
+ Checkpoint Node:	Checkpoint Node keeps track of the latest checkpoint in a directory that has same structure as that of NameNode’s directory.
            Checkpoint node creates checkpoints for the namespace at regular intervals by downloading the edits and fsimage file from the NameNode and merging it locally. The new image is then again updated back to the active NameNode.
+ BackupNode: This node also provides check pointing functionality like that of the Checkpoint node but it also maintains its up-to-date in-memory copy of the file system namespace that is in sync with the active NameNode.

[Table of Contents](#HADOOP)

## What is BigQuery, and how does it fit into the data engineering ecosystem?
BigQuery is a fully managed, serverless data warehouse solution provided by Google Cloud Platform (GCP). It allows users to analyze and query large datasets using SQL, with high scalability and performance.

[Table of Contents](#HADOOP)

## What do you know about Block and Block scanner in HDFS?
A large file in HDFS is broken into multiple parts and each part is stored on a different Block. By default a Block is of 64 MB capacity in HDFS.
    Block Scanner is a program that every Data node in HDFS runs periodically to verify the checksum of every block stored on the data node.
    The purpose of a Block Scanner is to detect any data corruption errors on Data node.

[Table of Contents](#HADOOP)

## What are the default port numbers on which Nodes run in Hadoop?
Default port numbers of Name Node, Job Tracker and Task Tracker are as follows:
    NameNode runs on port 50070
    Task Tracker runs on port 50060
    Job Tracker runs on port 50030

[Table of Contents](#HADOOP)

## How will you disable a Block Scanner on HDFS DataNode?
In HDFS, there is a configuration dfs.datanode.scan.period.hours in hdfs-site.xml to set the number of hours interval at which Block Scanner should run.
    We can set dfs.datanode.scan.period.hours=0 to disable the Block Scanner. It means it will not run on HDFS DataNode.

[Table of Contents](#HADOOP)

## How will you get the distance between two nodes in Apache Hadoop?
In Apache Hadoop we can use NetworkTopology.getDistance() method to get the distance between two nodes.
    Distance from a node to its parent is considered as 1.

[Table of Contents](#HADOOP)

## Why do we use commodity hardware in Hadoop?
Hadoop does not require a very high-end server with large memory and processing power. Due to this we can use any inexpensive system with average RAM and processor. Such kind of system is called commodity hardware.
    Since there is parallel processing in Hadoop MapReduce, it is convenient to distribute a task among multiple servers and then do the execution. It saves cost as well as it is much faster compared to other options. Another benefit of using commodity hardware in Hadoop is scalability. Commodity hardware is readily available in market. Whenever we need to scale up our operations in Hadoop cluster we can obtain more commodity hardware. In case of high-end machines, we have to raise purchase orders and get them built on demand.

[Table of Contents](#HADOOP)

## How does inter cluster data copying works in Hadoop?
In Hadoop, there is a utility called DistCP (Distributed Copy) to perform large inter/intra-cluster copying of data. This utility is also based on MapReduce. It creates Map tasks for files given as input.
    After every copy using DistCP, it is recommended to run crosschecks to confirm that there is no data corruption and copy is complete.

[Table of Contents](#HADOOP)

## How can we update a file at an arbitrary location in HDFS?
This is a trick question. In HDFS, it is not allowed to update a file at an arbitrary location. All the files are written in append only mode. It means all writes are done at the end of a file.
    So there is no possibility of updating the files at any random location.

[Table of Contents](#HADOOP)

## What is Replication factor in HDFS?
Replication factor in HDFS is the number of copies of a file in file system. A Hadoop application can specify the number of replicas of a file it wants HDFS to maintain. This information is stored in NameNode. We can set the replication factor in following ways:
    We can use Hadoop fs shell, to specify the replication factor for a file. Command as follows:
+ $hadoop fs –setrep –w 5 /file_name
    In above command, replication factor of file_name  file is set as 5.
    We can also use Hadoop fs shell, to specify the replication factor of all the files in a directory.
+ $hadoop fs –setrep –w 2 /dir_name
    In above command, replication factor of all the files under directory dir_name is set as 2.

[Table of Contents](#HADOOP)

## What is the difference between NAS and DAS in Hadoop cluster?
NAS stands for Network Attached Storage and DAS stands for Direct Attached Storage.
    In NAS, compute and storage layers are separated. Storage is distributed over different servers on a network.
    In DAS, storage is attached to the node where computation takes place.
    Apache Hadoop is based on the principle of moving processing near the location of data. So it needs storage disk to be local to computation.
    With DAS, we get very good performance on a Hadoop cluster. Also DAS can be implemented on commodity hardware. So it is more cost effective.
    Only when we have very high bandwidth (around 10 GbE) it is preferable to use NAS storage.

[Table of Contents](#HADOOP)

## What are the two messages that NameNode receives from DataNode?
NameNode receives following two messages from every DataNode:
+  Heartbeat: This message signals that DataNode is still alive. Periodic receipt of Heartbeat is vey important for NameNode to decide whether to use a DataNode or not.
+  Block Report: This is a list of all the data blocks hosted on a DataNode. This report is also very useful for functioning of NameNode. With this report, NameNode gets information about what data is stored on a specific DataNode.

[Table of Contents](#HADOOP)

## How does indexing work in Hadoop?
Indexing in Hadoop has two different levels.
    Index based on File URI: In this case data is indexed based on different files. When we search for data, index will return the files that contain the data.
    Index based on InputSplit: In this case, data is indexed based on locations where input split is located.

[Table of Contents](#HADOOP)

## What data is stored in a HDFS NameNode?
NameNode is the central node of an HDFS system. It does not store any actual data on which MapReduce operations have to be done. But it has all the metadata about the data stored in HDFS DataNodes.
    NameNode has the directory tree of all the files in HDFS filesystem. Using this meta data it manages all the data stored in different DataNodes.

[Table of Contents](#HADOOP)

## What would happen if NameNode crashes in a HDFS cluster?
There is only one NameNode in a HDFS cluster. This node maintains metadata about DataNodes. Since there is only one NameNode, it is the single point of failure in a HDFS cluster. When NameNode crashes, system may become unavailable.
    We can specify a secondary NameNode in HDFS cluster. The secondary
    NameNode takes the periodic checkpoints of the file system in HDFS. But it is not the backup of NameNode. We can use it to recreate the NameNode and restart it in case of a crash.

[Table of Contents](#HADOOP)

## What are the main functions of Secondary NameNode?
Main functions of Secondary NameNode are as follows:
+ FsImage: It stores a copy of FsImage file and EditLog.
+ NameNode crash: In case NameNode crashes, we can use Secondary NameNode's FsImage to recreate the NameNode.
+ Checkpoint: Secondary NameNode runs Checkpoint to confirm that data is not corrupt in HDFS.

Update: It periodically applies the updates from EditLog to FsImage file. In this way FsImage file on Secondary NameNode is kept up to date. This helps in saving time during NameNode restart.

[Table of Contents](#HADOOP)

## What happens if HDFS file is set with replication factor of 1 and DataNode crashes?
Replication factor is same as the number of copies of a file on HDFS. If we set the replication factor of 1, it means there is only 1 copy of the file.
    In case, DataNode that has this copy of file crashes, the data is lost. There is no way to recover it. It is essential to keep replication factor of more than 1 for any business critical data.

[Table of Contents](#HADOOP)

## What is the meaning of Rack Awareness in Hadoop?
In Hadoop, most of the components like NameNode, DataNode etc are rack- aware. It means they have the information about the rack on which they exist. The main use of rack awareness is in implementing fault-tolerance.
    Any communication between nodes on same rack is much faster than the communication between nodes on two different racks.
    In Hadoop, NameNode maintains information about rack of each DataNode. While reading/writing data, NameNode tries to choose the DataNodes that are closer to each other. Due to performance reasons, it is recommended to use close data nodes for any operation. So Rack Awareness is an important concept for high performance and fault- tolerance in Hadoop.
    If we set Replication factor 3 for a file, does it mean any computation will also take place 3 times?
    No. Replication factor of 3 means that there are 3 copies of a file. But computation takes place only one the one copy of file. If the node on which first copy exists, does not respond then computation will be done on second copy.

[Table of Contents](#HADOOP)

## How will you check if a file exists in HDFS?
In Hadoop, we can run hadoop fs command with option e to check the existence of a file in HDFS. This is generally used for testing purpose. Command will be as follows:
+ %>hadoop fs -test -ezd file_uri e is for checking the existence of file z is for checking non-zero size of
    File d is for checking if the path is directory

[Table of Contents](#HADOOP)

## Why do we use fsck command in HDFS?
fsck command is used for getting the details of files and directories in HDFS. Main uses of fsck command in HDFS are as follows:
+ delete: We use this option to delete files in HDFS.
+ move: This option is for moving corrupt files to lost/found.
+ locations: This option prints all the locations of a block in HDFS.
+ racks: This option gives the network topology of data-node locations.
+ blocks: This option gives the report of blocks in HDFS.

[Table of Contents](#HADOOP)

## What will happen when NameNode is down and a user submits a new job?
Since NameNode is the single point of failure in Hadoop, user job cannot execute. The job will fail when the NameNode is down. User will have to wait for NameNode to restart and come up, before running a job.

[Table of Contents](#HADOOP)

## What are the core methods of a Reducer in Hadoop?
The main task of Reducer is to reduce a larger set of data that shares a key to a smaller set of data. In Hadoop, Reducer has following three core methods:
+ setup(): At the start of a task, setup() method is called to configure various parameters for Reducer.
+ reduce(): This is the main operation of Reducer. In reduce() method we define the task that has to be done for a set of values that share a key.
+ cleanup(): Once reduce() task is done, we can use cleanup() to clean any intermediate data or temporary files.

[Table of Contents](#HADOOP)

## What are the primary phases of a Reducer in Hadoop?
In Hadoop, there are three primary phases of a Reducer:
+ Shuffle: In this phase, Reducer copies the sorted output from each Mapper.
+ Sort: In this phase, Hadoop framework sorts the input to Reducer by same key. It uses merge sort in this phase. Sometimes, shuffle and sort phases occur at the same time.
+ Reduce: This is the phase in which output values associated with a key are reduced to give output result. Output from Reducer is not re-sorted.

[Table of Contents](#HADOOP)

## What is the use of Context object in Hadoop?
Hadoop uses Context object with Mapper to interact with rest of the system. Context object gets the configuration of the system and job in its constructor.
    We use Context object to pass the information in setup(), cleanup() and map() methods. This is an important object that makes the important information available during the map operations.

[Table of Contents](#HADOOP)

## How does partitioning work in Hadoop?
Partitioning is the phase between Map phase and Reduce phase in Hadoop workflow. Since partitioner gives output to Reducer, the number of partitions is same as the number of Reducers.
    Partitioner will partition the output from Map phase into distinct partitions by using a user-defined condition.
    Partitions can be like Hash based buckets.
    E.g. If we have to find the student with the maximum marks in each gender in each subject. We can first use Map function to map the keys with each gender. Once mapping is done, the result is passed to Partitioner. Partitioner will partition each row with gender on the basis of subject. For each subject there will be a different Reducer. Reducer will take input from each partition and find the student with the highest marks.

[Table of Contents](#HADOOP)

## What is a Combiner in Hadoop?
Combiner is an optional step between Map and Reduce. Combiner is also called Semi-Reducer. Combiner takes output from Map, creates Key-value pairs and passes these to Reducer.
    Combiner's task is to summarize the outputs from Map into summary records with same key.
    By using Combiner, we can reduce the data transfer between Mapper and
    Reducer. Combiner does the task similar to reduce but it is done on the Map machine itself.

[Table of Contents](#HADOOP)

## What is the default replication factor in HDFS?
Default replication factor in HDFS is 3. It means there will be 3 copies of each data.
    We can configure it with dfs.replication in hdfs-site.xml file.
    We can even set it from command line in Hadoop fs command.

[Table of Contents](#HADOOP)

## How much storage is allocated by HDFS for storing a file of 25 MB size?
This is a question to test the basic concepts of HDFS. In HDFS, all the data is stored in blocks. The size of block can be configured in HDFS.In Apache Hadoop, the default block size is 64 MB. To store a file of 25 MB size, at least one block will be allocated. This means at least 64 MB will be allocated for the file of 25 MB size.

[Table of Contents](#HADOOP)

## Why does HDFS store data in Block structure?
HDFS stores all the data in terms of Blocks. With Block structure there are some benefits that HDFS gets. Some of these are as follows:
        Fault Tolerance: With Block structure, HDFS implements replication. By replicating same block in multiple locations, fault tolerance of the system increases. Even if some copy is not accessible, we can get the data from another copy.
        Large Files: We can store very large files that cannot be even stored one disk, in HDFS by using Block structure. We just divide the data of file in multiple Blocks. Each Block can be stored on same or different machines.
        Storage management: With Block storage it is easier for Hadoop nodes to calculate the data storage as well as perform optimization in the algorithm to minimize data transfer across the network.

[Table of Contents](#HADOOP)

## How will you create a custom Partitioner in a Hadoop job?
Partition phase runs between Map and Reduce phase. It is an optional phase. We can create a custom partitioner by extending the org.apache.hadoop.mapreduce.Partitio class in Hadoop. In this class, we have to override getPartition(KEY key, VALUE value, int numPartitions) method.
    This method takes three inputs. In this method, numPartitions is same as the number of reducers in our job. We pass key and value to get the partition number to which this key,value record will be assigned. There will be a reducer corresponding to that partition. The reducer will further handle to summarizing of the data.Once custom Partitioner class is ready, we have to set it in the Hadoop job. We can use following method to set it:
        job.setPartitionerClass(CustomPartitioner)

[Table of Contents](#HADOOP)

## What is a Checkpoint node in HDFS?
A Checkpoint node in HDFS periodically fetches fsimage and edits from NameNode, and merges them. This merge result is called a Checkpoint. Once a Checkpoint is created, Checkpoint Node uploads the Checkpoint to NameNode. Secondary node also takes Checkpoint similar to Checkpoint Node. But it does not upload the Checkpoint to NameNode.
    Main benefit of Checkpoint Node is in case of any failure on NameNode. A NameNode does not merge its edits to fsimage automatically during the runtime. If we have long running task, the edits will become huge. When we restart NameNode, it will take much longer time, because it will first merge the edits. In such a scenario, Checkpoint node helps for a long running task.
    Checkpoint nodes performs the task of merging the edits with fsimage and then uploads these to NameNode. This saves time during the restart of NameNode.

[Table of Contents](#HADOOP)

## What is a Backup Node in HDFS?
Backup Node in HDFS is similar to Checkpoint Node. It takes the stream of edits from NameNode. It keeps these edits in memory and also writes these to storage to create a new checkpoint. At any point of time, Backup Node is in sync with the Name Node.
    The difference between Checkpoint Node and Backup Node is that Backup Node does not upload any checkpoints to Name Node. Also Backup node takes a stream instead of periodic reading of edits from Name Node.

[Table of Contents](#HADOOP)

## What is the meaning of term Data Locality in Hadoop?
In a Big Data system, the size of data is huge. So it does not make sense to move data across the network. In such a scenario, Hadoop tries to move computation closer to data. So the Data remains local to the location wherever it was stored. But the computation tasks will be moved to data nodes that hold the data locally.
    Hadoop follows following rules for Data Locality optimization:
+ Hadoop first tries to schedule the task on node that has an HDFS file on a local disk. If it cannot be done, then Hadoop will try to schedule the task on a node on the same rack as the node that has data. If this also cannot be done, Hadoop will schedule the task on the node with same data on a different rack. The above method works well, when we work with the default replication factor of 3 in Hadoop.

[Table of Contents](#HADOOP)

## What is a Balancer in HDFS?
In HDFS, data is stored in blocks on a DataNode. There can be a situation when data is not uniformly spread into blocks on a DataNode. When we add a new DataNode to a cluster, we can face such a situation. In such a case, HDFS provides a useful tool Balancer to analyze the placement of blocks on a DataNode. Some people call it as Rebalancer also. This is an administrative tool used by admin staff. We can use this tool to spread the blocks in a uniform manner on a DataNode.

[Table of Contents](#HADOOP)

## What are the important points a NameNode considers before selecting the DataNode for placing a data block?
Some of the important points for selecting a DataNode by NameNode are as follows:
        NameNode tries to keep at least one replica of a Block on the same node that is writing the block.
        It tries to spread the different replicas of same block on different racks, so that in case of one rack failure, other rack has the data.
        One replica will be kept on a node on the same node as the one that it writing it. It is different from point 1. In Point 1, block is written to same node. In this point block is written on a different node on same rack. This is important for minimizing the network I/O. NameNode also tries to spread the blocks uniformly among all the DataNodes in a cluster.

[Table of Contents](#HADOOP)

## What is Safemode in HDFS?
Safemode is considered as the read-only mode of NameNode in a cluster. During the startup of NameNode, it is in SafeMode. It does not allow writing to file-system in Safemode. At this time, it collects data and statistics from all the DataNodes. Once it has all the data on blocks, it leaves Safemode.
    The main reason for Safemode is to avoid the situation when NameNode starts replicating data in DataNodes before collecting all the information from DataNodes. It may erroneously assume that a block is not replicated well enough, whereas, the issue is that NameNode does not know about whereabouts of all the replicas of a block. Therefore, in Safemode, NameNode first collects the information about how many replicas exist in cluster and then tries to create replicas wherever the number of replicas is less than the policy.

[Table of Contents](#HADOOP)

## How will you replace HDFS data volume before shutting down a DataNode?
In HDFS, DataNode supports hot swappable drives. With a swappable drive we can add or replace HDFS data volumes while the DataNode is still running. The procedure for replacing a hot swappable drive is as follows:
    First we format and mount the new drive. We update the DataNode configuration dfs.datanode.data.dir to reflect the data volume directories. Run the "dfsadmin -reconfig datanode HOST:PORT start" command to start the reconfiguration process Once the reconfiguration is complete, we just unmount the old data volume After unmount we can physically remove the old disks.

[Table of Contents](#HADOOP)

## What are the important configuration files in Hadoop?
There are two important configuration files in a Hadoop cluster:
+ Default Configuration: There are core-default.xml, hdfs-default.xml and mapred-default.xml files in which we specify the default configuration for Hadoop cluster. These are read only files.
+ Custom Configuration: We have site-specific custom files like core-site.xml, hdfs-site.xml, mapred-site.xml in which we can specify the site-specific configuration.
    
All the Jobs in Hadoop and HDFS implementation uses the parameters defined in the above-mentioned files. With customization we can tune these processes according to our use case. In Hadoop API, there is a Configuration class that loads these files and provides the values at run time to different jobs.

[Table of Contents](#HADOOP)

## How will you monitor memory used in a Hadoop cluster?
In Hadoop, TaskTracker is the one that uses high memory to perform a task. We can configure the TastTracker to monitor memory usage of the tasks it creates. It can monitor the memory usage to find the badly behaving tasks, so that these tasks do not bring the machine down with excess memory consumption. In memory monitoring we can also limit the maximum memory used by a tasks. We can even limit the memory usage per node. So that all the tasks executing together on a node do not consume more memory than a limit. Some of the parameters for setting memory monitoring in Hadoop are as follows:
        mapred.cluster.map.memory.mb, mapred.cluster.reduce.memory.mb: This is the size of virtual memory of a single map/reduce slot in a cluster of Map-Reduce framework. mapred.job.map.memory.mb, mapred.job.reduce.memory.mb: This is the default limit of memory
        set on each map/reduce task in Hadoop. mapred.cluster.max.map.memory.m mapred.cluster.max.reduce.memory This is the maximum limit of memory set on each map/reduce task in Hadoop.

[Table of Contents](#HADOOP)

## Why do we need Serialization in Hadoop map reduce methods?
In Hadoop, there are multiple data nodes that hold data. During the processing of map and reduce methods data may transfer from one node to another node. Hadoop uses serialization to convert the data from Object structure to Binary format. With serialization, data can be converted to binary format and with de-serialization data can be converted back to Object format with reliability.

[Table of Contents](#HADOOP)

## What is the use of Distributed Cache in Hadoop?
Hadoop provides a utility called Distributed Cache to improve the performance of jobs by caching the files used by applications. An application can specify which file it wants to cache by using JobConf configuration. Hadoop framework copies these files to the nodes one which a task has to be executed. This is done before the start of execution of a task. DistributedCache supports distribution of simple read only text files as well as complex files like jars, zips etc.

[Table of Contents](#HADOOP)

## How will you synchronize the changes made to a file in Distributed Cache in Hadoop?
It is a trick question. In Distributed Cache, it is not allowed to make any changes to a file. This is a mechanism to cache read-only data across multiple nodes.Therefore, it is not possible to update a cached file or run any synchronization in Distributed Cache.

[Table of Contents](#HADOOP)

## What is BigQuery, and how does it fit into the data engineering ecosystem?
BigQuery is a fully managed, serverless data warehouse solution provided by Google Cloud Platform (GCP). It allows users to analyze and query large datasets using SQL, with high scalability and performance.

[Table of Contents](#HADOOP)
 
## How does BigQuery handle data storage and processing?
BigQuery uses a distributed architecture for data storage and processing. It separates storage and compute, allowing users to scale each independently. Data is stored in Capacitor, a proprietary storage system, while processing is handled by Dremel, a distributed query execution engine.

[Table of Contents](#HADOOP)

## What are the key advantages of using BigQuery?
Some advantages of BigQuery include:
•	Scalability: It can handle massive datasets and query volumes.
•	Cost-effectiveness: Users only pay for the queries and storage they use.
•	Serverless architecture: No infrastructure management is required.
•	Integration with other GCP services: BigQuery can easily integrate with other GCP tools for data ingestion and processing.

[Table of Contents](#HADOOP)
