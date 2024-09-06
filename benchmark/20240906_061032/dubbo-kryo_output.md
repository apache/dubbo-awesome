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
# Warmup Iteration   1: 1.978 ops/ms
Iteration   1: 6.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.848 ops/ms


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
# Warmup Iteration   1: 6.489 ops/ms
Iteration   1: 13.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.582 ops/ms


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
# Warmup Iteration   1: 5.810 ops/ms
Iteration   1: 14.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.358 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.700 ops/ms
Iteration   1: 9.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.423 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.445 ±(99.9%) 0.051 ms/op
Iteration   1: 2.115 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.115 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.831 ±(99.9%) 0.042 ms/op
Iteration   1: 1.628 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.628 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.396 ±(99.9%) 0.061 ms/op
Iteration   1: 2.102 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.102 ms/op


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
# Warmup Iteration   1: 5.047 ±(99.9%) 0.106 ms/op
Iteration   1: 3.615 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.615 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.364 ±(99.9%) 0.084 ms/op
Iteration   1: 2.151 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   6.617 ms/op
                 createUser·p0.999:  30.676 ms/op
                 createUser·p0.9999: 33.209 ms/op
                 createUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15427
  mean =      2.151 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13431 
    [ 2.500,  5.000) = 1623 
    [ 5.000,  7.500) = 246 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      6.617 ms/op
     p(99.9000) =     30.676 ms/op
     p(99.9900) =     33.209 ms/op
     p(99.9990) =     33.227 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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
# Warmup Iteration   1: 2.891 ±(99.9%) 0.065 ms/op
Iteration   1: 2.059 ±(99.9%) 0.043 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   1.886 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.657 ms/op
                 existUser·p0.99:   4.518 ms/op
                 existUser·p0.999:  32.834 ms/op
                 existUser·p0.9999: 33.700 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15544
  mean =      2.059 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14344 
    [ 2.500,  5.000) = 1085 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.657 ms/op
     p(99.0000) =      4.518 ms/op
     p(99.9000) =     32.834 ms/op
     p(99.9900) =     33.700 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 3.115 ±(99.9%) 0.081 ms/op
Iteration   1: 1.983 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.327 ms/op
                 getUser·p0.95:   2.515 ms/op
                 getUser·p0.99:   4.468 ms/op
                 getUser·p0.999:  19.652 ms/op
                 getUser·p0.9999: 19.890 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16130
  mean =      1.983 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 15100 
    [ 2.500,  3.750) = 640 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      4.468 ms/op
     p(99.9000) =     19.652 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.126 ms/op
Iteration   1: 3.254 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.657 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  12.856 ms/op
                 listUser·p0.9999: 14.172 ms/op
                 listUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9815
  mean =      3.254 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 818 
    [ 2.500,  3.750) = 6933 
    [ 3.750,  5.000) = 1792 
    [ 5.000,  6.250) = 136 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     12.856 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.848          ops/ms
ClientSimple.existUser                       thrpt         13.582          ops/ms
ClientSimple.getUser                         thrpt         14.358          ops/ms
ClientSimple.listUser                        thrpt          9.423          ops/ms
ClientSimple.createUser                       avgt          2.115           ms/op
ClientSimple.existUser                        avgt          1.628           ms/op
ClientSimple.getUser                          avgt          2.102           ms/op
ClientSimple.listUser                         avgt          3.615           ms/op
ClientSimple.createUser                     sample  15427   2.151 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.573           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.617           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.676           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.209           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.227           ms/op
ClientSimple.existUser                      sample  15544   2.059 ± 0.043   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.543           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.886           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.657           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.518           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.834           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.700           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.882           ms/op
ClientSimple.getUser                        sample  16130   1.983 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.524           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.468           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.652           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.890           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.890           ms/op
ClientSimple.listUser                       sample   9815   3.254 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.657           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.941           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.137           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.160           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.856           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.172           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.172           ms/op

Benchmark result is saved to 1725602773377.json
