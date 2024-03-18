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
# Warmup Iteration   1: 1.817 ops/ms
Iteration   1: 7.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.537 ops/ms


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
# Warmup Iteration   1: 6.127 ops/ms
Iteration   1: 12.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.874 ops/ms


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
# Warmup Iteration   1: 6.477 ops/ms
Iteration   1: 14.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.477 ops/ms


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
# Warmup Iteration   1: 5.726 ops/ms
Iteration   1: 8.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.293 ops/ms


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.079 ms/op
Iteration   1: 2.023 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.023 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.054 ms/op
Iteration   1: 2.077 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.077 ms/op


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
# Warmup Iteration   1: 3.125 ±(99.9%) 0.051 ms/op
Iteration   1: 1.844 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.844 ms/op


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
# Warmup Iteration   1: 4.291 ±(99.9%) 0.085 ms/op
Iteration   1: 3.232 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.232 ms/op


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.093 ms/op
Iteration   1: 2.156 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.587 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.724 ms/op
                 createUser·p0.99:   5.060 ms/op
                 createUser·p0.999:  22.681 ms/op
                 createUser·p0.9999: 23.170 ms/op
                 createUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14834
  mean =      2.156 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13368 
    [ 2.500,  5.000) = 1305 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      5.060 ms/op
     p(99.9000) =     22.681 ms/op
     p(99.9900) =     23.170 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.072 ms/op
Iteration   1: 1.744 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   1.903 ms/op
                 existUser·p0.95:   2.138 ms/op
                 existUser·p0.99:   2.753 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 11.928 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18327
  mean =      1.744 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 17994 
    [ 2.500,  3.750) = 201 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      1.903 ms/op
     p(95.0000) =      2.138 ms/op
     p(99.0000) =      2.753 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     11.928 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


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
# Warmup Iteration   1: 3.435 ±(99.9%) 0.104 ms/op
Iteration   1: 1.882 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   1.759 ms/op
                 getUser·p0.90:   2.425 ms/op
                 getUser·p0.95:   2.564 ms/op
                 getUser·p0.99:   3.495 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 11.558 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16981
  mean =      1.882 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 419 
    [ 1.250,  2.500) = 15330 
    [ 2.500,  3.750) = 1095 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.495 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     11.558 ms/op
     p(99.9990) =     11.649 ms/op
     p(99.9999) =     11.649 ms/op
    p(100.0000) =     11.649 ms/op


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
# Warmup Iteration   1: 5.105 ±(99.9%) 0.164 ms/op
Iteration   1: 3.468 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.342 ms/op
                 listUser·p0.90:   4.188 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   13.222 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9225
  mean =      3.468 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1166 
    [ 2.500,  5.000) = 7782 
    [ 5.000,  7.500) = 181 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.188 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =     13.222 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.537          ops/ms
ClientSimple.existUser                       thrpt         12.874          ops/ms
ClientSimple.getUser                         thrpt         14.477          ops/ms
ClientSimple.listUser                        thrpt          8.293          ops/ms
ClientSimple.createUser                       avgt          2.023           ms/op
ClientSimple.existUser                        avgt          2.077           ms/op
ClientSimple.getUser                          avgt          1.844           ms/op
ClientSimple.listUser                         avgt          3.232           ms/op
ClientSimple.createUser                     sample  14834   2.156 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.587           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.060           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.681           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.170           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.265           ms/op
ClientSimple.existUser                      sample  18327   1.744 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.647           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.681           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.903           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.138           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.753           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.731           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.928           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.009           ms/op
ClientSimple.getUser                        sample  16981   1.882 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.710           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.759           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.425           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.495           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.633           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.558           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.649           ms/op
ClientSimple.listUser                       sample   9225   3.468 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.262           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.342           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.188           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.99        sample         13.222           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.120           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.135           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.135           ms/op

Benchmark result is saved to 1710763575167.json
