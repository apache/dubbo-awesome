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
# Warmup Iteration   1: 1.415 ops/ms
Iteration   1: 6.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.514 ops/ms


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
# Warmup Iteration   1: 5.739 ops/ms
Iteration   1: 11.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.133 ops/ms


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
# Warmup Iteration   1: 4.227 ops/ms
Iteration   1: 10.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.793 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ops/ms
Iteration   1: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.007 ops/ms


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.076 ms/op
Iteration   1: 2.299 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.299 ms/op


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
# Warmup Iteration   1: 3.473 ±(99.9%) 0.059 ms/op
Iteration   1: 1.901 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.901 ms/op


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
# Warmup Iteration   1: 3.408 ±(99.9%) 0.060 ms/op
Iteration   1: 2.306 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.306 ms/op


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
# Warmup Iteration   1: 4.807 ±(99.9%) 0.094 ms/op
Iteration   1: 3.809 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.809 ms/op


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.118 ms/op
Iteration   1: 2.167 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   1.966 ms/op
                 createUser·p0.90:   2.503 ms/op
                 createUser·p0.95:   2.761 ms/op
                 createUser·p0.99:   9.527 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 20.713 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14749
  mean =      2.167 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13270 
    [ 2.500,  5.000) = 1187 
    [ 5.000,  7.500) = 97 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      9.527 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     20.713 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.103 ms/op
Iteration   1: 2.110 ±(99.9%) 0.059 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.789 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   4.831 ms/op
                 existUser·p0.999:  49.218 ms/op
                 existUser·p0.9999: 53.150 ms/op
                 existUser·p1.00:   56.951 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15224
  mean =      2.110 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15101 
    [ 5.000, 10.000) = 52 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 23 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      4.831 ms/op
     p(99.9000) =     49.218 ms/op
     p(99.9900) =     53.150 ms/op
     p(99.9990) =     56.951 ms/op
     p(99.9999) =     56.951 ms/op
    p(100.0000) =     56.951 ms/op


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
# Warmup Iteration   1: 3.056 ±(99.9%) 0.079 ms/op
Iteration   1: 1.953 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   1.774 ms/op
                 getUser·p0.90:   2.322 ms/op
                 getUser·p0.95:   2.535 ms/op
                 getUser·p0.99:   6.245 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 17.531 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16360
  mean =      1.953 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 353 
    [ 1.250,  2.500) = 15106 
    [ 2.500,  3.750) = 629 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      6.245 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.135 ms/op
Iteration   1: 3.201 ±(99.9%) 0.065 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.368 ms/op
                 listUser·p0.99:   5.891 ms/op
                 listUser·p0.999:  41.222 ms/op
                 listUser·p0.9999: 41.681 ms/op
                 listUser·p1.00:   41.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9987
  mean =      3.201 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9742 
    [ 5.000, 10.000) = 193 
    [10.000, 15.000) = 15 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 11 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.368 ms/op
     p(99.0000) =      5.891 ms/op
     p(99.9000) =     41.222 ms/op
     p(99.9900) =     41.681 ms/op
     p(99.9990) =     41.681 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.514          ops/ms
ClientSimple.existUser                       thrpt         11.133          ops/ms
ClientSimple.getUser                         thrpt         10.793          ops/ms
ClientSimple.listUser                        thrpt          8.007          ops/ms
ClientSimple.createUser                       avgt          2.299           ms/op
ClientSimple.existUser                        avgt          1.901           ms/op
ClientSimple.getUser                          avgt          2.306           ms/op
ClientSimple.listUser                         avgt          3.809           ms/op
ClientSimple.createUser                     sample  14749   2.167 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.680           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.966           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.503           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.527           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.514           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.713           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.103           ms/op
ClientSimple.existUser                      sample  15224   2.110 ± 0.059   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.673           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.870           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.064           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.831           ms/op
ClientSimple.existUser:existUser·p0.999     sample         49.218           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         53.150           ms/op
ClientSimple.existUser:existUser·p1.00      sample         56.951           ms/op
ClientSimple.getUser                        sample  16360   1.953 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.637           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.774           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.322           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.245           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.334           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.531           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.531           ms/op
ClientSimple.listUser                       sample   9987   3.201 ± 0.065   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.059           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.937           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.002           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.368           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.891           ms/op
ClientSimple.listUser:listUser·p0.999       sample         41.222           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         41.681           ms/op
ClientSimple.listUser:listUser·p1.00        sample         41.681           ms/op

Benchmark result is saved to 1719144361132.json
