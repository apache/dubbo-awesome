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
# Warmup Iteration   1: 1.991 ops/ms
Iteration   1: 6.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.531 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.397 ops/ms
Iteration   1: 11.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.607 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.967 ops/ms
Iteration   1: 13.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.427 ops/ms


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
# Warmup Iteration   1: 5.154 ops/ms
Iteration   1: 8.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.290 ops/ms


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.068 ms/op
Iteration   1: 2.263 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.263 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.054 ms/op
Iteration   1: 1.813 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.813 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.061 ms/op
Iteration   1: 1.946 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.946 ms/op


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
# Warmup Iteration   1: 4.680 ±(99.9%) 0.112 ms/op
Iteration   1: 3.498 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.498 ms/op


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.084 ms/op
Iteration   1: 2.125 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   1.995 ms/op
                 createUser·p0.90:   2.461 ms/op
                 createUser·p0.95:   2.630 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  20.642 ms/op
                 createUser·p0.9999: 20.758 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15051
  mean =      2.125 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13772 
    [ 2.500,  5.000) = 1139 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.461 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =     20.642 ms/op
     p(99.9900) =     20.758 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.014 ±(99.9%) 0.066 ms/op
Iteration   1: 1.832 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   1.757 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   3.103 ms/op
                 existUser·p0.999:  13.353 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17441
  mean =      1.832 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 387 
    [ 1.250,  2.500) = 16459 
    [ 2.500,  3.750) = 465 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      3.103 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     13.631 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


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
# Warmup Iteration   1: 3.058 ±(99.9%) 0.086 ms/op
Iteration   1: 2.021 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   1.847 ms/op
                 getUser·p0.90:   2.576 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  13.028 ms/op
                 getUser·p0.9999: 14.113 ms/op
                 getUser·p1.00:   14.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15853
  mean =      2.021 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 182 
    [ 1.250,  2.500) = 13680 
    [ 2.500,  3.750) = 1786 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =     13.028 ms/op
     p(99.9900) =     14.113 ms/op
     p(99.9990) =     14.631 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 5.453 ±(99.9%) 0.146 ms/op
Iteration   1: 3.485 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.078 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9194
  mean =      3.485 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 946 
    [ 2.500,  3.750) = 5234 
    [ 3.750,  5.000) = 2756 
    [ 5.000,  6.250) = 172 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     16.810 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.531          ops/ms
ClientSimple.existUser                       thrpt         11.607          ops/ms
ClientSimple.getUser                         thrpt         13.427          ops/ms
ClientSimple.listUser                        thrpt          8.290          ops/ms
ClientSimple.createUser                       avgt          2.263           ms/op
ClientSimple.existUser                        avgt          1.813           ms/op
ClientSimple.getUser                          avgt          1.946           ms/op
ClientSimple.listUser                         avgt          3.498           ms/op
ClientSimple.createUser                     sample  15051   2.125 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.763           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.995           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.461           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.833           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.642           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.758           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.775           ms/op
ClientSimple.existUser                      sample  17441   1.832 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.692           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.757           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.103           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.353           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.631           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.631           ms/op
ClientSimple.getUser                        sample  15853   2.021 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.678           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.847           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.949           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.028           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.113           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.631           ms/op
ClientSimple.listUser                       sample   9194   3.485 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.196           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.502           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.078           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.008           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.810           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.810           ms/op

Benchmark result is saved to 1717221905295.json
