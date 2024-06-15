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
# Warmup Iteration   1: 1.793 ops/ms
Iteration   1: 7.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.986 ops/ms


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
# Warmup Iteration   1: 6.501 ops/ms
Iteration   1: 13.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.340 ops/ms


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
# Warmup Iteration   1: 6.441 ops/ms
Iteration   1: 14.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.554 ops/ms


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
# Warmup Iteration   1: 4.967 ops/ms
Iteration   1: 9.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.127 ops/ms


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.082 ms/op
Iteration   1: 2.085 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.085 ms/op


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
# Warmup Iteration   1: 2.990 ±(99.9%) 0.054 ms/op
Iteration   1: 1.929 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.929 ms/op


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
# Warmup Iteration   1: 3.194 ±(99.9%) 0.050 ms/op
Iteration   1: 2.249 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.249 ms/op


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
# Warmup Iteration   1: 5.242 ±(99.9%) 0.119 ms/op
Iteration   1: 3.939 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.939 ms/op


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
# Warmup Iteration   1: 3.394 ±(99.9%) 0.080 ms/op
Iteration   1: 2.328 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   2.753 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   11.002 ms/op
                 createUser·p0.999:  17.137 ms/op
                 createUser·p0.9999: 20.165 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14024
  mean =      2.328 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11344 
    [ 2.500,  5.000) = 2409 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =     11.002 ms/op
     p(99.9000) =     17.137 ms/op
     p(99.9900) =     20.165 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 2.775 ±(99.9%) 0.063 ms/op
Iteration   1: 1.905 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.372 ms/op
                 existUser·p0.99:   4.086 ms/op
                 existUser·p0.999:  21.627 ms/op
                 existUser·p0.9999: 21.767 ms/op
                 existUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17132
  mean =      1.905 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16574 
    [ 2.500,  5.000) = 438 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      4.086 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     21.767 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.082 ms/op
Iteration   1: 1.967 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   1.835 ms/op
                 getUser·p0.90:   2.515 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   3.342 ms/op
                 getUser·p0.999:  9.486 ms/op
                 getUser·p0.9999: 10.222 ms/op
                 getUser·p1.00:   10.355 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16248
  mean =      1.967 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 45 
    [ 1.000,  2.000) = 10036 
    [ 2.000,  3.000) = 5771 
    [ 3.000,  4.000) = 272 
    [ 4.000,  5.000) = 75 
    [ 5.000,  6.000) = 16 
    [ 6.000,  7.000) = 1 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 3 
    [ 9.000, 10.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.342 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     10.222 ms/op
     p(99.9990) =     10.355 ms/op
     p(99.9999) =     10.355 ms/op
    p(100.0000) =     10.355 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.139 ms/op
Iteration   1: 3.400 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   3.322 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.550 ms/op
                 listUser·p0.999:  11.262 ms/op
                 listUser·p0.9999: 12.665 ms/op
                 listUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9440
  mean =      3.400 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 535 
    [ 2.500,  3.750) = 6245 
    [ 3.750,  5.000) = 2477 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.550 ms/op
     p(99.9000) =     11.262 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.986          ops/ms
ClientSimple.existUser                       thrpt         13.340          ops/ms
ClientSimple.getUser                         thrpt         14.554          ops/ms
ClientSimple.listUser                        thrpt          9.127          ops/ms
ClientSimple.createUser                       avgt          2.085           ms/op
ClientSimple.existUser                        avgt          1.929           ms/op
ClientSimple.getUser                          avgt          2.249           ms/op
ClientSimple.listUser                         avgt          3.939           ms/op
ClientSimple.createUser                     sample  14024   2.328 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.931           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.092           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.002           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.137           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.165           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.218           ms/op
ClientSimple.existUser                      sample  17132   1.905 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.656           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.216           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.086           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.627           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.767           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.791           ms/op
ClientSimple.getUser                        sample  16248   1.967 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.610           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.835           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.342           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.486           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.222           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.355           ms/op
ClientSimple.listUser                       sample   9440   3.400 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.834           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.322           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.108           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.550           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.262           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.665           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.665           ms/op

Benchmark result is saved to 1718410543622.json
