# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.599 ops/ms
Iteration   1: 6.117 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.117 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.719 ops/ms
Iteration   1: 13.926 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.926 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ops/ms
Iteration   1: 7.845 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.845 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.352 ops/ms
Iteration   1: 3.973 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.973 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.536 ±(99.9%) 0.078 ms/op
Iteration   1: 3.110 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.110 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.211 ±(99.9%) 0.036 ms/op
Iteration   1: 2.012 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.012 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.455 ±(99.9%) 0.060 ms/op
Iteration   1: 2.859 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.859 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.898 ±(99.9%) 0.229 ms/op
Iteration   1: 7.994 ±(99.9%) 0.115 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.994 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.786 ±(99.9%) 0.094 ms/op
Iteration   1: 3.374 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   11.422 ms/op
                 createUser·p0.999:  21.037 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9484
  mean =      3.374 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 798 
    [ 2.500,  5.000) = 8352 
    [ 5.000,  7.500) = 157 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =     11.422 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.950 ±(99.9%) 0.053 ms/op
Iteration   1: 2.134 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.449 ms/op
                 existUser·p0.50:   2.042 ms/op
                 existUser·p0.90:   2.666 ms/op
                 existUser·p0.95:   2.884 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  11.272 ms/op
                 existUser·p0.9999: 11.510 ms/op
                 existUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14977
  mean =      2.134 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 12293 
    [ 2.500,  3.750) = 2372 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     11.510 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.089 ms/op
Iteration   1: 2.783 ±(99.9%) 0.056 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   8.058 ms/op
                 getUser·p0.999:  28.443 ms/op
                 getUser·p0.9999: 29.541 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11479
  mean =      2.783 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5623 
    [ 2.500,  5.000) = 5653 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      8.058 ms/op
     p(99.9000) =     28.443 ms/op
     p(99.9900) =     29.541 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 10.766 ±(99.9%) 0.377 ms/op
Iteration   1: 7.864 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   7.553 ms/op
                 listUser·p0.90:   10.486 ms/op
                 listUser·p0.95:   11.846 ms/op
                 listUser·p0.99:   15.764 ms/op
                 listUser·p0.999:  17.397 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4070
  mean =      7.864 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 23 
    [ 3.750,  5.000) = 154 
    [ 5.000,  6.250) = 787 
    [ 6.250,  7.500) = 1033 
    [ 7.500,  8.750) = 925 
    [ 8.750, 10.000) = 587 
    [10.000, 11.250) = 286 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.433 ms/op
     p(50.0000) =      7.553 ms/op
     p(90.0000) =     10.486 ms/op
     p(95.0000) =     11.846 ms/op
     p(99.0000) =     15.764 ms/op
     p(99.9000) =     17.397 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.117          ops/ms
Client.existUser                       thrpt         13.926          ops/ms
Client.getUser                         thrpt          7.845          ops/ms
Client.listUser                        thrpt          3.973          ops/ms
Client.createUser                       avgt          3.110           ms/op
Client.existUser                        avgt          2.012           ms/op
Client.getUser                          avgt          2.859           ms/op
Client.listUser                         avgt          7.994           ms/op
Client.createUser                     sample   9484   3.374 ± 0.054   ms/op
Client.createUser:createUser·p0.00    sample          1.229           ms/op
Client.createUser:createUser·p0.50    sample          3.158           ms/op
Client.createUser:createUser·p0.90    sample          3.944           ms/op
Client.createUser:createUser·p0.95    sample          4.506           ms/op
Client.createUser:createUser·p0.99    sample         11.422           ms/op
Client.createUser:createUser·p0.999   sample         21.037           ms/op
Client.createUser:createUser·p0.9999  sample         21.463           ms/op
Client.createUser:createUser·p1.00    sample         21.463           ms/op
Client.existUser                      sample  14977   2.134 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.449           ms/op
Client.existUser:existUser·p0.50      sample          2.042           ms/op
Client.existUser:existUser·p0.90      sample          2.666           ms/op
Client.existUser:existUser·p0.95      sample          2.884           ms/op
Client.existUser:existUser·p0.99      sample          4.530           ms/op
Client.existUser:existUser·p0.999     sample         11.272           ms/op
Client.existUser:existUser·p0.9999    sample         11.510           ms/op
Client.existUser:existUser·p1.00      sample         11.518           ms/op
Client.getUser                        sample  11479   2.783 ± 0.056   ms/op
Client.getUser:getUser·p0.00          sample          0.804           ms/op
Client.getUser:getUser·p0.50          sample          2.515           ms/op
Client.getUser:getUser·p0.90          sample          3.416           ms/op
Client.getUser:getUser·p0.95          sample          3.838           ms/op
Client.getUser:getUser·p0.99          sample          8.058           ms/op
Client.getUser:getUser·p0.999         sample         28.443           ms/op
Client.getUser:getUser·p0.9999        sample         29.541           ms/op
Client.getUser:getUser·p1.00          sample         29.590           ms/op
Client.listUser                       sample   4070   7.864 ± 0.112   ms/op
Client.listUser:listUser·p0.00        sample          2.433           ms/op
Client.listUser:listUser·p0.50        sample          7.553           ms/op
Client.listUser:listUser·p0.90        sample         10.486           ms/op
Client.listUser:listUser·p0.95        sample         11.846           ms/op
Client.listUser:listUser·p0.99        sample         15.764           ms/op
Client.listUser:listUser·p0.999       sample         17.397           ms/op
Client.listUser:listUser·p0.9999      sample         17.727           ms/op
Client.listUser:listUser·p1.00        sample         17.727           ms/op
