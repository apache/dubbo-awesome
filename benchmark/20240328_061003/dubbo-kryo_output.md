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
# Warmup Iteration   1: 2.138 ops/ms
Iteration   1: 5.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.875 ops/ms


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
# Warmup Iteration   1: 5.603 ops/ms
Iteration   1: 12.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.219 ops/ms


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
# Warmup Iteration   1: 5.735 ops/ms
Iteration   1: 12.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.760 ops/ms


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
# Warmup Iteration   1: 5.404 ops/ms
Iteration   1: 8.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.617 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ±(99.9%) 0.061 ms/op
Iteration   1: 2.082 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.082 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.050 ms/op
Iteration   1: 1.771 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.771 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.329 ±(99.9%) 0.068 ms/op
Iteration   1: 2.178 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.178 ms/op


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
# Warmup Iteration   1: 4.381 ±(99.9%) 0.070 ms/op
Iteration   1: 3.436 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.436 ms/op


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.099 ms/op
Iteration   1: 2.319 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.507 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  24.026 ms/op
                 createUser·p0.9999: 24.600 ms/op
                 createUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13795
  mean =      2.319 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11315 
    [ 2.500,  5.000) = 2256 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     24.026 ms/op
     p(99.9900) =     24.600 ms/op
     p(99.9990) =     24.674 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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
# Warmup Iteration   1: 2.964 ±(99.9%) 0.106 ms/op
Iteration   1: 1.932 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.492 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   3.074 ms/op
                 existUser·p0.999:  13.705 ms/op
                 existUser·p0.9999: 14.604 ms/op
                 existUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16544
  mean =      1.932 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 678 
    [ 1.250,  2.500) = 14423 
    [ 2.500,  3.750) = 1337 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.074 ms/op
     p(99.9000) =     13.705 ms/op
     p(99.9900) =     14.604 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 3.181 ±(99.9%) 0.086 ms/op
Iteration   1: 1.935 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   1.864 ms/op
                 getUser·p0.90:   2.286 ms/op
                 getUser·p0.95:   2.433 ms/op
                 getUser·p0.99:   3.305 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 18.438 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16523
  mean =      1.935 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 15796 
    [ 2.500,  3.750) = 457 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.305 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     18.438 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.764 ±(99.9%) 0.143 ms/op
Iteration   1: 3.596 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   0.653 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.962 ms/op
                 listUser·p0.999:  24.117 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9011
  mean =      3.596 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1072 
    [ 2.500,  5.000) = 7683 
    [ 5.000,  7.500) = 168 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.962 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.875          ops/ms
ClientSimple.existUser                       thrpt         12.219          ops/ms
ClientSimple.getUser                         thrpt         12.760          ops/ms
ClientSimple.listUser                        thrpt          8.617          ops/ms
ClientSimple.createUser                       avgt          2.082           ms/op
ClientSimple.existUser                        avgt          1.771           ms/op
ClientSimple.getUser                          avgt          2.178           ms/op
ClientSimple.listUser                         avgt          3.436           ms/op
ClientSimple.createUser                     sample  13795   2.319 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.507           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.748           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.026           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.600           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.674           ms/op
ClientSimple.existUser                      sample  16544   1.932 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.492           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.074           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.705           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.604           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.647           ms/op
ClientSimple.getUser                        sample  16523   1.935 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.629           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.864           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.286           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.305           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.055           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.438           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.481           ms/op
ClientSimple.listUser                       sample   9011   3.596 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.653           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.588           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.962           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.117           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.248           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.248           ms/op

Benchmark result is saved to 1711605921197.json
