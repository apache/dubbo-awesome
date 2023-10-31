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
# Warmup Iteration   1: 1.659 ops/ms
Iteration   1: 4.257 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.257 ops/ms


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
# Warmup Iteration   1: 3.741 ops/ms
Iteration   1: 11.718 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.718 ops/ms


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
# Warmup Iteration   1: 2.815 ops/ms
Iteration   1: 4.703 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.703 ops/ms


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
# Warmup Iteration   1: 1.028 ops/ms
Iteration   1: 1.700 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.700 ops/ms


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
# Warmup Iteration   1: 10.391 ±(99.9%) 0.194 ms/op
Iteration   1: 4.841 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.841 ms/op


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
# Warmup Iteration   1: 6.629 ±(99.9%) 0.081 ms/op
Iteration   1: 2.728 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.728 ms/op


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
# Warmup Iteration   1: 11.188 ±(99.9%) 0.167 ms/op
Iteration   1: 4.669 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.669 ms/op


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
# Warmup Iteration   1: 26.170 ±(99.9%) 0.939 ms/op
Iteration   1: 16.448 ±(99.9%) 0.272 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.448 ms/op


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
# Warmup Iteration   1: 9.445 ±(99.9%) 0.293 ms/op
Iteration   1: 3.845 ±(99.9%) 0.079 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.480 ms/op
                 createUser·p0.99:   13.368 ms/op
                 createUser·p0.999:  23.223 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8303
  mean =      3.845 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 522 
    [ 2.500,  5.000) = 6432 
    [ 5.000,  7.500) = 1056 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.480 ms/op
     p(99.0000) =     13.368 ms/op
     p(99.9000) =     23.223 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 6.831 ±(99.9%) 0.233 ms/op
Iteration   1: 2.355 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   1.855 ms/op
                 existUser·p0.90:   3.515 ms/op
                 existUser·p0.95:   4.952 ms/op
                 existUser·p0.99:   8.618 ms/op
                 existUser·p0.999:  20.094 ms/op
                 existUser·p0.9999: 20.672 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13788
  mean =      2.355 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10851 
    [ 2.500,  5.000) = 2255 
    [ 5.000,  7.500) = 338 
    [ 7.500, 10.000) = 301 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      3.515 ms/op
     p(95.0000) =      4.952 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     20.094 ms/op
     p(99.9900) =     20.672 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 8.297 ±(99.9%) 0.308 ms/op
Iteration   1: 3.382 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   10.519 ms/op
                 getUser·p0.999:  18.317 ms/op
                 getUser·p0.9999: 19.726 ms/op
                 getUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9447
  mean =      3.382 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 746 
    [ 2.500,  3.750) = 6608 
    [ 3.750,  5.000) = 1488 
    [ 5.000,  6.250) = 271 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 22.529 ±(99.9%) 0.944 ms/op
Iteration   1: 14.121 ±(99.9%) 0.258 ms/op
                 listUser·p0.00:   5.161 ms/op
                 listUser·p0.50:   13.746 ms/op
                 listUser·p0.90:   18.743 ms/op
                 listUser·p0.95:   21.530 ms/op
                 listUser·p0.99:   25.409 ms/op
                 listUser·p0.999:  34.559 ms/op
                 listUser·p0.9999: 36.241 ms/op
                 listUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2258
  mean =     14.121 ±(99.9%) 0.258 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 521 
    [12.500, 15.000) = 688 
    [15.000, 17.500) = 462 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      5.161 ms/op
     p(50.0000) =     13.746 ms/op
     p(90.0000) =     18.743 ms/op
     p(95.0000) =     21.530 ms/op
     p(99.0000) =     25.409 ms/op
     p(99.9000) =     34.559 ms/op
     p(99.9900) =     36.241 ms/op
     p(99.9990) =     36.241 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.257          ops/ms
Client.existUser                       thrpt         11.718          ops/ms
Client.getUser                         thrpt          4.703          ops/ms
Client.listUser                        thrpt          1.700          ops/ms
Client.createUser                       avgt          4.841           ms/op
Client.existUser                        avgt          2.728           ms/op
Client.getUser                          avgt          4.669           ms/op
Client.listUser                         avgt         16.448           ms/op
Client.createUser                     sample   8303   3.845 ± 0.079   ms/op
Client.createUser:createUser·p0.00    sample          1.305           ms/op
Client.createUser:createUser·p0.50    sample          3.142           ms/op
Client.createUser:createUser·p0.90    sample          5.693           ms/op
Client.createUser:createUser·p0.95    sample          6.480           ms/op
Client.createUser:createUser·p0.99    sample         13.368           ms/op
Client.createUser:createUser·p0.999   sample         23.223           ms/op
Client.createUser:createUser·p0.9999  sample         25.002           ms/op
Client.createUser:createUser·p1.00    sample         25.002           ms/op
Client.existUser                      sample  13788   2.355 ± 0.044   ms/op
Client.existUser:existUser·p0.00      sample          0.755           ms/op
Client.existUser:existUser·p0.50      sample          1.855           ms/op
Client.existUser:existUser·p0.90      sample          3.515           ms/op
Client.existUser:existUser·p0.95      sample          4.952           ms/op
Client.existUser:existUser·p0.99      sample          8.618           ms/op
Client.existUser:existUser·p0.999     sample         20.094           ms/op
Client.existUser:existUser·p0.9999    sample         20.672           ms/op
Client.existUser:existUser·p1.00      sample         20.709           ms/op
Client.getUser                        sample   9447   3.382 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample          0.691           ms/op
Client.getUser:getUser·p0.50          sample          2.961           ms/op
Client.getUser:getUser·p0.90          sample          4.342           ms/op
Client.getUser:getUser·p0.95          sample          5.628           ms/op
Client.getUser:getUser·p0.99          sample         10.519           ms/op
Client.getUser:getUser·p0.999         sample         18.317           ms/op
Client.getUser:getUser·p0.9999        sample         19.726           ms/op
Client.getUser:getUser·p1.00          sample         19.726           ms/op
Client.listUser                       sample   2258  14.121 ± 0.258   ms/op
Client.listUser:listUser·p0.00        sample          5.161           ms/op
Client.listUser:listUser·p0.50        sample         13.746           ms/op
Client.listUser:listUser·p0.90        sample         18.743           ms/op
Client.listUser:listUser·p0.95        sample         21.530           ms/op
Client.listUser:listUser·p0.99        sample         25.409           ms/op
Client.listUser:listUser·p0.999       sample         34.559           ms/op
Client.listUser:listUser·p0.9999      sample         36.241           ms/op
Client.listUser:listUser·p1.00        sample         36.241           ms/op
