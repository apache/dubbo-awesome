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
# Warmup Iteration   1: 2.165 ops/ms
Iteration   1: 6.335 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.335 ops/ms


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
# Warmup Iteration   1: 4.958 ops/ms
Iteration   1: 12.630 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.630 ops/ms


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
# Warmup Iteration   1: 4.419 ops/ms
Iteration   1: 8.868 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.868 ops/ms


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
# Warmup Iteration   1: 2.083 ops/ms
Iteration   1: 3.927 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.927 ops/ms


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
# Warmup Iteration   1: 5.267 ±(99.9%) 0.069 ms/op
Iteration   1: 3.361 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.361 ms/op


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
# Warmup Iteration   1: 3.276 ±(99.9%) 0.031 ms/op
Iteration   1: 1.861 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.861 ms/op


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
# Warmup Iteration   1: 5.385 ±(99.9%) 0.068 ms/op
Iteration   1: 2.917 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.917 ms/op


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
# Warmup Iteration   1: 11.851 ±(99.9%) 0.219 ms/op
Iteration   1: 7.643 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.643 ms/op


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
# Warmup Iteration   1: 5.002 ±(99.9%) 0.119 ms/op
Iteration   1: 3.426 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   7.510 ms/op
                 createUser·p0.999:  33.489 ms/op
                 createUser·p0.9999: 33.817 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9553
  mean =      3.426 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 902 
    [ 2.500,  5.000) = 8349 
    [ 5.000,  7.500) = 207 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.510 ms/op
     p(99.9000) =     33.489 ms/op
     p(99.9900) =     33.817 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 3.183 ±(99.9%) 0.084 ms/op
Iteration   1: 1.953 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   1.886 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  6.706 ms/op
                 existUser·p0.9999: 7.077 ms/op
                 existUser·p1.00:   7.234 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16371
  mean =      1.953 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 33 
    [1.000, 1.500) = 1807 
    [1.500, 2.000) = 8329 
    [2.000, 2.500) = 4733 
    [2.500, 3.000) = 1119 
    [3.000, 3.500) = 158 
    [3.500, 4.000) = 91 
    [4.000, 4.500) = 14 
    [4.500, 5.000) = 6 
    [5.000, 5.500) = 29 
    [5.500, 6.000) = 22 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 20 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      6.706 ms/op
     p(99.9900) =      7.077 ms/op
     p(99.9990) =      7.234 ms/op
     p(99.9999) =      7.234 ms/op
    p(100.0000) =      7.234 ms/op


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.107 ms/op
Iteration   1: 2.609 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  7.721 ms/op
                 getUser·p0.9999: 8.084 ms/op
                 getUser·p1.00:   8.086 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12247
  mean =      2.609 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 85 
    [1.500, 2.000) = 934 
    [2.000, 2.500) = 5758 
    [2.500, 3.000) = 3002 
    [3.000, 3.500) = 1457 
    [3.500, 4.000) = 643 
    [4.000, 4.500) = 200 
    [4.500, 5.000) = 55 
    [5.000, 5.500) = 29 
    [5.500, 6.000) = 7 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 26 
    [7.000, 7.500) = 29 
    [7.500, 8.000) = 17 
    [8.000, 8.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      7.721 ms/op
     p(99.9900) =      8.084 ms/op
     p(99.9990) =      8.086 ms/op
     p(99.9999) =      8.086 ms/op
    p(100.0000) =      8.086 ms/op


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
# Warmup Iteration   1: 13.646 ±(99.9%) 0.609 ms/op
Iteration   1: 8.264 ±(99.9%) 0.130 ms/op
                 listUser·p0.00:   2.957 ms/op
                 listUser·p0.50:   7.913 ms/op
                 listUser·p0.90:   10.404 ms/op
                 listUser·p0.95:   11.502 ms/op
                 listUser·p0.99:   15.148 ms/op
                 listUser·p0.999:  31.025 ms/op
                 listUser·p0.9999: 31.785 ms/op
                 listUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3926
  mean =      8.264 ±(99.9%) 0.130 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 59 
    [ 5.000,  7.500) = 1556 
    [ 7.500, 10.000) = 1775 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.957 ms/op
     p(50.0000) =      7.913 ms/op
     p(90.0000) =     10.404 ms/op
     p(95.0000) =     11.502 ms/op
     p(99.0000) =     15.148 ms/op
     p(99.9000) =     31.025 ms/op
     p(99.9900) =     31.785 ms/op
     p(99.9990) =     31.785 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.335          ops/ms
Client.existUser                       thrpt         12.630          ops/ms
Client.getUser                         thrpt          8.868          ops/ms
Client.listUser                        thrpt          3.927          ops/ms
Client.createUser                       avgt          3.361           ms/op
Client.existUser                        avgt          1.861           ms/op
Client.getUser                          avgt          2.917           ms/op
Client.listUser                         avgt          7.643           ms/op
Client.createUser                     sample   9553   3.426 ± 0.059   ms/op
Client.createUser:createUser·p0.00    sample          0.927           ms/op
Client.createUser:createUser·p0.50    sample          3.240           ms/op
Client.createUser:createUser·p0.90    sample          4.190           ms/op
Client.createUser:createUser·p0.95    sample          4.547           ms/op
Client.createUser:createUser·p0.99    sample          7.510           ms/op
Client.createUser:createUser·p0.999   sample         33.489           ms/op
Client.createUser:createUser·p0.9999  sample         33.817           ms/op
Client.createUser:createUser·p1.00    sample         33.817           ms/op
Client.existUser                      sample  16371   1.953 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.652           ms/op
Client.existUser:existUser·p0.50      sample          1.886           ms/op
Client.existUser:existUser·p0.90      sample          2.474           ms/op
Client.existUser:existUser·p0.95      sample          2.650           ms/op
Client.existUser:existUser·p0.99      sample          3.703           ms/op
Client.existUser:existUser·p0.999     sample          6.706           ms/op
Client.existUser:existUser·p0.9999    sample          7.077           ms/op
Client.existUser:existUser·p1.00      sample          7.234           ms/op
Client.getUser                        sample  12247   2.609 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.754           ms/op
Client.getUser:getUser·p0.50          sample          2.433           ms/op
Client.getUser:getUser·p0.90          sample          3.412           ms/op
Client.getUser:getUser·p0.95          sample          3.760           ms/op
Client.getUser:getUser·p0.99          sample          4.858           ms/op
Client.getUser:getUser·p0.999         sample          7.721           ms/op
Client.getUser:getUser·p0.9999        sample          8.084           ms/op
Client.getUser:getUser·p1.00          sample          8.086           ms/op
Client.listUser                       sample   3926   8.264 ± 0.130   ms/op
Client.listUser:listUser·p0.00        sample          2.957           ms/op
Client.listUser:listUser·p0.50        sample          7.913           ms/op
Client.listUser:listUser·p0.90        sample         10.404           ms/op
Client.listUser:listUser·p0.95        sample         11.502           ms/op
Client.listUser:listUser·p0.99        sample         15.148           ms/op
Client.listUser:listUser·p0.999       sample         31.025           ms/op
Client.listUser:listUser·p0.9999      sample         31.785           ms/op
Client.listUser:listUser·p1.00        sample         31.785           ms/op
