# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.872 ops/ms
Iteration   1: 7.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.338 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.650 ops/ms
Iteration   1: 11.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.124 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.371 ops/ms
Iteration   1: 14.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.462 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.921 ops/ms
Iteration   1: 8.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.856 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.074 ms/op
Iteration   1: 1.880 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.880 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.294 ±(99.9%) 0.047 ms/op
Iteration   1: 1.766 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.766 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.381 ±(99.9%) 0.052 ms/op
Iteration   1: 1.908 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.908 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ±(99.9%) 0.134 ms/op
Iteration   1: 3.225 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.225 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.267 ±(99.9%) 0.077 ms/op
Iteration   1: 2.106 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   1.892 ms/op
                 createUser·p0.90:   2.564 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   5.770 ms/op
                 createUser·p0.999:  15.172 ms/op
                 createUser·p0.9999: 18.513 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15162
  mean =      2.106 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 13276 
    [ 2.500,  3.750) = 1329 
    [ 3.750,  5.000) = 158 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      5.770 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     18.513 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.236 ±(99.9%) 0.072 ms/op
Iteration   1: 1.840 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   1.982 ms/op
                 existUser·p0.95:   2.080 ms/op
                 existUser·p0.99:   3.563 ms/op
                 existUser·p0.999:  15.804 ms/op
                 existUser·p0.9999: 16.159 ms/op
                 existUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17383
  mean =      1.840 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 16961 
    [ 2.500,  3.750) = 93 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      1.982 ms/op
     p(95.0000) =      2.080 ms/op
     p(99.0000) =      3.563 ms/op
     p(99.9000) =     15.804 ms/op
     p(99.9900) =     16.159 ms/op
     p(99.9990) =     16.171 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.497 ±(99.9%) 0.296 ms/op
Iteration   1: 2.435 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.603 ms/op
                 getUser·p0.50:   2.269 ms/op
                 getUser·p0.90:   3.158 ms/op
                 getUser·p0.95:   3.416 ms/op
                 getUser·p0.99:   5.454 ms/op
                 getUser·p0.999:  14.168 ms/op
                 getUser·p0.9999: 14.836 ms/op
                 getUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13120
  mean =      2.435 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 8607 
    [ 2.500,  3.750) = 4031 
    [ 3.750,  5.000) = 205 
    [ 5.000,  6.250) = 130 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.416 ms/op
     p(99.0000) =      5.454 ms/op
     p(99.9000) =     14.168 ms/op
     p(99.9900) =     14.836 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.568 ±(99.9%) 0.129 ms/op
Iteration   1: 3.294 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   3.281 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.581 ms/op
                 listUser·p0.999:  7.120 ms/op
                 listUser·p0.9999: 9.535 ms/op
                 listUser·p1.00:   9.535 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9734
  mean =      3.294 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 0 
    [ 1.500,  2.000) = 37 
    [ 2.000,  2.500) = 1115 
    [ 2.500,  3.000) = 2869 
    [ 3.000,  3.500) = 1585 
    [ 3.500,  4.000) = 2858 
    [ 4.000,  4.500) = 951 
    [ 4.500,  5.000) = 153 
    [ 5.000,  5.500) = 58 
    [ 5.500,  6.000) = 45 
    [ 6.000,  6.500) = 24 
    [ 6.500,  7.000) = 29 
    [ 7.000,  7.500) = 3 
    [ 7.500,  8.000) = 6 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.581 ms/op
     p(99.9000) =      7.120 ms/op
     p(99.9900) =      9.535 ms/op
     p(99.9990) =      9.535 ms/op
     p(99.9999) =      9.535 ms/op
    p(100.0000) =      9.535 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.338          ops/ms
ClientSimple.existUser                       thrpt         11.124          ops/ms
ClientSimple.getUser                         thrpt         14.462          ops/ms
ClientSimple.listUser                        thrpt          8.856          ops/ms
ClientSimple.createUser                       avgt          1.880           ms/op
ClientSimple.existUser                        avgt          1.766           ms/op
ClientSimple.getUser                          avgt          1.908           ms/op
ClientSimple.listUser                         avgt          3.225           ms/op
ClientSimple.createUser                     sample  15162   2.106 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.732           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.892           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.770           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.172           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.513           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.547           ms/op
ClientSimple.existUser                      sample  17383   1.840 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.510           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.982           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.080           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.563           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.804           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.159           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.171           ms/op
ClientSimple.getUser                        sample  13120   2.435 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.603           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.158           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.416           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.454           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.168           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.836           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.877           ms/op
ClientSimple.listUser                       sample   9734   3.294 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.749           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.281           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.581           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.120           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.535           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.535           ms/op

Benchmark result is saved to 1722535517215.json
