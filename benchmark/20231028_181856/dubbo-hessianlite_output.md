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
# Warmup Iteration   1: 1.463 ops/ms
Iteration   1: 3.910 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.910 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 3.668 ops/ms
Iteration   1: 6.394 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.394 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.705 ops/ms
Iteration   1: 5.060 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.060 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.193 ops/ms
Iteration   1: 1.657 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.657 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 11.717 ±(99.9%) 0.494 ms/op
Iteration   1: 6.969 ±(99.9%) 0.103 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.969 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.267 ±(99.9%) 0.089 ms/op
Iteration   1: 2.506 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.506 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.058 ±(99.9%) 0.147 ms/op
Iteration   1: 4.884 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.884 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 23.795 ±(99.9%) 0.508 ms/op
Iteration   1: 17.836 ±(99.9%) 0.151 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.836 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.407 ±(99.9%) 0.228 ms/op
Iteration   1: 3.509 ±(99.9%) 0.069 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   2.748 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   13.679 ms/op
                 createUser·p0.999:  17.954 ms/op
                 createUser·p0.9999: 18.809 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9101
  mean =      3.509 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1208 
    [ 2.500,  3.750) = 5899 
    [ 3.750,  5.000) = 885 
    [ 5.000,  6.250) = 469 
    [ 6.250,  7.500) = 195 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 126 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      7.438 ms/op
     p(99.0000) =     13.679 ms/op
     p(99.9000) =     17.954 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.177 ±(99.9%) 0.188 ms/op
Iteration   1: 2.353 ±(99.9%) 0.058 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   10.584 ms/op
                 existUser·p0.999:  26.575 ms/op
                 existUser·p0.9999: 31.013 ms/op
                 existUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13890
  mean =      2.353 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11395 
    [ 2.500,  5.000) = 1694 
    [ 5.000,  7.500) = 510 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     26.575 ms/op
     p(99.9900) =     31.013 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 7.724 ±(99.9%) 0.207 ms/op
Iteration   1: 3.823 ±(99.9%) 0.092 ms/op
                 getUser·p0.00:   1.636 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   11.126 ms/op
                 getUser·p0.999:  39.602 ms/op
                 getUser·p0.9999: 39.846 ms/op
                 getUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8363
  mean =      3.823 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 7482 
    [ 5.000,  7.500) = 519 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.636 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =     11.126 ms/op
     p(99.9000) =     39.602 ms/op
     p(99.9900) =     39.846 ms/op
     p(99.9990) =     39.846 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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
# Warmup Iteration   1: 24.511 ±(99.9%) 1.014 ms/op
Iteration   1: 13.597 ±(99.9%) 0.275 ms/op
                 listUser·p0.00:   6.038 ms/op
                 listUser·p0.50:   12.894 ms/op
                 listUser·p0.90:   18.022 ms/op
                 listUser·p0.95:   19.694 ms/op
                 listUser·p0.99:   29.157 ms/op
                 listUser·p0.999:  40.239 ms/op
                 listUser·p0.9999: 40.305 ms/op
                 listUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2336
  mean =     13.597 ±(99.9%) 0.275 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 340 
    [10.000, 15.000) = 1337 
    [15.000, 20.000) = 554 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      6.038 ms/op
     p(50.0000) =     12.894 ms/op
     p(90.0000) =     18.022 ms/op
     p(95.0000) =     19.694 ms/op
     p(99.0000) =     29.157 ms/op
     p(99.9000) =     40.239 ms/op
     p(99.9900) =     40.305 ms/op
     p(99.9990) =     40.305 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.910          ops/ms
Client.existUser                       thrpt          6.394          ops/ms
Client.getUser                         thrpt          5.060          ops/ms
Client.listUser                        thrpt          1.657          ops/ms
Client.createUser                       avgt          6.969           ms/op
Client.existUser                        avgt          2.506           ms/op
Client.getUser                          avgt          4.884           ms/op
Client.listUser                         avgt         17.836           ms/op
Client.createUser                     sample   9101   3.509 ± 0.069   ms/op
Client.createUser:createUser·p0.00    sample          1.495           ms/op
Client.createUser:createUser·p0.50    sample          2.748           ms/op
Client.createUser:createUser·p0.90    sample          5.480           ms/op
Client.createUser:createUser·p0.95    sample          7.438           ms/op
Client.createUser:createUser·p0.99    sample         13.679           ms/op
Client.createUser:createUser·p0.999   sample         17.954           ms/op
Client.createUser:createUser·p0.9999  sample         18.809           ms/op
Client.createUser:createUser·p1.00    sample         18.809           ms/op
Client.existUser                      sample  13890   2.353 ± 0.058   ms/op
Client.existUser:existUser·p0.00      sample          0.509           ms/op
Client.existUser:existUser·p0.50      sample          1.833           ms/op
Client.existUser:existUser·p0.90      sample          3.412           ms/op
Client.existUser:existUser·p0.95      sample          5.276           ms/op
Client.existUser:existUser·p0.99      sample         10.584           ms/op
Client.existUser:existUser·p0.999     sample         26.575           ms/op
Client.existUser:existUser·p0.9999    sample         31.013           ms/op
Client.existUser:existUser·p1.00      sample         31.293           ms/op
Client.getUser                        sample   8363   3.823 ± 0.092   ms/op
Client.getUser:getUser·p0.00          sample          1.636           ms/op
Client.getUser:getUser·p0.50          sample          3.301           ms/op
Client.getUser:getUser·p0.90          sample          4.866           ms/op
Client.getUser:getUser·p0.95          sample          5.825           ms/op
Client.getUser:getUser·p0.99          sample         11.126           ms/op
Client.getUser:getUser·p0.999         sample         39.602           ms/op
Client.getUser:getUser·p0.9999        sample         39.846           ms/op
Client.getUser:getUser·p1.00          sample         39.846           ms/op
Client.listUser                       sample   2336  13.597 ± 0.275   ms/op
Client.listUser:listUser·p0.00        sample          6.038           ms/op
Client.listUser:listUser·p0.50        sample         12.894           ms/op
Client.listUser:listUser·p0.90        sample         18.022           ms/op
Client.listUser:listUser·p0.95        sample         19.694           ms/op
Client.listUser:listUser·p0.99        sample         29.157           ms/op
Client.listUser:listUser·p0.999       sample         40.239           ms/op
Client.listUser:listUser·p0.9999      sample         40.305           ms/op
Client.listUser:listUser·p1.00        sample         40.305           ms/op
