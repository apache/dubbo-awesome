# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.113 ops/ms
Iteration   1: 2.300 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.300 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.381 ops/ms
Iteration   1: 5.963 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.963 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.998 ops/ms
Iteration   1: 4.187 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.187 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.780 ops/ms
Iteration   1: 1.357 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.357 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 18.649 ±(99.9%) 0.266 ms/op
Iteration   1: 8.871 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.871 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.979 ±(99.9%) 0.070 ms/op
Iteration   1: 4.757 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.018 ±(99.9%) 0.180 ms/op
Iteration   1: 5.468 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.468 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 27.819 ±(99.9%) 0.572 ms/op
Iteration   1: 17.851 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.851 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.548 ±(99.9%) 0.358 ms/op
Iteration   1: 6.543 ±(99.9%) 0.106 ms/op
                 createUser·p0.00:   2.523 ms/op
                 createUser·p0.50:   6.746 ms/op
                 createUser·p0.90:   7.725 ms/op
                 createUser·p0.95:   8.856 ms/op
                 createUser·p0.99:   13.779 ms/op
                 createUser·p0.999:  24.624 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4924
  mean =      6.543 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1140 
    [ 5.000,  7.500) = 2808 
    [ 7.500, 10.000) = 773 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.523 ms/op
     p(50.0000) =      6.746 ms/op
     p(90.0000) =      7.725 ms/op
     p(95.0000) =      8.856 ms/op
     p(99.0000) =     13.779 ms/op
     p(99.9000) =     24.624 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.577 ±(99.9%) 0.186 ms/op
Iteration   1: 4.397 ±(99.9%) 0.118 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   7.717 ms/op
                 existUser·p0.99:   14.139 ms/op
                 existUser·p0.999:  39.070 ms/op
                 existUser·p0.9999: 40.305 ms/op
                 existUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7277
  mean =      4.397 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6371 
    [ 5.000, 10.000) = 710 
    [10.000, 15.000) = 134 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =     14.139 ms/op
     p(99.9000) =     39.070 ms/op
     p(99.9900) =     40.305 ms/op
     p(99.9990) =     40.305 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 11.205 ±(99.9%) 0.395 ms/op
Iteration   1: 4.817 ±(99.9%) 0.097 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   6.242 ms/op
                 getUser·p0.95:   7.455 ms/op
                 getUser·p0.99:   19.300 ms/op
                 getUser·p0.999:  24.248 ms/op
                 getUser·p0.9999: 24.281 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6671
  mean =      4.817 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 4270 
    [ 5.000,  7.500) = 2036 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     19.300 ms/op
     p(99.9000) =     24.248 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.494 ±(99.9%) 0.690 ms/op
Iteration   1: 16.581 ±(99.9%) 0.172 ms/op
                 listUser·p0.00:   6.496 ms/op
                 listUser·p0.50:   16.171 ms/op
                 listUser·p0.90:   18.481 ms/op
                 listUser·p0.95:   19.975 ms/op
                 listUser·p0.99:   27.066 ms/op
                 listUser·p0.999:  29.920 ms/op
                 listUser·p0.9999: 29.950 ms/op
                 listUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1921
  mean =     16.581 ±(99.9%) 0.172 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 1412 
    [17.500, 20.000) = 286 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      6.496 ms/op
     p(50.0000) =     16.171 ms/op
     p(90.0000) =     18.481 ms/op
     p(95.0000) =     19.975 ms/op
     p(99.0000) =     27.066 ms/op
     p(99.9000) =     29.920 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.300          ops/ms
Client.existUser                       thrpt         5.963          ops/ms
Client.getUser                         thrpt         4.187          ops/ms
Client.listUser                        thrpt         1.357          ops/ms
Client.createUser                       avgt         8.871           ms/op
Client.existUser                        avgt         4.757           ms/op
Client.getUser                          avgt         5.468           ms/op
Client.listUser                         avgt        17.851           ms/op
Client.createUser                     sample  4924   6.543 ± 0.106   ms/op
Client.createUser:createUser·p0.00    sample         2.523           ms/op
Client.createUser:createUser·p0.50    sample         6.746           ms/op
Client.createUser:createUser·p0.90    sample         7.725           ms/op
Client.createUser:createUser·p0.95    sample         8.856           ms/op
Client.createUser:createUser·p0.99    sample        13.779           ms/op
Client.createUser:createUser·p0.999   sample        24.624           ms/op
Client.createUser:createUser·p0.9999  sample        26.280           ms/op
Client.createUser:createUser·p1.00    sample        26.280           ms/op
Client.existUser                      sample  7277   4.397 ± 0.118   ms/op
Client.existUser:existUser·p0.00      sample         1.346           ms/op
Client.existUser:existUser·p0.50      sample         4.047           ms/op
Client.existUser:existUser·p0.90      sample         5.399           ms/op
Client.existUser:existUser·p0.95      sample         7.717           ms/op
Client.existUser:existUser·p0.99      sample        14.139           ms/op
Client.existUser:existUser·p0.999     sample        39.070           ms/op
Client.existUser:existUser·p0.9999    sample        40.305           ms/op
Client.existUser:existUser·p1.00      sample        40.305           ms/op
Client.getUser                        sample  6671   4.817 ± 0.097   ms/op
Client.getUser:getUser·p0.00          sample         1.382           ms/op
Client.getUser:getUser·p0.50          sample         4.325           ms/op
Client.getUser:getUser·p0.90          sample         6.242           ms/op
Client.getUser:getUser·p0.95          sample         7.455           ms/op
Client.getUser:getUser·p0.99          sample        19.300           ms/op
Client.getUser:getUser·p0.999         sample        24.248           ms/op
Client.getUser:getUser·p0.9999        sample        24.281           ms/op
Client.getUser:getUser·p1.00          sample        24.281           ms/op
Client.listUser                       sample  1921  16.581 ± 0.172   ms/op
Client.listUser:listUser·p0.00        sample         6.496           ms/op
Client.listUser:listUser·p0.50        sample        16.171           ms/op
Client.listUser:listUser·p0.90        sample        18.481           ms/op
Client.listUser:listUser·p0.95        sample        19.975           ms/op
Client.listUser:listUser·p0.99        sample        27.066           ms/op
Client.listUser:listUser·p0.999       sample        29.920           ms/op
Client.listUser:listUser·p0.9999      sample        29.950           ms/op
Client.listUser:listUser·p1.00        sample        29.950           ms/op
