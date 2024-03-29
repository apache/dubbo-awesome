# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.711 ops/ms
Iteration   1: 6.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.168 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.479 ops/ms
Iteration   1: 13.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.125 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.586 ops/ms
Iteration   1: 11.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.958 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ops/ms
Iteration   1: 8.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.453 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ±(99.9%) 0.073 ms/op
Iteration   1: 2.036 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.036 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.290 ±(99.9%) 0.060 ms/op
Iteration   1: 2.021 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.021 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.598 ±(99.9%) 0.064 ms/op
Iteration   1: 1.990 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.206 ±(99.9%) 0.155 ms/op
Iteration   1: 3.907 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.595 ±(99.9%) 0.102 ms/op
Iteration   1: 2.008 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   1.669 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.810 ms/op
                 createUser·p0.99:   8.248 ms/op
                 createUser·p0.999:  43.647 ms/op
                 createUser·p0.9999: 44.395 ms/op
                 createUser·p1.00:   44.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15919
  mean =      2.008 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15580 
    [ 5.000, 10.000) = 263 
    [10.000, 15.000) = 31 
    [15.000, 20.000) = 13 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      8.248 ms/op
     p(99.9000) =     43.647 ms/op
     p(99.9900) =     44.395 ms/op
     p(99.9990) =     44.433 ms/op
     p(99.9999) =     44.433 ms/op
    p(100.0000) =     44.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ±(99.9%) 0.076 ms/op
Iteration   1: 1.979 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   1.862 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  13.894 ms/op
                 existUser·p0.9999: 15.020 ms/op
                 existUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16532
  mean =      1.979 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 437 
    [ 1.250,  2.500) = 14614 
    [ 2.500,  3.750) = 1331 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     15.020 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.545 ±(99.9%) 0.102 ms/op
Iteration   1: 1.957 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   1.812 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.626 ms/op
                 getUser·p0.99:   5.528 ms/op
                 getUser·p0.999:  19.060 ms/op
                 getUser·p0.9999: 19.745 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16340
  mean =      1.957 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 418 
    [ 1.250,  2.500) = 14658 
    [ 2.500,  3.750) = 1044 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      5.528 ms/op
     p(99.9000) =     19.060 ms/op
     p(99.9900) =     19.745 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.139 ms/op
Iteration   1: 3.233 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  16.781 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9892
  mean =      3.233 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 827 
    [ 2.500,  3.750) = 7276 
    [ 3.750,  5.000) = 1611 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     16.781 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.168          ops/ms
ClientSimple.existUser                       thrpt         13.125          ops/ms
ClientSimple.getUser                         thrpt         11.958          ops/ms
ClientSimple.listUser                        thrpt          8.453          ops/ms
ClientSimple.createUser                       avgt          2.036           ms/op
ClientSimple.existUser                        avgt          2.021           ms/op
ClientSimple.getUser                          avgt          1.990           ms/op
ClientSimple.listUser                         avgt          3.907           ms/op
ClientSimple.createUser                     sample  15919   2.008 ± 0.056   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.610           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.669           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.248           ms/op
ClientSimple.createUser:createUser·p0.999   sample         43.647           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         44.395           ms/op
ClientSimple.createUser:createUser·p1.00    sample         44.433           ms/op
ClientSimple.existUser                      sample  16532   1.979 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.603           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.862           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.580           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.894           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.020           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.106           ms/op
ClientSimple.getUser                        sample  16340   1.957 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.626           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.812           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.528           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.060           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.745           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.890           ms/op
ClientSimple.listUser                       sample   9892   3.233 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.169           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.937           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.603           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.781           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.252           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.252           ms/op

Benchmark result is saved to 1711692315012.json
