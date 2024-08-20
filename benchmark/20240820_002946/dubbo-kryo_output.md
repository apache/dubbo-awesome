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
# Warmup Iteration   1: 1.874 ops/ms
Iteration   1: 7.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.637 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.747 ops/ms
Iteration   1: 13.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.429 ops/ms


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
# Warmup Iteration   1: 6.000 ops/ms
Iteration   1: 13.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.816 ops/ms


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
# Warmup Iteration   1: 4.410 ops/ms
Iteration   1: 8.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.793 ops/ms


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.072 ms/op
Iteration   1: 2.517 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.517 ms/op


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
# Warmup Iteration   1: 3.083 ±(99.9%) 0.044 ms/op
Iteration   1: 2.102 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.267 ±(99.9%) 0.054 ms/op
Iteration   1: 1.847 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.847 ms/op


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.078 ms/op
Iteration   1: 3.453 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.453 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.094 ms/op
Iteration   1: 2.084 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.375 ms/op
                 createUser·p0.50:   1.903 ms/op
                 createUser·p0.90:   2.535 ms/op
                 createUser·p0.95:   2.836 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  30.856 ms/op
                 createUser·p0.9999: 31.651 ms/op
                 createUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15469
  mean =      2.084 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13782 
    [ 2.500,  5.000) = 1360 
    [ 5.000,  7.500) = 145 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.836 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     30.856 ms/op
     p(99.9900) =     31.651 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 3.004 ±(99.9%) 0.068 ms/op
Iteration   1: 1.955 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.541 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  31.783 ms/op
                 existUser·p0.9999: 32.738 ms/op
                 existUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16356
  mean =      1.955 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14746 
    [ 2.500,  5.000) = 1546 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =     31.783 ms/op
     p(99.9900) =     32.738 ms/op
     p(99.9990) =     32.801 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.101 ms/op
Iteration   1: 1.856 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.270 ms/op
                 getUser·p0.50:   1.651 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  10.744 ms/op
                 getUser·p0.9999: 11.657 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17209
  mean =      1.856 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 640 
    [ 1.250,  2.500) = 14436 
    [ 2.500,  3.750) = 1969 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.270 ms/op
     p(50.0000) =      1.651 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =     10.744 ms/op
     p(99.9900) =     11.657 ms/op
     p(99.9990) =     11.764 ms/op
     p(99.9999) =     11.764 ms/op
    p(100.0000) =     11.764 ms/op


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
# Warmup Iteration   1: 4.948 ±(99.9%) 0.133 ms/op
Iteration   1: 3.603 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  20.189 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8874
  mean =      3.603 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 384 
    [ 2.500,  5.000) = 8285 
    [ 5.000,  7.500) = 137 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     20.189 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.637          ops/ms
ClientSimple.existUser                       thrpt         13.429          ops/ms
ClientSimple.getUser                         thrpt         13.816          ops/ms
ClientSimple.listUser                        thrpt          8.793          ops/ms
ClientSimple.createUser                       avgt          2.517           ms/op
ClientSimple.existUser                        avgt          2.102           ms/op
ClientSimple.getUser                          avgt          1.847           ms/op
ClientSimple.listUser                         avgt          3.453           ms/op
ClientSimple.createUser                     sample  15469   2.084 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.375           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.903           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.836           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.184           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.856           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.651           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.687           ms/op
ClientSimple.existUser                      sample  16356   1.955 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.541           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.829           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.543           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.783           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.738           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.801           ms/op
ClientSimple.getUser                        sample  17209   1.856 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.270           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.651           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.740           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.744           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.657           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.764           ms/op
ClientSimple.listUser                       sample   8874   3.603 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.063           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.572           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.447           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.189           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.414           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.414           ms/op

Benchmark result is saved to 1724113008980.json
