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
# Warmup Iteration   1: 1.694 ops/ms
Iteration   1: 6.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.746 ops/ms


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
# Warmup Iteration   1: 5.871 ops/ms
Iteration   1: 12.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.956 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.602 ops/ms
Iteration   1: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.718 ops/ms


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
# Warmup Iteration   1: 4.692 ops/ms
Iteration   1: 8.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.245 ops/ms


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.059 ms/op
Iteration   1: 2.280 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.280 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.046 ms/op
Iteration   1: 1.799 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.799 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.056 ms/op
Iteration   1: 1.759 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.759 ms/op


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
# Warmup Iteration   1: 4.210 ±(99.9%) 0.089 ms/op
Iteration   1: 3.658 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.658 ms/op


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
# Warmup Iteration   1: 3.390 ±(99.9%) 0.079 ms/op
Iteration   1: 2.239 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.444 ms/op
                 createUser·p0.50:   2.001 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.945 ms/op
                 createUser·p0.99:   11.797 ms/op
                 createUser·p0.999:  28.201 ms/op
                 createUser·p0.9999: 34.173 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14273
  mean =      2.239 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12347 
    [ 2.500,  5.000) = 1680 
    [ 5.000,  7.500) = 21 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =     11.797 ms/op
     p(99.9000) =     28.201 ms/op
     p(99.9900) =     34.173 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 2.957 ±(99.9%) 0.065 ms/op
Iteration   1: 1.828 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.373 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  19.841 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17485
  mean =      1.828 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16644 
    [ 2.500,  5.000) = 738 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.375 ms/op
     p(99.9000) =     19.841 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.106 ms/op
Iteration   1: 2.163 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.228 ms/op
                 getUser·p0.50:   2.015 ms/op
                 getUser·p0.90:   2.871 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  12.979 ms/op
                 getUser·p0.9999: 13.665 ms/op
                 getUser·p1.00:   13.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14852
  mean =      2.163 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 223 
    [ 1.250,  2.500) = 11305 
    [ 2.500,  3.750) = 3194 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.228 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =     12.979 ms/op
     p(99.9900) =     13.665 ms/op
     p(99.9990) =     13.681 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 5.263 ±(99.9%) 0.162 ms/op
Iteration   1: 3.792 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.061 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  13.649 ms/op
                 listUser·p0.9999: 14.844 ms/op
                 listUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8464
  mean =      3.792 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 605 
    [ 2.500,  3.750) = 3502 
    [ 3.750,  5.000) = 3909 
    [ 5.000,  6.250) = 229 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.061 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     13.649 ms/op
     p(99.9900) =     14.844 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.746          ops/ms
ClientSimple.existUser                       thrpt         12.956          ops/ms
ClientSimple.getUser                         thrpt         10.718          ops/ms
ClientSimple.listUser                        thrpt          8.245          ops/ms
ClientSimple.createUser                       avgt          2.280           ms/op
ClientSimple.existUser                        avgt          1.799           ms/op
ClientSimple.getUser                          avgt          1.759           ms/op
ClientSimple.listUser                         avgt          3.658           ms/op
ClientSimple.createUser                     sample  14273   2.239 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.444           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.001           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.797           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.201           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.173           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.341           ms/op
ClientSimple.existUser                      sample  17485   1.828 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.373           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.645           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.375           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.841           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.054           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.152           ms/op
ClientSimple.getUser                        sample  14852   2.163 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.228           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.015           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.080           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.674           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.979           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.665           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.681           ms/op
ClientSimple.listUser                       sample   8464   3.792 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.358           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.772           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.061           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.682           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.649           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.844           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.844           ms/op

Benchmark result is saved to 1711239413651.json
