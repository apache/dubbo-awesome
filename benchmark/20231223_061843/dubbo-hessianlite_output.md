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
# Warmup Iteration   1: 2.457 ops/ms
Iteration   1: 5.614 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.614 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.865 ops/ms
Iteration   1: 15.837 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  15.837 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.453 ops/ms
Iteration   1: 9.387 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.387 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.918 ops/ms
Iteration   1: 3.643 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.643 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.176 ±(99.9%) 0.066 ms/op
Iteration   1: 3.296 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.296 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.098 ±(99.9%) 0.031 ms/op
Iteration   1: 2.034 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.034 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ±(99.9%) 0.054 ms/op
Iteration   1: 2.898 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.898 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.649 ±(99.9%) 0.232 ms/op
Iteration   1: 7.930 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.930 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ±(99.9%) 0.123 ms/op
Iteration   1: 2.997 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   2.839 ms/op
                 createUser·p0.90:   3.545 ms/op
                 createUser·p0.95:   4.005 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  22.512 ms/op
                 createUser·p0.9999: 23.125 ms/op
                 createUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10665
  mean =      2.997 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1937 
    [ 2.500,  5.000) = 8562 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.545 ms/op
     p(95.0000) =      4.005 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     22.512 ms/op
     p(99.9900) =     23.125 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.950 ±(99.9%) 0.061 ms/op
Iteration   1: 1.750 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.448 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   2.816 ms/op
                 existUser·p0.999:  4.205 ms/op
                 existUser·p0.9999: 5.405 ms/op
                 existUser·p1.00:   5.743 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18246
  mean =      1.750 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 10 
    [1.000, 1.500) = 3397 
    [1.500, 2.000) = 11660 
    [2.000, 2.500) = 2469 
    [2.500, 3.000) = 625 
    [3.000, 3.500) = 55 
    [3.500, 4.000) = 10 
    [4.000, 4.500) = 5 
    [4.500, 5.000) = 10 
    [5.000, 5.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      2.816 ms/op
     p(99.9000) =      4.205 ms/op
     p(99.9900) =      5.405 ms/op
     p(99.9990) =      5.743 ms/op
     p(99.9999) =      5.743 ms/op
    p(100.0000) =      5.743 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.242 ±(99.9%) 0.116 ms/op
Iteration   1: 2.942 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   2.789 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   4.023 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  17.498 ms/op
                 getUser·p0.9999: 18.035 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10874
  mean =      2.942 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 2572 
    [ 2.500,  3.750) = 7377 
    [ 3.750,  5.000) = 802 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.023 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     18.035 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.031 ±(99.9%) 0.413 ms/op
Iteration   1: 7.944 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   7.504 ms/op
                 listUser·p0.90:   9.952 ms/op
                 listUser·p0.95:   11.164 ms/op
                 listUser·p0.99:   21.404 ms/op
                 listUser·p0.999:  31.737 ms/op
                 listUser·p0.9999: 33.489 ms/op
                 listUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4225
  mean =      7.944 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 110 
    [ 5.000,  7.500) = 1997 
    [ 7.500, 10.000) = 1717 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.327 ms/op
     p(50.0000) =      7.504 ms/op
     p(90.0000) =      9.952 ms/op
     p(95.0000) =     11.164 ms/op
     p(99.0000) =     21.404 ms/op
     p(99.9000) =     31.737 ms/op
     p(99.9900) =     33.489 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.614          ops/ms
Client.existUser                       thrpt         15.837          ops/ms
Client.getUser                         thrpt          9.387          ops/ms
Client.listUser                        thrpt          3.643          ops/ms
Client.createUser                       avgt          3.296           ms/op
Client.existUser                        avgt          2.034           ms/op
Client.getUser                          avgt          2.898           ms/op
Client.listUser                         avgt          7.930           ms/op
Client.createUser                     sample  10665   2.997 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          0.870           ms/op
Client.createUser:createUser·p0.50    sample          2.839           ms/op
Client.createUser:createUser·p0.90    sample          3.545           ms/op
Client.createUser:createUser·p0.95    sample          4.005           ms/op
Client.createUser:createUser·p0.99    sample          6.685           ms/op
Client.createUser:createUser·p0.999   sample         22.512           ms/op
Client.createUser:createUser·p0.9999  sample         23.125           ms/op
Client.createUser:createUser·p1.00    sample         23.134           ms/op
Client.existUser                      sample  18246   1.750 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.448           ms/op
Client.existUser:existUser·p0.50      sample          1.667           ms/op
Client.existUser:existUser·p0.90      sample          2.200           ms/op
Client.existUser:existUser·p0.95      sample          2.429           ms/op
Client.existUser:existUser·p0.99      sample          2.816           ms/op
Client.existUser:existUser·p0.999     sample          4.205           ms/op
Client.existUser:existUser·p0.9999    sample          5.405           ms/op
Client.existUser:existUser·p1.00      sample          5.743           ms/op
Client.getUser                        sample  10874   2.942 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          0.819           ms/op
Client.getUser:getUser·p0.50          sample          2.789           ms/op
Client.getUser:getUser·p0.90          sample          3.650           ms/op
Client.getUser:getUser·p0.95          sample          4.023           ms/op
Client.getUser:getUser·p0.99          sample          5.071           ms/op
Client.getUser:getUser·p0.999         sample         17.498           ms/op
Client.getUser:getUser·p0.9999        sample         18.035           ms/op
Client.getUser:getUser·p1.00          sample         18.055           ms/op
Client.listUser                       sample   4225   7.944 ± 0.137   ms/op
Client.listUser:listUser·p0.00        sample          2.327           ms/op
Client.listUser:listUser·p0.50        sample          7.504           ms/op
Client.listUser:listUser·p0.90        sample          9.952           ms/op
Client.listUser:listUser·p0.95        sample         11.164           ms/op
Client.listUser:listUser·p0.99        sample         21.404           ms/op
Client.listUser:listUser·p0.999       sample         31.737           ms/op
Client.listUser:listUser·p0.9999      sample         33.489           ms/op
Client.listUser:listUser·p1.00        sample         33.489           ms/op
