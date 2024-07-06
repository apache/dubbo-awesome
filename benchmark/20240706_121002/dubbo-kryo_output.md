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
# Warmup Iteration   1: 1.637 ops/ms
Iteration   1: 7.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.170 ops/ms


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
# Warmup Iteration   1: 6.574 ops/ms
Iteration   1: 14.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.166 ops/ms


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
# Warmup Iteration   1: 6.201 ops/ms
Iteration   1: 15.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.010 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.532 ops/ms
Iteration   1: 8.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.231 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.071 ms/op
Iteration   1: 2.083 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.083 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.462 ±(99.9%) 0.066 ms/op
Iteration   1: 2.160 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.160 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.251 ±(99.9%) 0.049 ms/op
Iteration   1: 2.159 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.159 ms/op


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.075 ms/op
Iteration   1: 3.400 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.400 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.078 ms/op
Iteration   1: 2.307 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   2.232 ms/op
                 createUser·p0.90:   2.822 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   5.449 ms/op
                 createUser·p0.999:  15.974 ms/op
                 createUser·p0.9999: 19.288 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13982
  mean =      2.307 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 9852 
    [ 2.500,  3.750) = 3768 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      5.449 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     19.288 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.072 ms/op
Iteration   1: 1.647 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   1.855 ms/op
                 existUser·p0.95:   2.009 ms/op
                 existUser·p0.99:   2.527 ms/op
                 existUser·p0.999:  12.059 ms/op
                 existUser·p0.9999: 12.306 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19404
  mean =      1.647 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 342 
    [ 1.250,  2.500) = 18861 
    [ 2.500,  3.750) = 112 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      1.855 ms/op
     p(95.0000) =      2.009 ms/op
     p(99.0000) =      2.527 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     12.306 ms/op
     p(99.9990) =     12.337 ms/op
     p(99.9999) =     12.337 ms/op
    p(100.0000) =     12.337 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.079 ms/op
Iteration   1: 2.364 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.232 ms/op
                 getUser·p0.50:   2.298 ms/op
                 getUser·p0.90:   2.892 ms/op
                 getUser·p0.95:   3.168 ms/op
                 getUser·p0.99:   3.802 ms/op
                 getUser·p0.999:  32.161 ms/op
                 getUser·p0.9999: 32.504 ms/op
                 getUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13528
  mean =      2.364 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8570 
    [ 2.500,  5.000) = 4889 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.232 ms/op
     p(50.0000) =      2.298 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.168 ms/op
     p(99.0000) =      3.802 ms/op
     p(99.9000) =     32.161 ms/op
     p(99.9900) =     32.504 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.117 ms/op
Iteration   1: 3.564 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   5.622 ms/op
                 listUser·p0.999:  8.291 ms/op
                 listUser·p0.9999: 9.126 ms/op
                 listUser·p1.00:   9.126 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8969
  mean =      3.564 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 3 
    [ 1.500,  2.000) = 22 
    [ 2.000,  2.500) = 343 
    [ 2.500,  3.000) = 2053 
    [ 3.000,  3.500) = 1559 
    [ 3.500,  4.000) = 2703 
    [ 4.000,  4.500) = 1419 
    [ 4.500,  5.000) = 639 
    [ 5.000,  5.500) = 111 
    [ 5.500,  6.000) = 66 
    [ 6.000,  6.500) = 3 
    [ 6.500,  7.000) = 17 
    [ 7.000,  7.500) = 16 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 13 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.622 ms/op
     p(99.9000) =      8.291 ms/op
     p(99.9900) =      9.126 ms/op
     p(99.9990) =      9.126 ms/op
     p(99.9999) =      9.126 ms/op
    p(100.0000) =      9.126 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.170          ops/ms
ClientSimple.existUser                       thrpt         14.166          ops/ms
ClientSimple.getUser                         thrpt         15.010          ops/ms
ClientSimple.listUser                        thrpt          8.231          ops/ms
ClientSimple.createUser                       avgt          2.083           ms/op
ClientSimple.existUser                        avgt          2.160           ms/op
ClientSimple.getUser                          avgt          2.159           ms/op
ClientSimple.listUser                         avgt          3.400           ms/op
ClientSimple.createUser                     sample  13982   2.307 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.527           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.232           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.449           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.974           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.288           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.366           ms/op
ClientSimple.existUser                      sample  19404   1.647 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.513           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.597           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.855           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.009           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.059           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.306           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.337           ms/op
ClientSimple.getUser                        sample  13528   2.364 ± 0.046   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.232           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.298           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.168           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.802           ms/op
ClientSimple.getUser:getUser·p0.999         sample         32.161           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         32.504           ms/op
ClientSimple.getUser:getUser·p1.00          sample         32.539           ms/op
ClientSimple.listUser                       sample   8969   3.564 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.305           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.592           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.622           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.291           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.126           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.126           ms/op

Benchmark result is saved to 1720267556511.json
