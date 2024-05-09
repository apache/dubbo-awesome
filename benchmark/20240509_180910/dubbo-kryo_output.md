# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.743 ops/ms
Iteration   1: 7.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.881 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.379 ops/ms
Iteration   1: 11.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.600 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.041 ops/ms
Iteration   1: 12.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.546 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.162 ops/ms
Iteration   1: 8.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.392 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.091 ms/op
Iteration   1: 2.071 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.071 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ±(99.9%) 0.058 ms/op
Iteration   1: 1.939 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.939 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.202 ±(99.9%) 0.058 ms/op
Iteration   1: 1.972 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.972 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.552 ±(99.9%) 0.087 ms/op
Iteration   1: 3.553 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.553 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.112 ms/op
Iteration   1: 2.116 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.427 ms/op
                 createUser·p0.50:   1.923 ms/op
                 createUser·p0.90:   2.617 ms/op
                 createUser·p0.95:   2.933 ms/op
                 createUser·p0.99:   7.060 ms/op
                 createUser·p0.999:  18.055 ms/op
                 createUser·p0.9999: 22.108 ms/op
                 createUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15152
  mean =      2.116 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13247 
    [ 2.500,  5.000) = 1661 
    [ 5.000,  7.500) = 114 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.427 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      7.060 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     22.108 ms/op
     p(99.9990) =     22.446 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.682 ±(99.9%) 0.061 ms/op
Iteration   1: 1.853 ±(99.9%) 0.051 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.089 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  36.756 ms/op
                 existUser·p0.9999: 40.244 ms/op
                 existUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17697
  mean =      1.853 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 17581 
    [ 5.000, 10.000) = 10 
    [10.000, 15.000) = 5 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 36 
    [25.000, 30.000) = 35 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.089 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =     36.756 ms/op
     p(99.9900) =     40.244 ms/op
     p(99.9990) =     40.698 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.310 ±(99.9%) 0.088 ms/op
Iteration   1: 1.728 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.411 ms/op
                 getUser·p0.50:   1.645 ms/op
                 getUser·p0.90:   2.159 ms/op
                 getUser·p0.95:   2.372 ms/op
                 getUser·p0.99:   3.061 ms/op
                 getUser·p0.999:  14.557 ms/op
                 getUser·p0.9999: 15.521 ms/op
                 getUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18484
  mean =      1.728 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1424 
    [ 1.250,  2.500) = 16417 
    [ 2.500,  3.750) = 541 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      3.061 ms/op
     p(99.9000) =     14.557 ms/op
     p(99.9900) =     15.521 ms/op
     p(99.9990) =     15.548 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.315 ±(99.9%) 0.123 ms/op
Iteration   1: 3.514 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.187 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  20.926 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9200
  mean =      3.514 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 989 
    [ 2.500,  5.000) = 7689 
    [ 5.000,  7.500) = 415 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     20.926 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.881          ops/ms
ClientSimple.existUser                       thrpt         11.600          ops/ms
ClientSimple.getUser                         thrpt         12.546          ops/ms
ClientSimple.listUser                        thrpt          8.392          ops/ms
ClientSimple.createUser                       avgt          2.071           ms/op
ClientSimple.existUser                        avgt          1.939           ms/op
ClientSimple.getUser                          avgt          1.972           ms/op
ClientSimple.listUser                         avgt          3.553           ms/op
ClientSimple.createUser                     sample  15152   2.116 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.427           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.923           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.060           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.055           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.108           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.446           ms/op
ClientSimple.existUser                      sample  17697   1.853 ± 0.051   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.498           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.638           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.089           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.453           ms/op
ClientSimple.existUser:existUser·p0.999     sample         36.756           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         40.244           ms/op
ClientSimple.existUser:existUser·p1.00      sample         40.698           ms/op
ClientSimple.getUser                        sample  18484   1.728 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.411           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.645           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.061           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.557           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.521           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.548           ms/op
ClientSimple.listUser                       sample   9200   3.514 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.862           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.187           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.054           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.602           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.926           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.036           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.036           ms/op

Benchmark result is saved to 1715277887234.json
