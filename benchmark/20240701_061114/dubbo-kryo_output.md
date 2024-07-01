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
# Warmup Iteration   1: 1.818 ops/ms
Iteration   1: 6.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.682 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.279 ops/ms
Iteration   1: 12.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.702 ops/ms


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
# Warmup Iteration   1: 6.536 ops/ms
Iteration   1: 12.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.770 ops/ms


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
# Warmup Iteration   1: 4.813 ops/ms
Iteration   1: 8.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.278 ops/ms


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.091 ms/op
Iteration   1: 2.086 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.086 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.048 ms/op
Iteration   1: 1.665 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.665 ms/op


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
# Warmup Iteration   1: 3.276 ±(99.9%) 0.058 ms/op
Iteration   1: 2.094 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.094 ms/op


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
# Warmup Iteration   1: 4.734 ±(99.9%) 0.074 ms/op
Iteration   1: 3.157 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.157 ms/op


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
# Warmup Iteration   1: 3.403 ±(99.9%) 0.093 ms/op
Iteration   1: 2.214 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.440 ms/op
                 createUser·p0.50:   2.013 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   9.224 ms/op
                 createUser·p0.999:  23.106 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14424
  mean =      2.214 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11557 
    [ 2.500,  5.000) = 2668 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     23.106 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 3.042 ±(99.9%) 0.083 ms/op
Iteration   1: 2.051 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.439 ms/op
                 existUser·p0.50:   1.882 ms/op
                 existUser·p0.90:   2.503 ms/op
                 existUser·p0.95:   2.699 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  27.535 ms/op
                 existUser·p0.9999: 27.895 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15698
  mean =      2.051 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14128 
    [ 2.500,  5.000) = 1363 
    [ 5.000,  7.500) = 79 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     27.535 ms/op
     p(99.9900) =     27.895 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 3.210 ±(99.9%) 0.070 ms/op
Iteration   1: 2.021 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.314 ms/op
                 getUser·p0.50:   1.976 ms/op
                 getUser·p0.90:   2.540 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   3.508 ms/op
                 getUser·p0.999:  18.322 ms/op
                 getUser·p0.9999: 18.617 ms/op
                 getUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15854
  mean =      2.021 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 659 
    [ 1.250,  2.500) = 13282 
    [ 2.500,  3.750) = 1797 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.314 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.508 ms/op
     p(99.9000) =     18.322 ms/op
     p(99.9900) =     18.617 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.121 ms/op
Iteration   1: 3.406 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   3.248 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.477 ms/op
                 listUser·p0.99:   5.749 ms/op
                 listUser·p0.999:  19.923 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9409
  mean =      3.406 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 582 
    [ 2.500,  5.000) = 8669 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.477 ms/op
     p(99.0000) =      5.749 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.682          ops/ms
ClientSimple.existUser                       thrpt         12.702          ops/ms
ClientSimple.getUser                         thrpt         12.770          ops/ms
ClientSimple.listUser                        thrpt          8.278          ops/ms
ClientSimple.createUser                       avgt          2.086           ms/op
ClientSimple.existUser                        avgt          1.665           ms/op
ClientSimple.getUser                          avgt          2.094           ms/op
ClientSimple.listUser                         avgt          3.157           ms/op
ClientSimple.createUser                     sample  14424   2.214 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.440           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.013           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.224           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.106           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.724           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.724           ms/op
ClientSimple.existUser                      sample  15698   2.051 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.439           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.882           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.971           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.535           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.895           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.951           ms/op
ClientSimple.getUser                        sample  15854   2.021 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.314           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.976           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.508           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.322           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.617           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.809           ms/op
ClientSimple.listUser                       sample   9409   3.406 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.885           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.248           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.477           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.749           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.923           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.103           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.103           ms/op

Benchmark result is saved to 1719814006726.json
