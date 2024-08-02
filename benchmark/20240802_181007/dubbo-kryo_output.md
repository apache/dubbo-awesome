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
# Warmup Iteration   1: 1.745 ops/ms
Iteration   1: 6.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.172 ops/ms


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
# Warmup Iteration   1: 5.943 ops/ms
Iteration   1: 13.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.434 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.157 ops/ms
Iteration   1: 14.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.182 ops/ms


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
# Warmup Iteration   1: 4.363 ops/ms
Iteration   1: 8.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.527 ops/ms


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.064 ms/op
Iteration   1: 2.649 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.649 ms/op


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
# Warmup Iteration   1: 3.109 ±(99.9%) 0.052 ms/op
Iteration   1: 1.841 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.841 ms/op


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
# Warmup Iteration   1: 3.275 ±(99.9%) 0.067 ms/op
Iteration   1: 1.742 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.742 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.161 ±(99.9%) 0.072 ms/op
Iteration   1: 3.169 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.169 ms/op


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.091 ms/op
Iteration   1: 2.278 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.466 ms/op
                 createUser·p0.50:   2.138 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   10.643 ms/op
                 createUser·p0.999:  14.565 ms/op
                 createUser·p0.9999: 14.657 ms/op
                 createUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14039
  mean =      2.278 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 214 
    [ 1.250,  2.500) = 11269 
    [ 2.500,  3.750) = 2285 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =     10.643 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     14.657 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.086 ms/op
Iteration   1: 2.098 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.077 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  10.105 ms/op
                 existUser·p0.9999: 10.461 ms/op
                 existUser·p1.00:   10.469 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15261
  mean =      2.098 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 56 
    [ 1.000,  2.000) = 6519 
    [ 2.000,  3.000) = 8203 
    [ 3.000,  4.000) = 250 
    [ 4.000,  5.000) = 164 
    [ 5.000,  6.000) = 7 
    [ 6.000,  7.000) = 30 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =     10.105 ms/op
     p(99.9900) =     10.461 ms/op
     p(99.9990) =     10.469 ms/op
     p(99.9999) =     10.469 ms/op
    p(100.0000) =     10.469 ms/op


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
# Warmup Iteration   1: 3.393 ±(99.9%) 0.091 ms/op
Iteration   1: 2.110 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   2.093 ms/op
                 getUser·p0.90:   2.634 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   3.383 ms/op
                 getUser·p0.999:  15.165 ms/op
                 getUser·p0.9999: 15.327 ms/op
                 getUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15400
  mean =      2.110 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 296 
    [ 1.250,  2.500) = 12716 
    [ 2.500,  3.750) = 2268 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      3.383 ms/op
     p(99.9000) =     15.165 ms/op
     p(99.9900) =     15.327 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 4.154 ±(99.9%) 0.123 ms/op
Iteration   1: 3.799 ±(99.9%) 0.061 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.774 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  25.952 ms/op
                 listUser·p0.9999: 26.280 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8444
  mean =      3.799 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 354 
    [ 2.500,  5.000) = 7784 
    [ 5.000,  7.500) = 191 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.774 ms/op
     p(99.0000) =      8.298 ms/op
     p(99.9000) =     25.952 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.172          ops/ms
ClientSimple.existUser                       thrpt         13.434          ops/ms
ClientSimple.getUser                         thrpt         14.182          ops/ms
ClientSimple.listUser                        thrpt          8.527          ops/ms
ClientSimple.createUser                       avgt          2.649           ms/op
ClientSimple.existUser                        avgt          1.841           ms/op
ClientSimple.getUser                          avgt          1.742           ms/op
ClientSimple.listUser                         avgt          3.169           ms/op
ClientSimple.createUser                     sample  14039   2.278 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.466           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.138           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.643           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.565           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.657           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.664           ms/op
ClientSimple.existUser                      sample  15261   2.098 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.848           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.077           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.227           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.105           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.461           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.469           ms/op
ClientSimple.getUser                        sample  15400   2.110 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.653           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.093           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.383           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.165           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.327           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.335           ms/op
ClientSimple.listUser                       sample   8444   3.799 ± 0.061   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.290           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.613           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.774           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.298           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.952           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.280           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.280           ms/op

Benchmark result is saved to 1722621941596.json
