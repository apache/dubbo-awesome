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
# Warmup Iteration   1: 1.646 ops/ms
Iteration   1: 6.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.841 ops/ms


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
# Warmup Iteration   1: 5.579 ops/ms
Iteration   1: 10.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.124 ops/ms


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
# Warmup Iteration   1: 5.438 ops/ms
Iteration   1: 12.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.028 ops/ms


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
# Warmup Iteration   1: 5.100 ops/ms
Iteration   1: 7.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.868 ops/ms


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.066 ms/op
Iteration   1: 2.241 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.241 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.064 ms/op
Iteration   1: 1.883 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.883 ms/op


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.069 ms/op
Iteration   1: 1.920 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.920 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ±(99.9%) 0.096 ms/op
Iteration   1: 3.174 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.174 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ±(99.9%) 0.083 ms/op
Iteration   1: 2.279 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.159 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  17.859 ms/op
                 createUser·p0.9999: 19.319 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14026
  mean =      2.279 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 11411 
    [ 2.500,  3.750) = 2188 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     19.319 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.056 ±(99.9%) 0.072 ms/op
Iteration   1: 1.899 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.193 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.426 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.207 ms/op
                 existUser·p0.999:  16.601 ms/op
                 existUser·p0.9999: 17.854 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16877
  mean =      1.899 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1226 
    [ 1.250,  2.500) = 14371 
    [ 2.500,  3.750) = 1163 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.193 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.426 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.207 ms/op
     p(99.9000) =     16.601 ms/op
     p(99.9900) =     17.854 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.267 ±(99.9%) 0.084 ms/op
Iteration   1: 2.187 ±(99.9%) 0.072 ms/op
                 getUser·p0.00:   0.447 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   2.680 ms/op
                 getUser·p0.99:   8.686 ms/op
                 getUser·p0.999:  53.799 ms/op
                 getUser·p0.9999: 66.778 ms/op
                 getUser·p1.00:   66.847 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15273
  mean =      2.187 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15053 
    [ 5.000, 10.000) = 88 
    [10.000, 15.000) = 54 
    [15.000, 20.000) = 38 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 8 
    [55.000, 60.000) = 6 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.680 ms/op
     p(99.0000) =      8.686 ms/op
     p(99.9000) =     53.799 ms/op
     p(99.9900) =     66.778 ms/op
     p(99.9990) =     66.847 ms/op
     p(99.9999) =     66.847 ms/op
    p(100.0000) =     66.847 ms/op


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.127 ms/op
Iteration   1: 3.735 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   8.060 ms/op
                 listUser·p0.999:  18.101 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8608
  mean =      3.735 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 589 
    [ 2.500,  3.750) = 4056 
    [ 3.750,  5.000) = 3576 
    [ 5.000,  6.250) = 266 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      8.060 ms/op
     p(99.9000) =     18.101 ms/op
     p(99.9900) =     18.481 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.841          ops/ms
ClientSimple.existUser                       thrpt         10.124          ops/ms
ClientSimple.getUser                         thrpt         12.028          ops/ms
ClientSimple.listUser                        thrpt          7.868          ops/ms
ClientSimple.createUser                       avgt          2.241           ms/op
ClientSimple.existUser                        avgt          1.883           ms/op
ClientSimple.getUser                          avgt          1.920           ms/op
ClientSimple.listUser                         avgt          3.174           ms/op
ClientSimple.createUser                     sample  14026   2.279 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.764           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.159           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.995           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.859           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.319           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.530           ms/op
ClientSimple.existUser                      sample  16877   1.899 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.193           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.796           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.426           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.207           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.601           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.854           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.990           ms/op
ClientSimple.getUser                        sample  15273   2.187 ± 0.072   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.447           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.680           ms/op
ClientSimple.getUser:getUser·p0.99          sample          8.686           ms/op
ClientSimple.getUser:getUser·p0.999         sample         53.799           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         66.778           ms/op
ClientSimple.getUser:getUser·p1.00          sample         66.847           ms/op
ClientSimple.listUser                       sample   8608   3.735 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.161           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.686           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.060           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.101           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.481           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.481           ms/op

Benchmark result is saved to 1719381937590.json
