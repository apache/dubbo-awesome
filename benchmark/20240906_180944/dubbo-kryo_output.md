# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
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
Iteration   1: 7.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.888 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.508 ops/ms
Iteration   1: 12.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.347 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.277 ops/ms
Iteration   1: 10.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.896 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.700 ops/ms
Iteration   1: 8.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.781 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.648 ±(99.9%) 0.061 ms/op
Iteration   1: 2.381 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.381 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.072 ±(99.9%) 0.046 ms/op
Iteration   1: 1.739 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.311 ±(99.9%) 0.058 ms/op
Iteration   1: 1.795 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.795 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.014 ±(99.9%) 0.087 ms/op
Iteration   1: 3.649 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.649 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ±(99.9%) 0.091 ms/op
Iteration   1: 2.268 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   2.042 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  29.420 ms/op
                 createUser·p0.9999: 43.722 ms/op
                 createUser·p1.00:   43.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14088
  mean =      2.268 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13836 
    [ 5.000, 10.000) = 167 
    [10.000, 15.000) = 37 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 21 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     29.420 ms/op
     p(99.9900) =     43.722 ms/op
     p(99.9990) =     43.909 ms/op
     p(99.9999) =     43.909 ms/op
    p(100.0000) =     43.909 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.982 ±(99.9%) 0.070 ms/op
Iteration   1: 2.068 ±(99.9%) 0.047 ms/op
                 existUser·p0.00:   0.411 ms/op
                 existUser·p0.50:   1.948 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   3.249 ms/op
                 existUser·p0.999:  31.147 ms/op
                 existUser·p0.9999: 31.895 ms/op
                 existUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15472
  mean =      2.068 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14164 
    [ 2.500,  5.000) = 1221 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.249 ms/op
     p(99.9000) =     31.147 ms/op
     p(99.9900) =     31.895 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.099 ±(99.9%) 0.077 ms/op
Iteration   1: 2.064 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   2.015 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.949 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  10.281 ms/op
                 getUser·p0.9999: 10.904 ms/op
                 getUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15513
  mean =      2.064 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 331 
    [ 1.250,  2.500) = 12856 
    [ 2.500,  3.750) = 2065 
    [ 3.750,  5.000) = 173 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     10.281 ms/op
     p(99.9900) =     10.904 ms/op
     p(99.9990) =     11.076 ms/op
     p(99.9999) =     11.076 ms/op
    p(100.0000) =     11.076 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.308 ±(99.9%) 0.128 ms/op
Iteration   1: 3.324 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   3.150 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.437 ms/op
                 listUser·p0.999:  8.837 ms/op
                 listUser·p0.9999: 10.682 ms/op
                 listUser·p1.00:   10.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9629
  mean =      3.324 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 55 
    [ 2.000,  3.000) = 3845 
    [ 3.000,  4.000) = 4223 
    [ 4.000,  5.000) = 1378 
    [ 5.000,  6.000) = 58 
    [ 6.000,  7.000) = 38 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 31 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.434 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.437 ms/op
     p(99.9000) =      8.837 ms/op
     p(99.9900) =     10.682 ms/op
     p(99.9990) =     10.682 ms/op
     p(99.9999) =     10.682 ms/op
    p(100.0000) =     10.682 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.888          ops/ms
ClientSimple.existUser                       thrpt         12.347          ops/ms
ClientSimple.getUser                         thrpt         10.896          ops/ms
ClientSimple.listUser                        thrpt          8.781          ops/ms
ClientSimple.createUser                       avgt          2.381           ms/op
ClientSimple.existUser                        avgt          1.739           ms/op
ClientSimple.getUser                          avgt          1.795           ms/op
ClientSimple.listUser                         avgt          3.649           ms/op
ClientSimple.createUser                     sample  14088   2.268 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.779           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.042           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.068           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.365           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.420           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         43.722           ms/op
ClientSimple.createUser:createUser·p1.00    sample         43.909           ms/op
ClientSimple.existUser                      sample  15472   2.068 ± 0.047   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.411           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.948           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.249           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.147           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.895           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.949           ms/op
ClientSimple.getUser                        sample  15513   2.064 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.524           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.015           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.342           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.281           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.904           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.076           ms/op
ClientSimple.listUser                       sample   9629   3.324 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.434           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.150           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.153           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.437           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.837           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.682           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.682           ms/op

Benchmark result is saved to 1725645910061.json
