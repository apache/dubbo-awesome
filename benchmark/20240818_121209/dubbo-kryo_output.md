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
# Warmup Iteration   1: 1.694 ops/ms
Iteration   1: 6.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.072 ops/ms


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
# Warmup Iteration   1: 6.715 ops/ms
Iteration   1: 13.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.187 ops/ms


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
# Warmup Iteration   1: 6.329 ops/ms
Iteration   1: 13.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.573 ops/ms


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
# Warmup Iteration   1: 4.694 ops/ms
Iteration   1: 8.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.660 ops/ms


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.066 ms/op
Iteration   1: 1.989 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.989 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.051 ms/op
Iteration   1: 2.148 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.148 ms/op


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
# Warmup Iteration   1: 3.684 ±(99.9%) 0.071 ms/op
Iteration   1: 2.011 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.011 ms/op


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.091 ms/op
Iteration   1: 3.719 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.719 ms/op


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
# Warmup Iteration   1: 3.554 ±(99.9%) 0.092 ms/op
Iteration   1: 2.174 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   1.939 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   9.109 ms/op
                 createUser·p0.999:  17.780 ms/op
                 createUser·p0.9999: 18.418 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14704
  mean =      2.174 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 252 
    [ 1.250,  2.500) = 12061 
    [ 2.500,  3.750) = 2003 
    [ 3.750,  5.000) = 132 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      9.109 ms/op
     p(99.9000) =     17.780 ms/op
     p(99.9900) =     18.418 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.073 ms/op
Iteration   1: 1.932 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   5.271 ms/op
                 existUser·p0.999:  21.463 ms/op
                 existUser·p0.9999: 22.294 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16558
  mean =      1.932 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15730 
    [ 2.500,  5.000) = 635 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      5.271 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     22.294 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.098 ms/op
Iteration   1: 2.022 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.503 ms/op
                 getUser·p0.50:   1.911 ms/op
                 getUser·p0.90:   2.515 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   3.039 ms/op
                 getUser·p0.999:  13.274 ms/op
                 getUser·p0.9999: 13.475 ms/op
                 getUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15810
  mean =      2.022 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 13995 
    [ 2.500,  3.750) = 1589 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.039 ms/op
     p(99.9000) =     13.274 ms/op
     p(99.9900) =     13.475 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


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
# Warmup Iteration   1: 4.503 ±(99.9%) 0.158 ms/op
Iteration   1: 3.270 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  11.476 ms/op
                 listUser·p0.9999: 11.715 ms/op
                 listUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9791
  mean =      3.270 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 489 
    [ 2.500,  3.750) = 7445 
    [ 3.750,  5.000) = 1576 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     11.476 ms/op
     p(99.9900) =     11.715 ms/op
     p(99.9990) =     11.715 ms/op
     p(99.9999) =     11.715 ms/op
    p(100.0000) =     11.715 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.072          ops/ms
ClientSimple.existUser                       thrpt         13.187          ops/ms
ClientSimple.getUser                         thrpt         13.573          ops/ms
ClientSimple.listUser                        thrpt          8.660          ops/ms
ClientSimple.createUser                       avgt          1.989           ms/op
ClientSimple.existUser                        avgt          2.148           ms/op
ClientSimple.getUser                          avgt          2.011           ms/op
ClientSimple.listUser                         avgt          3.719           ms/op
ClientSimple.createUser                     sample  14704   2.174 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.817           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.939           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.109           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.780           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.418           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.448           ms/op
ClientSimple.existUser                      sample  16558   1.932 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.631           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.759           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.271           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.463           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.294           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.315           ms/op
ClientSimple.getUser                        sample  15810   2.022 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.503           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.911           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.039           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.274           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.475           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.484           ms/op
ClientSimple.listUser                       sample   9791   3.270 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.397           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.006           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.225           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.476           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.715           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.715           ms/op

Benchmark result is saved to 1723982868468.json
