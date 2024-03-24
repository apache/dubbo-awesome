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
# Warmup Iteration   1: 1.411 ops/ms
Iteration   1: 6.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.304 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.258 ops/ms
Iteration   1: 12.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.085 ops/ms


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
# Warmup Iteration   1: 6.189 ops/ms
Iteration   1: 12.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.789 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ops/ms
Iteration   1: 8.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.583 ops/ms


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.075 ms/op
Iteration   1: 2.225 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.225 ms/op


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
# Warmup Iteration   1: 3.341 ±(99.9%) 0.058 ms/op
Iteration   1: 1.833 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.833 ms/op


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
# Warmup Iteration   1: 3.431 ±(99.9%) 0.054 ms/op
Iteration   1: 2.008 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.008 ms/op


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.091 ms/op
Iteration   1: 3.403 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.403 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.087 ms/op
Iteration   1: 2.319 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.454 ms/op
                 createUser·p0.50:   2.134 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   2.917 ms/op
                 createUser·p0.99:   12.036 ms/op
                 createUser·p0.999:  22.746 ms/op
                 createUser·p0.9999: 23.563 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13838
  mean =      2.319 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11852 
    [ 2.500,  5.000) = 1672 
    [ 5.000,  7.500) = 53 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.917 ms/op
     p(99.0000) =     12.036 ms/op
     p(99.9000) =     22.746 ms/op
     p(99.9900) =     23.563 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.093 ms/op
Iteration   1: 1.964 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.305 ms/op
                 existUser·p0.50:   1.823 ms/op
                 existUser·p0.90:   2.695 ms/op
                 existUser·p0.95:   2.941 ms/op
                 existUser·p0.99:   3.900 ms/op
                 existUser·p0.999:  14.261 ms/op
                 existUser·p0.9999: 14.524 ms/op
                 existUser·p1.00:   14.565 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16290
  mean =      1.964 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 954 
    [ 1.250,  2.500) = 12962 
    [ 2.500,  3.750) = 2178 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.305 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      3.900 ms/op
     p(99.9000) =     14.261 ms/op
     p(99.9900) =     14.524 ms/op
     p(99.9990) =     14.565 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.088 ms/op
Iteration   1: 1.898 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.526 ms/op
                 getUser·p0.50:   1.718 ms/op
                 getUser·p0.90:   2.335 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   3.684 ms/op
                 getUser·p0.999:  18.350 ms/op
                 getUser·p0.9999: 19.286 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16815
  mean =      1.898 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 330 
    [ 1.250,  2.500) = 15420 
    [ 2.500,  3.750) = 900 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.684 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     19.286 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.161 ms/op
Iteration   1: 3.864 ±(99.9%) 0.061 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   8.540 ms/op
                 listUser·p0.999:  25.100 ms/op
                 listUser·p0.9999: 25.657 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8274
  mean =      3.864 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 422 
    [ 2.500,  5.000) = 7463 
    [ 5.000,  7.500) = 283 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      8.540 ms/op
     p(99.9000) =     25.100 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.304          ops/ms
ClientSimple.existUser                       thrpt         12.085          ops/ms
ClientSimple.getUser                         thrpt         12.789          ops/ms
ClientSimple.listUser                        thrpt          8.583          ops/ms
ClientSimple.createUser                       avgt          2.225           ms/op
ClientSimple.existUser                        avgt          1.833           ms/op
ClientSimple.getUser                          avgt          2.008           ms/op
ClientSimple.listUser                         avgt          3.403           ms/op
ClientSimple.createUser                     sample  13838   2.319 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.454           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.134           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.917           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.036           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.746           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.563           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.626           ms/op
ClientSimple.existUser                      sample  16290   1.964 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.305           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.823           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.941           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.900           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.261           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.524           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.565           ms/op
ClientSimple.getUser                        sample  16815   1.898 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.526           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.718           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.335           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.684           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.350           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.286           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.464           ms/op
ClientSimple.listUser                       sample   8274   3.864 ± 0.061   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.061           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.781           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.956           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.540           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.100           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.657           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.657           ms/op

Benchmark result is saved to 1711303541374.json
