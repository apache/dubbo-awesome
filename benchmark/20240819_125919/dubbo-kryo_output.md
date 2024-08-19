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
# Warmup Iteration   1: 1.678 ops/ms
Iteration   1: 7.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.353 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.305 ops/ms
Iteration   1: 11.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.693 ops/ms


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
# Warmup Iteration   1: 5.652 ops/ms
Iteration   1: 11.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.746 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.852 ops/ms
Iteration   1: 8.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.480 ops/ms


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.083 ms/op
Iteration   1: 1.993 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.993 ms/op


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.065 ms/op
Iteration   1: 2.180 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.180 ms/op


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.086 ms/op
Iteration   1: 2.148 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.013 ±(99.9%) 0.097 ms/op
Iteration   1: 3.780 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.780 ms/op


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.114 ms/op
Iteration   1: 2.329 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.367 ms/op
                 createUser·p0.99:   12.321 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 19.976 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13770
  mean =      2.329 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 11266 
    [ 2.500,  3.750) = 1852 
    [ 3.750,  5.000) = 161 
    [ 5.000,  6.250) = 143 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 61 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =     12.321 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     19.976 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.076 ms/op
Iteration   1: 1.792 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.021 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   3.097 ms/op
                 existUser·p0.999:  19.300 ms/op
                 existUser·p0.9999: 19.464 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18129
  mean =      1.792 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 331 
    [ 1.250,  2.500) = 17130 
    [ 2.500,  3.750) = 557 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.021 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      3.097 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     19.464 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.103 ms/op
Iteration   1: 2.162 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   1.974 ms/op
                 getUser·p0.90:   2.810 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  14.680 ms/op
                 getUser·p0.9999: 14.995 ms/op
                 getUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14894
  mean =      2.162 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 12147 
    [ 2.500,  3.750) = 2417 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     14.995 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 4.495 ±(99.9%) 0.185 ms/op
Iteration   1: 3.214 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.527 ms/op
                 listUser·p0.99:   8.197 ms/op
                 listUser·p0.999:  17.334 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9946
  mean =      3.214 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1329 
    [ 2.500,  3.750) = 6652 
    [ 3.750,  5.000) = 1678 
    [ 5.000,  6.250) = 136 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.527 ms/op
     p(99.0000) =      8.197 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.353          ops/ms
ClientSimple.existUser                       thrpt         11.693          ops/ms
ClientSimple.getUser                         thrpt         11.746          ops/ms
ClientSimple.listUser                        thrpt          8.480          ops/ms
ClientSimple.createUser                       avgt          1.993           ms/op
ClientSimple.existUser                        avgt          2.180           ms/op
ClientSimple.getUser                          avgt          2.148           ms/op
ClientSimple.listUser                         avgt          3.780           ms/op
ClientSimple.createUser                     sample  13770   2.329 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.727           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.367           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.321           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.431           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.976           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.988           ms/op
ClientSimple.existUser                      sample  18129   1.792 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.473           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.681           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.021           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.097           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.300           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.464           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.464           ms/op
ClientSimple.getUser                        sample  14894   2.162 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.627           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.974           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.113           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.010           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.680           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.995           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.188           ms/op
ClientSimple.listUser                       sample   9946   3.214 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.059           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.892           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.527           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.197           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.334           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.973           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.973           ms/op

Benchmark result is saved to 1724070868907.json
