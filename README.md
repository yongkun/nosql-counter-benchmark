Counter is an important function in NoSQL systems like Apache Cassandra. Counter can be used to count the activities in real-time, such as 'tweet it' by Twitter, 'like' by Facebook, '+1' by Google+. Therefore, the performance of Counter operation is a good indicator for NoSQL systems. YCSB (Yahoo Cloud Service Benchmark) doesn't provide this benchmark.

The following aspects are measured:
1. single row or different row
2. percentage of new/old counters
3. batch size
4. single thread or multi-threading

