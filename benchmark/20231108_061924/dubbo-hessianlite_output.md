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
# Warmup Iteration   1: 2.296 ops/ms
Iteration   1: 5.864 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.864 ops/ms


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
# Warmup Iteration   1: 7.276 ops/ms
Iteration   1: 13.672 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.672 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.691 ops/ms
Iteration   1: 9.615 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.615 ops/ms


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
# Warmup Iteration   1: 2.435 ops/ms
Iteration   1: 3.887 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.887 ops/ms


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
# Warmup Iteration   1: 4.733 ±(99.9%) 0.060 ms/op
Iteration   1: 2.807 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.807 ms/op


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
# Warmup Iteration   1: 3.042 ±(99.9%) 0.034 ms/op
Iteration   1: 1.945 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.945 ms/op


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.053 ms/op
Iteration   1: 2.967 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.967 ms/op


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
# Warmup Iteration   1: 11.889 ±(99.9%) 0.191 ms/op
Iteration   1: 8.552 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.552 ms/op


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
# Warmup Iteration   1: 4.888 ±(99.9%) 0.097 ms/op
Iteration   1: 3.049 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   2.691 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.413 ms/op
                 createUser·p0.99:   10.863 ms/op
                 createUser·p0.999:  32.244 ms/op
                 createUser·p0.9999: 33.517 ms/op
                 createUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10485
  mean =      3.049 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4342 
    [ 2.500,  5.000) = 5748 
    [ 5.000,  7.500) = 167 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      2.691 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.413 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     32.244 ms/op
     p(99.9900) =     33.517 ms/op
     p(99.9990) =     33.522 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 2.934 ±(99.9%) 0.047 ms/op
Iteration   1: 2.130 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.091 ms/op
                 existUser·p0.90:   2.642 ms/op
                 existUser·p0.95:   2.826 ms/op
                 existUser·p0.99:   3.844 ms/op
                 existUser·p0.999:  5.194 ms/op
                 existUser·p0.9999: 5.595 ms/op
                 existUser·p1.00:   5.612 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15043
  mean =      2.130 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 53 
    [1.000, 1.500) = 621 
    [1.500, 2.000) = 5482 
    [2.000, 2.500) = 6310 
    [2.500, 3.000) = 2255 
    [3.000, 3.500) = 163 
    [3.500, 4.000) = 44 
    [4.000, 4.500) = 55 
    [4.500, 5.000) = 44 
    [5.000, 5.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.091 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      3.844 ms/op
     p(99.9000) =      5.194 ms/op
     p(99.9900) =      5.595 ms/op
     p(99.9990) =      5.612 ms/op
     p(99.9999) =      5.612 ms/op
    p(100.0000) =      5.612 ms/op


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.095 ms/op
Iteration   1: 3.256 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.231 ms/op
                 getUser·p0.999:  21.660 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9841
  mean =      3.256 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1253 
    [ 2.500,  5.000) = 8343 
    [ 5.000,  7.500) = 176 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.231 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 12.299 ±(99.9%) 0.444 ms/op
Iteration   1: 8.286 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   7.946 ms/op
                 listUser·p0.90:   11.474 ms/op
                 listUser·p0.95:   12.911 ms/op
                 listUser·p0.99:   16.134 ms/op
                 listUser·p0.999:  19.361 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3856
  mean =      8.286 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 176 
    [ 5.000,  7.500) = 1418 
    [ 7.500, 10.000) = 1567 
    [10.000, 12.500) = 450 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      7.946 ms/op
     p(90.0000) =     11.474 ms/op
     p(95.0000) =     12.911 ms/op
     p(99.0000) =     16.134 ms/op
     p(99.9000) =     19.361 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.864          ops/ms
Client.existUser                       thrpt         13.672          ops/ms
Client.getUser                         thrpt          9.615          ops/ms
Client.listUser                        thrpt          3.887          ops/ms
Client.createUser                       avgt          2.807           ms/op
Client.existUser                        avgt          1.945           ms/op
Client.getUser                          avgt          2.967           ms/op
Client.listUser                         avgt          8.552           ms/op
Client.createUser                     sample  10485   3.049 ± 0.068   ms/op
Client.createUser:createUser·p0.00    sample          1.180           ms/op
Client.createUser:createUser·p0.50    sample          2.691           ms/op
Client.createUser:createUser·p0.90    sample          3.674           ms/op
Client.createUser:createUser·p0.95    sample          4.413           ms/op
Client.createUser:createUser·p0.99    sample         10.863           ms/op
Client.createUser:createUser·p0.999   sample         32.244           ms/op
Client.createUser:createUser·p0.9999  sample         33.517           ms/op
Client.createUser:createUser·p1.00    sample         33.522           ms/op
Client.existUser                      sample  15043   2.130 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.640           ms/op
Client.existUser:existUser·p0.50      sample          2.091           ms/op
Client.existUser:existUser·p0.90      sample          2.642           ms/op
Client.existUser:existUser·p0.95      sample          2.826           ms/op
Client.existUser:existUser·p0.99      sample          3.844           ms/op
Client.existUser:existUser·p0.999     sample          5.194           ms/op
Client.existUser:existUser·p0.9999    sample          5.595           ms/op
Client.existUser:existUser·p1.00      sample          5.612           ms/op
Client.getUser                        sample   9841   3.256 ± 0.042   ms/op
Client.getUser:getUser·p0.00          sample          0.840           ms/op
Client.getUser:getUser·p0.50          sample          3.166           ms/op
Client.getUser:getUser·p0.90          sample          3.879           ms/op
Client.getUser:getUser·p0.95          sample          4.268           ms/op
Client.getUser:getUser·p0.99          sample          6.231           ms/op
Client.getUser:getUser·p0.999         sample         21.660           ms/op
Client.getUser:getUser·p0.9999        sample         21.823           ms/op
Client.getUser:getUser·p1.00          sample         21.823           ms/op
Client.listUser                       sample   3856   8.286 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          2.253           ms/op
Client.listUser:listUser·p0.50        sample          7.946           ms/op
Client.listUser:listUser·p0.90        sample         11.474           ms/op
Client.listUser:listUser·p0.95        sample         12.911           ms/op
Client.listUser:listUser·p0.99        sample         16.134           ms/op
Client.listUser:listUser·p0.999       sample         19.361           ms/op
Client.listUser:listUser·p0.9999      sample         21.889           ms/op
Client.listUser:listUser·p1.00        sample         21.889           ms/op
