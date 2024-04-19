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
# Warmup Iteration   1: 1.621 ops/ms
Iteration   1: 7.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.515 ops/ms


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
# Warmup Iteration   1: 6.463 ops/ms
Iteration   1: 13.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.299 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.762 ops/ms
Iteration   1: 12.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.164 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.657 ops/ms
Iteration   1: 8.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.835 ops/ms


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.095 ms/op
Iteration   1: 2.479 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.479 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.333 ±(99.9%) 0.059 ms/op
Iteration   1: 2.009 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.009 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.054 ms/op
Iteration   1: 2.069 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.069 ms/op


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.100 ms/op
Iteration   1: 3.566 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.566 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.080 ms/op
Iteration   1: 2.001 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.329 ms/op
                 createUser·p0.50:   1.851 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.634 ms/op
                 createUser·p0.99:   5.779 ms/op
                 createUser·p0.999:  22.643 ms/op
                 createUser·p0.9999: 23.580 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15979
  mean =      2.001 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14728 
    [ 2.500,  5.000) = 1048 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      5.779 ms/op
     p(99.9000) =     22.643 ms/op
     p(99.9900) =     23.580 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 2.874 ±(99.9%) 0.066 ms/op
Iteration   1: 1.807 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   1.694 ms/op
                 existUser·p0.90:   2.159 ms/op
                 existUser·p0.95:   2.339 ms/op
                 existUser·p0.99:   3.060 ms/op
                 existUser·p0.999:  19.540 ms/op
                 existUser·p0.9999: 19.691 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17691
  mean =      1.807 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 487 
    [ 1.250,  2.500) = 16751 
    [ 2.500,  3.750) = 345 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      1.694 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.339 ms/op
     p(99.0000) =      3.060 ms/op
     p(99.9000) =     19.540 ms/op
     p(99.9900) =     19.691 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.079 ms/op
Iteration   1: 2.187 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   2.087 ms/op
                 getUser·p0.90:   2.822 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.886 ms/op
                 getUser·p0.999:  12.288 ms/op
                 getUser·p0.9999: 13.114 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14607
  mean =      2.187 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 11100 
    [ 2.500,  3.750) = 3175 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.087 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.886 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     13.114 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.130 ms/op
Iteration   1: 3.374 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.297 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  23.658 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9479
  mean =      3.374 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 878 
    [ 2.500,  5.000) = 8404 
    [ 5.000,  7.500) = 163 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     23.658 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     24.543 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.515          ops/ms
ClientSimple.existUser                       thrpt         13.299          ops/ms
ClientSimple.getUser                         thrpt         12.164          ops/ms
ClientSimple.listUser                        thrpt          8.835          ops/ms
ClientSimple.createUser                       avgt          2.479           ms/op
ClientSimple.existUser                        avgt          2.009           ms/op
ClientSimple.getUser                          avgt          2.069           ms/op
ClientSimple.listUser                         avgt          3.566           ms/op
ClientSimple.createUser                     sample  15979   2.001 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.329           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.851           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.779           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.643           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.580           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.757           ms/op
ClientSimple.existUser                      sample  17691   1.807 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.746           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.694           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.159           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.060           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.540           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.691           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.792           ms/op
ClientSimple.getUser                        sample  14607   2.187 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.582           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.087           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.068           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.886           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.288           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.114           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.189           ms/op
ClientSimple.listUser                       sample   9479   3.374 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.059           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.297           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.026           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.652           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.658           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.543           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.543           ms/op

Benchmark result is saved to 1713528387405.json
