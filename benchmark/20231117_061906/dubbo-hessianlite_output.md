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
# Warmup Iteration   1: 2.380 ops/ms
Iteration   1: 5.979 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.979 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.888 ops/ms
Iteration   1: 11.861 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.861 ops/ms


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
# Warmup Iteration   1: 3.997 ops/ms
Iteration   1: 8.113 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.113 ops/ms


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
# Warmup Iteration   1: 1.998 ops/ms
Iteration   1: 3.614 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.614 ops/ms


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.071 ms/op
Iteration   1: 3.417 ±(99.9%) 0.056 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.417 ms/op


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
# Warmup Iteration   1: 2.751 ±(99.9%) 0.028 ms/op
Iteration   1: 1.866 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.866 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.049 ms/op
Iteration   1: 2.927 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.927 ms/op


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
# Warmup Iteration   1: 11.061 ±(99.9%) 0.170 ms/op
Iteration   1: 7.838 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.838 ms/op


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
# Warmup Iteration   1: 4.854 ±(99.9%) 0.123 ms/op
Iteration   1: 3.008 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   2.830 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.699 ms/op
                 createUser·p0.999:  11.229 ms/op
                 createUser·p0.9999: 15.863 ms/op
                 createUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10624
  mean =      3.008 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2240 
    [ 2.500,  3.750) = 7491 
    [ 3.750,  5.000) = 567 
    [ 5.000,  6.250) = 175 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.699 ms/op
     p(99.9000) =     11.229 ms/op
     p(99.9900) =     15.863 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.056 ms/op
Iteration   1: 1.815 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   1.739 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.404 ms/op
                 existUser·p0.99:   2.867 ms/op
                 existUser·p0.999:  6.729 ms/op
                 existUser·p0.9999: 6.810 ms/op
                 existUser·p1.00:   6.816 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17616
  mean =      1.815 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 13 
    [1.000, 1.500) = 879 
    [1.500, 2.000) = 14192 
    [2.000, 2.500) = 1869 
    [2.500, 3.000) = 523 
    [3.000, 3.500) = 54 
    [3.500, 4.000) = 15 
    [4.000, 4.500) = 1 
    [4.500, 5.000) = 4 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 21 
    [6.000, 6.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      2.867 ms/op
     p(99.9000) =      6.729 ms/op
     p(99.9900) =      6.810 ms/op
     p(99.9990) =      6.816 ms/op
     p(99.9999) =      6.816 ms/op
    p(100.0000) =      6.816 ms/op


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.106 ms/op
Iteration   1: 3.080 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.941 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.284 ms/op
                 getUser·p0.999:  13.238 ms/op
                 getUser·p0.9999: 13.514 ms/op
                 getUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10438
  mean =      3.080 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2598 
    [ 2.500,  3.750) = 6262 
    [ 3.750,  5.000) = 1434 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.941 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.284 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     13.514 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


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
# Warmup Iteration   1: 10.847 ±(99.9%) 0.321 ms/op
Iteration   1: 7.238 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   2.781 ms/op
                 listUser·p0.50:   6.865 ms/op
                 listUser·p0.90:   9.470 ms/op
                 listUser·p0.95:   10.567 ms/op
                 listUser·p0.99:   15.780 ms/op
                 listUser·p0.999:  23.983 ms/op
                 listUser·p0.9999: 27.656 ms/op
                 listUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4426
  mean =      7.238 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 346 
    [ 5.000,  7.500) = 2523 
    [ 7.500, 10.000) = 1260 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.781 ms/op
     p(50.0000) =      6.865 ms/op
     p(90.0000) =      9.470 ms/op
     p(95.0000) =     10.567 ms/op
     p(99.0000) =     15.780 ms/op
     p(99.9000) =     23.983 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.979          ops/ms
Client.existUser                       thrpt         11.861          ops/ms
Client.getUser                         thrpt          8.113          ops/ms
Client.listUser                        thrpt          3.614          ops/ms
Client.createUser                       avgt          3.417           ms/op
Client.existUser                        avgt          1.866           ms/op
Client.getUser                          avgt          2.927           ms/op
Client.listUser                         avgt          7.838           ms/op
Client.createUser                     sample  10624   3.008 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          1.223           ms/op
Client.createUser:createUser·p0.50    sample          2.830           ms/op
Client.createUser:createUser·p0.90    sample          3.621           ms/op
Client.createUser:createUser·p0.95    sample          4.309           ms/op
Client.createUser:createUser·p0.99    sample          6.699           ms/op
Client.createUser:createUser·p0.999   sample         11.229           ms/op
Client.createUser:createUser·p0.9999  sample         15.863           ms/op
Client.createUser:createUser·p1.00    sample         16.073           ms/op
Client.existUser                      sample  17616   1.815 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.899           ms/op
Client.existUser:existUser·p0.50      sample          1.739           ms/op
Client.existUser:existUser·p0.90      sample          2.126           ms/op
Client.existUser:existUser·p0.95      sample          2.404           ms/op
Client.existUser:existUser·p0.99      sample          2.867           ms/op
Client.existUser:existUser·p0.999     sample          6.729           ms/op
Client.existUser:existUser·p0.9999    sample          6.810           ms/op
Client.existUser:existUser·p1.00      sample          6.816           ms/op
Client.getUser                        sample  10438   3.080 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          1.276           ms/op
Client.getUser:getUser·p0.50          sample          2.929           ms/op
Client.getUser:getUser·p0.90          sample          3.941           ms/op
Client.getUser:getUser·p0.95          sample          4.301           ms/op
Client.getUser:getUser·p0.99          sample          6.284           ms/op
Client.getUser:getUser·p0.999         sample         13.238           ms/op
Client.getUser:getUser·p0.9999        sample         13.514           ms/op
Client.getUser:getUser·p1.00          sample         13.517           ms/op
Client.listUser                       sample   4426   7.238 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample          2.781           ms/op
Client.listUser:listUser·p0.50        sample          6.865           ms/op
Client.listUser:listUser·p0.90        sample          9.470           ms/op
Client.listUser:listUser·p0.95        sample         10.567           ms/op
Client.listUser:listUser·p0.99        sample         15.780           ms/op
Client.listUser:listUser·p0.999       sample         23.983           ms/op
Client.listUser:listUser·p0.9999      sample         27.656           ms/op
Client.listUser:listUser·p1.00        sample         27.656           ms/op
