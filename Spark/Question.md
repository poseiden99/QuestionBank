### suppose 2 wide transformation, 2 narrow transformation and 2 action are their. How many stages and task/Partitions will get created?
 
Answer: 2 wide = 2 stage, 2 action = twice, 1 initial stage for each, so total 3x2=6 stages

### difference between the broadcast variable and cache variable, in which scenario we use them, any limitations?

Answer:

### suppose you have 1 job it contains 5 notebooks, broadcast variable and cache variable created in Notebook 1, can we use them in rest of notebooks, if yes why, if No why..?

Answer:

### suppose 2 GB of file is handled by one job which takes 30 min suddenly it start taking 1-2hr, even though query is optimised. what are steps you would take to debug that, and how you will correct the issue, walk me through it.

Answer:

### What is the difference between repartition() and coalesce() in PySpark? When would you use each?

Answer:

### What are wide vs narrow transformations in Spark? Why does it matter for performance?

Answer:

### How does the Catalyst optimizer work in Spark SQL? What kinds of optimizations does it perform?

Answer:

### Describe the stages and tasks in a Spark job. How can you identify bottlenecks using the DAG?

Answer:


### What is the difference between an action and a transformation in PySpark? Give 2 examples of each

Answer:


### How can you use explode() and posexplode() in PySpark to flatten nested JSON data?
### How would you implement Slowly Changing Dimension Type 2 (SCD Type 2) in PySpark?
### Suppose we want to process 100 GB of data. Tell me the Spark configuration you would use in order to get it processed without any issue. Number of executor nodes, total memory, executor memory, number of executor cores. - Same but different question, suppose there is upstream system.