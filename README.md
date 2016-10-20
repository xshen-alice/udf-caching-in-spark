# udf-caching-in-spark
Improved the UDF performance by using a course-grained hash function to stream input into multiple partition relations on disks and then executed parallel query processing in spark.
