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
# Warmup Iteration   1: 2.351 ops/ms
Iteration   1: 6.046 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.046 ops/ms


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
# Warmup Iteration   1: 5.959 ops/ms
Iteration   1: 13.107 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.107 ops/ms


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
# Warmup Iteration   1: 4.978 ops/ms
Iteration   1: 9.619 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.619 ops/ms


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
# Warmup Iteration   1: 2.292 ops/ms
Iteration   1: 3.765 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.765 ops/ms


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
# Warmup Iteration   1: 5.629 ±(99.9%) 0.093 ms/op
Iteration   1: 3.400 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.400 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.051 ms/op
Iteration   1: 1.982 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.982 ms/op


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
# Warmup Iteration   1: 4.667 ±(99.9%) 0.050 ms/op
Iteration   1: 3.054 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.054 ms/op


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
# Warmup Iteration   1: 13.190 ±(99.9%) 0.266 ms/op
Iteration   1: 7.671 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.671 ms/op


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
# Warmup Iteration   1: 5.521 ±(99.9%) 0.252 ms/op
Iteration   1: 3.031 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   2.793 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   8.113 ms/op
                 createUser·p0.999:  16.457 ms/op
                 createUser·p0.9999: 16.955 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10773
  mean =      3.031 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1252 
    [ 2.500,  3.750) = 8711 
    [ 3.750,  5.000) = 411 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      2.793 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      8.113 ms/op
     p(99.9000) =     16.457 ms/op
     p(99.9900) =     16.955 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 2.862 ±(99.9%) 0.071 ms/op
Iteration   1: 1.635 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   1.556 ms/op
                 existUser·p0.90:   2.142 ms/op
                 existUser·p0.95:   2.277 ms/op
                 existUser·p0.99:   3.019 ms/op
                 existUser·p0.999:  5.369 ms/op
                 existUser·p0.9999: 7.023 ms/op
                 existUser·p1.00:   7.070 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19565
  mean =      1.635 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 360 
    [1.000, 1.500) = 8034 
    [1.500, 2.000) = 7945 
    [2.000, 2.500) = 2774 
    [2.500, 3.000) = 251 
    [3.000, 3.500) = 77 
    [3.500, 4.000) = 51 
    [4.000, 4.500) = 39 
    [4.500, 5.000) = 3 
    [5.000, 5.500) = 19 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.556 ms/op
     p(90.0000) =      2.142 ms/op
     p(95.0000) =      2.277 ms/op
     p(99.0000) =      3.019 ms/op
     p(99.9000) =      5.369 ms/op
     p(99.9900) =      7.023 ms/op
     p(99.9990) =      7.070 ms/op
     p(99.9999) =      7.070 ms/op
    p(100.0000) =      7.070 ms/op


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.143 ms/op
Iteration   1: 2.962 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   2.855 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  9.191 ms/op
                 getUser·p0.9999: 10.902 ms/op
                 getUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10808
  mean =      2.962 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 245 
    [ 2.000,  3.000) = 5941 
    [ 3.000,  4.000) = 3951 
    [ 4.000,  5.000) = 522 
    [ 5.000,  6.000) = 93 
    [ 6.000,  7.000) = 29 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 3 
    [ 9.000, 10.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     10.902 ms/op
     p(99.9990) =     10.945 ms/op
     p(99.9999) =     10.945 ms/op
    p(100.0000) =     10.945 ms/op


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
# Warmup Iteration   1: 12.673 ±(99.9%) 0.421 ms/op
Iteration   1: 7.785 ±(99.9%) 0.101 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   7.496 ms/op
                 listUser·p0.90:   10.011 ms/op
                 listUser·p0.95:   10.961 ms/op
                 listUser·p0.99:   14.124 ms/op
                 listUser·p0.999:  19.101 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4096
  mean =      7.785 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 24 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 525 
    [ 6.250,  7.500) = 1373 
    [ 7.500,  8.750) = 1056 
    [ 8.750, 10.000) = 575 
    [10.000, 11.250) = 241 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.454 ms/op
     p(50.0000) =      7.496 ms/op
     p(90.0000) =     10.011 ms/op
     p(95.0000) =     10.961 ms/op
     p(99.0000) =     14.124 ms/op
     p(99.9000) =     19.101 ms/op
     p(99.9900) =     19.333 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.046          ops/ms
Client.existUser                       thrpt         13.107          ops/ms
Client.getUser                         thrpt          9.619          ops/ms
Client.listUser                        thrpt          3.765          ops/ms
Client.createUser                       avgt          3.400           ms/op
Client.existUser                        avgt          1.982           ms/op
Client.getUser                          avgt          3.054           ms/op
Client.listUser                         avgt          7.671           ms/op
Client.createUser                     sample  10773   3.031 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.122           ms/op
Client.createUser:createUser·p0.50    sample          2.793           ms/op
Client.createUser:createUser·p0.90    sample          3.555           ms/op
Client.createUser:createUser·p0.95    sample          4.309           ms/op
Client.createUser:createUser·p0.99    sample          8.113           ms/op
Client.createUser:createUser·p0.999   sample         16.457           ms/op
Client.createUser:createUser·p0.9999  sample         16.955           ms/op
Client.createUser:createUser·p1.00    sample         16.974           ms/op
Client.existUser                      sample  19565   1.635 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.671           ms/op
Client.existUser:existUser·p0.50      sample          1.556           ms/op
Client.existUser:existUser·p0.90      sample          2.142           ms/op
Client.existUser:existUser·p0.95      sample          2.277           ms/op
Client.existUser:existUser·p0.99      sample          3.019           ms/op
Client.existUser:existUser·p0.999     sample          5.369           ms/op
Client.existUser:existUser·p0.9999    sample          7.023           ms/op
Client.existUser:existUser·p1.00      sample          7.070           ms/op
Client.getUser                        sample  10808   2.962 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          1.153           ms/op
Client.getUser:getUser·p0.50          sample          2.855           ms/op
Client.getUser:getUser·p0.90          sample          3.793           ms/op
Client.getUser:getUser·p0.95          sample          4.084           ms/op
Client.getUser:getUser·p0.99          sample          5.251           ms/op
Client.getUser:getUser·p0.999         sample          9.191           ms/op
Client.getUser:getUser·p0.9999        sample         10.902           ms/op
Client.getUser:getUser·p1.00          sample         10.945           ms/op
Client.listUser                       sample   4096   7.785 ± 0.101   ms/op
Client.listUser:listUser·p0.00        sample          2.454           ms/op
Client.listUser:listUser·p0.50        sample          7.496           ms/op
Client.listUser:listUser·p0.90        sample         10.011           ms/op
Client.listUser:listUser·p0.95        sample         10.961           ms/op
Client.listUser:listUser·p0.99        sample         14.124           ms/op
Client.listUser:listUser·p0.999       sample         19.101           ms/op
Client.listUser:listUser·p0.9999      sample         19.333           ms/op
Client.listUser:listUser·p1.00        sample         19.333           ms/op
