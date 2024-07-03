# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.926 ops/ms
Iteration   1: 6.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.551 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.142 ops/ms
Iteration   1: 13.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.903 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.171 ops/ms
Iteration   1: 12.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.675 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.409 ops/ms
Iteration   1: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.033 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.950 ±(99.9%) 0.083 ms/op
Iteration   1: 2.140 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.140 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.474 ±(99.9%) 0.085 ms/op
Iteration   1: 1.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.937 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.602 ±(99.9%) 0.065 ms/op
Iteration   1: 2.154 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.154 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.449 ±(99.9%) 0.120 ms/op
Iteration   1: 3.232 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.232 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.878 ±(99.9%) 0.089 ms/op
Iteration   1: 2.235 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.052 ms/op
                 createUser·p0.90:   2.683 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   6.120 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 19.740 ms/op
                 createUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14292
  mean =      2.235 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12003 
    [ 2.500,  5.000) = 2053 
    [ 5.000,  7.500) = 140 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      6.120 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     19.740 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.050 ±(99.9%) 0.076 ms/op
Iteration   1: 1.948 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   1.894 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  21.894 ms/op
                 existUser·p0.9999: 22.519 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16420
  mean =      1.948 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15637 
    [ 2.500,  5.000) = 711 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =     21.894 ms/op
     p(99.9900) =     22.519 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.143 ±(99.9%) 0.081 ms/op
Iteration   1: 2.178 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.097 ms/op
                 getUser·p0.90:   2.777 ms/op
                 getUser·p0.95:   3.093 ms/op
                 getUser·p0.99:   5.048 ms/op
                 getUser·p0.999:  13.271 ms/op
                 getUser·p0.9999: 13.584 ms/op
                 getUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14675
  mean =      2.178 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 896 
    [ 1.250,  2.500) = 10292 
    [ 2.500,  3.750) = 3078 
    [ 3.750,  5.000) = 260 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      3.093 ms/op
     p(99.0000) =      5.048 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     13.584 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.970 ±(99.9%) 0.160 ms/op
Iteration   1: 3.234 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   3.072 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.194 ms/op
                 listUser·p0.999:  9.071 ms/op
                 listUser·p0.9999: 12.059 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9881
  mean =      3.234 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 391 
    [ 2.500,  3.750) = 7901 
    [ 3.750,  5.000) = 1444 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =      9.071 ms/op
     p(99.9900) =     12.059 ms/op
     p(99.9990) =     12.059 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.551          ops/ms
ClientSimple.existUser                       thrpt         13.903          ops/ms
ClientSimple.getUser                         thrpt         12.675          ops/ms
ClientSimple.listUser                        thrpt          8.033          ops/ms
ClientSimple.createUser                       avgt          2.140           ms/op
ClientSimple.existUser                        avgt          1.937           ms/op
ClientSimple.getUser                          avgt          2.154           ms/op
ClientSimple.listUser                         avgt          3.232           ms/op
ClientSimple.createUser                     sample  14292   2.235 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.108           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.052           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.117           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.120           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.202           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.740           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.021           ms/op
ClientSimple.existUser                      sample  16420   1.948 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.527           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.894           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.523           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.894           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.519           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.708           ms/op
ClientSimple.getUser                        sample  14675   2.178 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.579           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.097           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.093           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.048           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.271           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.584           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.730           ms/op
ClientSimple.listUser                       sample   9881   3.234 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.999           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.072           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.994           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.194           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.071           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.059           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.059           ms/op

Benchmark result is saved to 1719965778366.json
