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
# Warmup Iteration   1: 1.057 ops/ms
Iteration   1: 2.626 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.626 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ops/ms
Iteration   1: 6.985 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.985 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.288 ops/ms
Iteration   1: 5.531 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.531 ops/ms


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
# Warmup Iteration   1: 0.998 ops/ms
Iteration   1: 1.425 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.425 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 14.961 ±(99.9%) 0.229 ms/op
Iteration   1: 6.700 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.700 ms/op


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
# Warmup Iteration   1: 7.404 ±(99.9%) 0.077 ms/op
Iteration   1: 3.239 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.239 ms/op


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
# Warmup Iteration   1: 9.481 ±(99.9%) 0.121 ms/op
Iteration   1: 4.887 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.887 ms/op


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
# Warmup Iteration   1: 25.563 ±(99.9%) 0.464 ms/op
Iteration   1: 18.293 ±(99.9%) 0.130 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.293 ms/op


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
# Warmup Iteration   1: 10.343 ±(99.9%) 0.343 ms/op
Iteration   1: 6.385 ±(99.9%) 0.104 ms/op
                 createUser·p0.00:   3.162 ms/op
                 createUser·p0.50:   5.841 ms/op
                 createUser·p0.90:   6.655 ms/op
                 createUser·p0.95:   11.005 ms/op
                 createUser·p0.99:   15.598 ms/op
                 createUser·p0.999:  24.740 ms/op
                 createUser·p0.9999: 26.509 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5085
  mean =      6.385 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 15 
    [ 5.000,  7.500) = 4708 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      3.162 ms/op
     p(50.0000) =      5.841 ms/op
     p(90.0000) =      6.655 ms/op
     p(95.0000) =     11.005 ms/op
     p(99.0000) =     15.598 ms/op
     p(99.9000) =     24.740 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 6.114 ±(99.9%) 0.197 ms/op
Iteration   1: 3.031 ±(99.9%) 0.051 ms/op
                 existUser·p0.00:   0.258 ms/op
                 existUser·p0.50:   2.781 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   9.437 ms/op
                 existUser·p0.999:  25.520 ms/op
                 existUser·p0.9999: 26.079 ms/op
                 existUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10594
  mean =      3.031 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4661 
    [ 2.500,  5.000) = 5624 
    [ 5.000,  7.500) = 114 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.258 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     25.520 ms/op
     p(99.9900) =     26.079 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 7.894 ±(99.9%) 0.316 ms/op
Iteration   1: 4.699 ±(99.9%) 0.068 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   4.751 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  24.248 ms/op
                 getUser·p0.9999: 24.936 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6831
  mean =      4.699 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 5030 
    [ 5.000,  7.500) = 1601 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     24.248 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 28.512 ±(99.9%) 1.064 ms/op
Iteration   1: 13.588 ±(99.9%) 0.267 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   11.813 ms/op
                 listUser·p0.90:   17.960 ms/op
                 listUser·p0.95:   22.322 ms/op
                 listUser·p0.99:   29.203 ms/op
                 listUser·p0.999:  38.115 ms/op
                 listUser·p0.9999: 40.698 ms/op
                 listUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2378
  mean =     13.588 ±(99.9%) 0.267 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3 
    [ 5.000, 10.000) = 17 
    [10.000, 15.000) = 1905 
    [15.000, 20.000) = 269 
    [20.000, 25.000) = 120 
    [25.000, 30.000) = 44 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =     11.813 ms/op
     p(90.0000) =     17.960 ms/op
     p(95.0000) =     22.322 ms/op
     p(99.0000) =     29.203 ms/op
     p(99.9000) =     38.115 ms/op
     p(99.9900) =     40.698 ms/op
     p(99.9990) =     40.698 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.626          ops/ms
Client.existUser                       thrpt          6.985          ops/ms
Client.getUser                         thrpt          5.531          ops/ms
Client.listUser                        thrpt          1.425          ops/ms
Client.createUser                       avgt          6.700           ms/op
Client.existUser                        avgt          3.239           ms/op
Client.getUser                          avgt          4.887           ms/op
Client.listUser                         avgt         18.293           ms/op
Client.createUser                     sample   5085   6.385 ± 0.104   ms/op
Client.createUser:createUser·p0.00    sample          3.162           ms/op
Client.createUser:createUser·p0.50    sample          5.841           ms/op
Client.createUser:createUser·p0.90    sample          6.655           ms/op
Client.createUser:createUser·p0.95    sample         11.005           ms/op
Client.createUser:createUser·p0.99    sample         15.598           ms/op
Client.createUser:createUser·p0.999   sample         24.740           ms/op
Client.createUser:createUser·p0.9999  sample         26.509           ms/op
Client.createUser:createUser·p1.00    sample         26.509           ms/op
Client.existUser                      sample  10594   3.031 ± 0.051   ms/op
Client.existUser:existUser·p0.00      sample          0.258           ms/op
Client.existUser:existUser·p0.50      sample          2.781           ms/op
Client.existUser:existUser·p0.90      sample          3.674           ms/op
Client.existUser:existUser·p0.95      sample          3.961           ms/op
Client.existUser:existUser·p0.99      sample          9.437           ms/op
Client.existUser:existUser·p0.999     sample         25.520           ms/op
Client.existUser:existUser·p0.9999    sample         26.079           ms/op
Client.existUser:existUser·p1.00      sample         26.083           ms/op
Client.getUser                        sample   6831   4.699 ± 0.068   ms/op
Client.getUser:getUser·p0.00          sample          1.167           ms/op
Client.getUser:getUser·p0.50          sample          4.751           ms/op
Client.getUser:getUser·p0.90          sample          5.415           ms/op
Client.getUser:getUser·p0.95          sample          5.956           ms/op
Client.getUser:getUser·p0.99          sample          9.372           ms/op
Client.getUser:getUser·p0.999         sample         24.248           ms/op
Client.getUser:getUser·p0.9999        sample         24.936           ms/op
Client.getUser:getUser·p1.00          sample         24.936           ms/op
Client.listUser                       sample   2378  13.588 ± 0.267   ms/op
Client.listUser:listUser·p0.00        sample          2.314           ms/op
Client.listUser:listUser·p0.50        sample         11.813           ms/op
Client.listUser:listUser·p0.90        sample         17.960           ms/op
Client.listUser:listUser·p0.95        sample         22.322           ms/op
Client.listUser:listUser·p0.99        sample         29.203           ms/op
Client.listUser:listUser·p0.999       sample         38.115           ms/op
Client.listUser:listUser·p0.9999      sample         40.698           ms/op
Client.listUser:listUser·p1.00        sample         40.698           ms/op
