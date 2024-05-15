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
# Warmup Iteration   1: 1.459 ops/ms
Iteration   1: 7.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.571 ops/ms


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
# Warmup Iteration   1: 7.023 ops/ms
Iteration   1: 12.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.886 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.027 ops/ms
Iteration   1: 15.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.218 ops/ms


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
# Warmup Iteration   1: 5.570 ops/ms
Iteration   1: 7.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.961 ops/ms


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.068 ms/op
Iteration   1: 2.333 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.333 ms/op


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
# Warmup Iteration   1: 3.138 ±(99.9%) 0.048 ms/op
Iteration   1: 1.724 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.724 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.052 ms/op
Iteration   1: 2.058 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.058 ms/op


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.092 ms/op
Iteration   1: 3.705 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.705 ms/op


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.252 ms/op
Iteration   1: 2.102 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.445 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 12.693 ms/op
                 createUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15210
  mean =      2.102 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 13807 
    [ 2.500,  3.750) = 949 
    [ 3.750,  5.000) = 144 
    [ 5.000,  6.250) = 139 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     11.551 ms/op
     p(99.9900) =     12.693 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.699 ±(99.9%) 0.056 ms/op
Iteration   1: 1.737 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   1.647 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   2.691 ms/op
                 existUser·p0.999:  12.822 ms/op
                 existUser·p0.9999: 13.043 ms/op
                 existUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18424
  mean =      1.737 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1565 
    [ 1.250,  2.500) = 16432 
    [ 2.500,  3.750) = 361 
    [ 3.750,  5.000) = 2 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      1.647 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      2.691 ms/op
     p(99.9000) =     12.822 ms/op
     p(99.9900) =     13.043 ms/op
     p(99.9990) =     13.140 ms/op
     p(99.9999) =     13.140 ms/op
    p(100.0000) =     13.140 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ±(99.9%) 0.072 ms/op
Iteration   1: 1.816 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   1.729 ms/op
                 getUser·p0.90:   2.273 ms/op
                 getUser·p0.95:   2.408 ms/op
                 getUser·p0.99:   3.008 ms/op
                 getUser·p0.999:  11.944 ms/op
                 getUser·p0.9999: 12.553 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17608
  mean =      1.816 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 519 
    [ 1.250,  2.500) = 16478 
    [ 2.500,  3.750) = 537 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      3.008 ms/op
     p(99.9000) =     11.944 ms/op
     p(99.9900) =     12.553 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.152 ±(99.9%) 0.134 ms/op
Iteration   1: 3.496 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.674 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.444 ms/op
                 listUser·p0.99:   4.866 ms/op
                 listUser·p0.999:  8.829 ms/op
                 listUser·p0.9999: 9.699 ms/op
                 listUser·p1.00:   9.699 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9149
  mean =      3.496 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 234 
    [ 2.000,  3.000) = 1500 
    [ 3.000,  4.000) = 5641 
    [ 4.000,  5.000) = 1701 
    [ 5.000,  6.000) = 43 
    [ 6.000,  7.000) = 12 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.444 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      8.829 ms/op
     p(99.9900) =      9.699 ms/op
     p(99.9990) =      9.699 ms/op
     p(99.9999) =      9.699 ms/op
    p(100.0000) =      9.699 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.571          ops/ms
ClientSimple.existUser                       thrpt         12.886          ops/ms
ClientSimple.getUser                         thrpt         15.218          ops/ms
ClientSimple.listUser                        thrpt          7.961          ops/ms
ClientSimple.createUser                       avgt          2.333           ms/op
ClientSimple.existUser                        avgt          1.724           ms/op
ClientSimple.getUser                          avgt          2.058           ms/op
ClientSimple.listUser                         avgt          3.705           ms/op
ClientSimple.createUser                     sample  15210   2.102 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.888           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.445           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.595           ms/op
ClientSimple.createUser:createUser·p0.999   sample         11.551           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.693           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.222           ms/op
ClientSimple.existUser                      sample  18424   1.737 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.577           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.647           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.691           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.822           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.043           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.140           ms/op
ClientSimple.getUser                        sample  17608   1.816 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.674           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.729           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.273           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.008           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.944           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.553           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.665           ms/op
ClientSimple.listUser                       sample   9149   3.496 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.674           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.584           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.444           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.829           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.699           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.699           ms/op

Benchmark result is saved to 1715774835003.json
