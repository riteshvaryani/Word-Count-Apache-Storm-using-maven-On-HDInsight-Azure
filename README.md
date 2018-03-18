# Word-Count-Apache-Storm-using-maven-On-HDInsight-Azure
This is a simple word-count project to run a word count on a set of strings using Apache Storm. it contains the input Spout of random strings out of which these strings are sent to at random to the Bolts- first for splitting and then on to the next bolt for counting of the words and outputting on the console. The maven project is run using the command 

``` compile exec:java -Dstorm.topology=com.microsoft.example.WordCountTopology```

from the source directory of the project.
