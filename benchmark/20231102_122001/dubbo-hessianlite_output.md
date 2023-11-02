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
# Warmup Iteration   1: 1.237 ops/ms
Iteration   1: 3.676 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.676 ops/ms


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
# Warmup Iteration   1: 3.699 ops/ms
Iteration   1: 9.438 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.438 ops/ms


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
# Warmup Iteration   1: 2.397 ops/ms
Iteration   1: 4.168 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.168 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 0.826 ops/ms
Iteration   1: 1.404 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.404 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 11.134 ±(99.9%) 0.301 ms/op
Iteration   1: 6.418 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.418 ms/op


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
# Warmup Iteration   1: 6.770 ±(99.9%) 0.111 ms/op
Iteration   1: 2.773 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.773 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.461 ±(99.9%) 0.172 ms/op
Iteration   1: 5.174 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.174 ms/op


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
# Warmup Iteration   1: 27.321 ±(99.9%) 0.811 ms/op
Iteration   1: 16.403 ±(99.9%) 0.194 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.403 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.913 ±(99.9%) 0.261 ms/op
Iteration   1: 3.564 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   5.299 ms/op
                 createUser·p0.95:   6.808 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  17.629 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8971
  mean =      3.564 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 305 
    [ 2.500,  3.750) = 6769 
    [ 3.750,  5.000) = 901 
    [ 5.000,  6.250) = 429 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      5.299 ms/op
     p(95.0000) =      6.808 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.946 ±(99.9%) 0.161 ms/op
Iteration   1: 2.398 ±(99.9%) 0.065 ms/op
                 existUser·p0.00:   0.381 ms/op
                 existUser·p0.50:   1.776 ms/op
                 existUser·p0.90:   3.677 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  34.188 ms/op
                 existUser·p0.9999: 34.800 ms/op
                 existUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13332
  mean =      2.398 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11201 
    [ 2.500,  5.000) = 1265 
    [ 5.000,  7.500) = 445 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      3.677 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     34.188 ms/op
     p(99.9900) =     34.800 ms/op
     p(99.9990) =     34.800 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 8.641 ±(99.9%) 0.255 ms/op
Iteration   1: 3.482 ±(99.9%) 0.070 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   6.996 ms/op
                 getUser·p0.99:   13.945 ms/op
                 getUser·p0.999:  19.360 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9183
  mean =      3.482 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1505 
    [ 2.500,  3.750) = 6013 
    [ 3.750,  5.000) = 850 
    [ 5.000,  6.250) = 271 
    [ 6.250,  7.500) = 129 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =     13.945 ms/op
     p(99.9000) =     19.360 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 23.427 ±(99.9%) 0.939 ms/op
Iteration   1: 13.990 ±(99.9%) 0.342 ms/op
                 listUser·p0.00:   4.637 ms/op
                 listUser·p0.50:   12.796 ms/op
                 listUser·p0.90:   20.385 ms/op
                 listUser·p0.95:   23.298 ms/op
                 listUser·p0.99:   33.388 ms/op
                 listUser·p0.999:  42.658 ms/op
                 listUser·p0.9999: 44.368 ms/op
                 listUser·p1.00:   44.368 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2408
  mean =     13.990 ±(99.9%) 0.342 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1 
    [ 5.000, 10.000) = 411 
    [10.000, 15.000) = 1236 
    [15.000, 20.000) = 493 
    [20.000, 25.000) = 185 
    [25.000, 30.000) = 39 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      4.637 ms/op
     p(50.0000) =     12.796 ms/op
     p(90.0000) =     20.385 ms/op
     p(95.0000) =     23.298 ms/op
     p(99.0000) =     33.388 ms/op
     p(99.9000) =     42.658 ms/op
     p(99.9900) =     44.368 ms/op
     p(99.9990) =     44.368 ms/op
     p(99.9999) =     44.368 ms/op
    p(100.0000) =     44.368 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.676          ops/ms
Client.existUser                       thrpt          9.438          ops/ms
Client.getUser                         thrpt          4.168          ops/ms
Client.listUser                        thrpt          1.404          ops/ms
Client.createUser                       avgt          6.418           ms/op
Client.existUser                        avgt          2.773           ms/op
Client.getUser                          avgt          5.174           ms/op
Client.listUser                         avgt         16.403           ms/op
Client.createUser                     sample   8971   3.564 ± 0.060   ms/op
Client.createUser:createUser·p0.00    sample          1.096           ms/op
Client.createUser:createUser·p0.50    sample          2.978           ms/op
Client.createUser:createUser·p0.90    sample          5.299           ms/op
Client.createUser:createUser·p0.95    sample          6.808           ms/op
Client.createUser:createUser·p0.99    sample         11.256           ms/op
Client.createUser:createUser·p0.999   sample         17.629           ms/op
Client.createUser:createUser·p0.9999  sample         17.629           ms/op
Client.createUser:createUser·p1.00    sample         17.629           ms/op
Client.existUser                      sample  13332   2.398 ± 0.065   ms/op
Client.existUser:existUser·p0.00      sample          0.381           ms/op
Client.existUser:existUser·p0.50      sample          1.776           ms/op
Client.existUser:existUser·p0.90      sample          3.677           ms/op
Client.existUser:existUser·p0.95      sample          5.849           ms/op
Client.existUser:existUser·p0.99      sample         10.420           ms/op
Client.existUser:existUser·p0.999     sample         34.188           ms/op
Client.existUser:existUser·p0.9999    sample         34.800           ms/op
Client.existUser:existUser·p1.00      sample         34.800           ms/op
Client.getUser                        sample   9183   3.482 ± 0.070   ms/op
Client.getUser:getUser·p0.00          sample          0.907           ms/op
Client.getUser:getUser·p0.50          sample          2.994           ms/op
Client.getUser:getUser·p0.90          sample          4.751           ms/op
Client.getUser:getUser·p0.95          sample          6.996           ms/op
Client.getUser:getUser·p0.99          sample         13.945           ms/op
Client.getUser:getUser·p0.999         sample         19.360           ms/op
Client.getUser:getUser·p0.9999        sample         19.562           ms/op
Client.getUser:getUser·p1.00          sample         19.562           ms/op
Client.listUser                       sample   2408  13.990 ± 0.342   ms/op
Client.listUser:listUser·p0.00        sample          4.637           ms/op
Client.listUser:listUser·p0.50        sample         12.796           ms/op
Client.listUser:listUser·p0.90        sample         20.385           ms/op
Client.listUser:listUser·p0.95        sample         23.298           ms/op
Client.listUser:listUser·p0.99        sample         33.388           ms/op
Client.listUser:listUser·p0.999       sample         42.658           ms/op
Client.listUser:listUser·p0.9999      sample         44.368           ms/op
Client.listUser:listUser·p1.00        sample         44.368           ms/op
