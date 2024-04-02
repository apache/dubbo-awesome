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
# Warmup Iteration   1: 2.010 ops/ms
Iteration   1: 7.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.348 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.081 ops/ms
Iteration   1: 11.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.508 ops/ms


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
# Warmup Iteration   1: 5.424 ops/ms
Iteration   1: 13.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.824 ops/ms


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
# Warmup Iteration   1: 5.912 ops/ms
Iteration   1: 8.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.895 ops/ms


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.069 ms/op
Iteration   1: 2.315 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.315 ms/op


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
# Warmup Iteration   1: 3.058 ±(99.9%) 0.056 ms/op
Iteration   1: 1.936 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.936 ms/op


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.051 ms/op
Iteration   1: 2.105 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.105 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.289 ±(99.9%) 0.127 ms/op
Iteration   1: 3.636 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.636 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ±(99.9%) 0.110 ms/op
Iteration   1: 2.363 ±(99.9%) 0.072 ms/op
                 createUser·p0.00:   0.425 ms/op
                 createUser·p0.50:   1.898 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   8.247 ms/op
                 createUser·p0.999:  50.659 ms/op
                 createUser·p0.9999: 52.051 ms/op
                 createUser·p1.00:   52.167 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13525
  mean =      2.363 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13177 
    [ 5.000, 10.000) = 247 
    [10.000, 15.000) = 69 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 5 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.396 ms/op
     p(99.0000) =      8.247 ms/op
     p(99.9000) =     50.659 ms/op
     p(99.9900) =     52.051 ms/op
     p(99.9990) =     52.167 ms/op
     p(99.9999) =     52.167 ms/op
    p(100.0000) =     52.167 ms/op


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.347 ms/op
Iteration   1: 2.031 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  17.459 ms/op
                 existUser·p0.9999: 17.807 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15730
  mean =      2.031 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 14543 
    [ 2.500,  3.750) = 957 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =     17.459 ms/op
     p(99.9900) =     17.807 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 3.034 ±(99.9%) 0.075 ms/op
Iteration   1: 2.010 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.233 ms/op
                 getUser·p0.50:   1.923 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   3.147 ms/op
                 getUser·p0.999:  11.502 ms/op
                 getUser·p0.9999: 11.852 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15978
  mean =      2.010 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 334 
    [ 1.250,  2.500) = 13114 
    [ 2.500,  3.750) = 2461 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.233 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.147 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     11.852 ms/op
     p(99.9990) =     11.911 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


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
# Warmup Iteration   1: 4.632 ±(99.9%) 0.145 ms/op
Iteration   1: 3.571 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.820 ms/op
                 listUser·p0.999:  11.043 ms/op
                 listUser·p0.9999: 11.190 ms/op
                 listUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9076
  mean =      3.571 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 607 
    [ 2.500,  3.750) = 5394 
    [ 3.750,  5.000) = 2843 
    [ 5.000,  6.250) = 148 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.820 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     11.190 ms/op
     p(99.9990) =     11.190 ms/op
     p(99.9999) =     11.190 ms/op
    p(100.0000) =     11.190 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.348          ops/ms
ClientSimple.existUser                       thrpt         11.508          ops/ms
ClientSimple.getUser                         thrpt         13.824          ops/ms
ClientSimple.listUser                        thrpt          8.895          ops/ms
ClientSimple.createUser                       avgt          2.315           ms/op
ClientSimple.existUser                        avgt          1.936           ms/op
ClientSimple.getUser                          avgt          2.105           ms/op
ClientSimple.listUser                         avgt          3.636           ms/op
ClientSimple.createUser                     sample  13525   2.363 ± 0.072   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.425           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.898           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.396           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.247           ms/op
ClientSimple.createUser:createUser·p0.999   sample         50.659           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         52.051           ms/op
ClientSimple.createUser:createUser·p1.00    sample         52.167           ms/op
ClientSimple.existUser                      sample  15730   2.031 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.865           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.923           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.854           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.459           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.807           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.826           ms/op
ClientSimple.getUser                        sample  15978   2.010 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.233           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.923           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.147           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.502           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.852           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.911           ms/op
ClientSimple.listUser                       sample   9076   3.571 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.971           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.820           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.043           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.190           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.190           ms/op

Benchmark result is saved to 1712081100381.json
