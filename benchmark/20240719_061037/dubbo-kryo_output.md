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
# Warmup Iteration   1: 1.827 ops/ms
Iteration   1: 6.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.719 ops/ms


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
# Warmup Iteration   1: 5.822 ops/ms
Iteration   1: 12.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.037 ops/ms


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
# Warmup Iteration   1: 6.044 ops/ms
Iteration   1: 12.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.087 ops/ms


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
# Warmup Iteration   1: 3.057 ops/ms
Iteration   1: 7.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.479 ops/ms


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.063 ms/op
Iteration   1: 2.195 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.195 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.052 ms/op
Iteration   1: 1.787 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.787 ms/op


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
# Warmup Iteration   1: 3.486 ±(99.9%) 0.061 ms/op
Iteration   1: 2.048 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.048 ms/op


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.101 ms/op
Iteration   1: 3.095 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.095 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.098 ms/op
Iteration   1: 1.994 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.432 ms/op
                 createUser·p0.50:   1.804 ms/op
                 createUser·p0.90:   2.384 ms/op
                 createUser·p0.95:   2.691 ms/op
                 createUser·p0.99:   7.528 ms/op
                 createUser·p0.999:  16.563 ms/op
                 createUser·p0.9999: 16.653 ms/op
                 createUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16056
  mean =      1.994 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 764 
    [ 1.250,  2.500) = 14073 
    [ 2.500,  3.750) = 776 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     16.563 ms/op
     p(99.9900) =     16.653 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 2.565 ±(99.9%) 0.054 ms/op
Iteration   1: 1.842 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.377 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   2.228 ms/op
                 existUser·p0.95:   2.400 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  22.381 ms/op
                 existUser·p0.9999: 22.875 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17819
  mean =      1.842 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17157 
    [ 2.500,  5.000) = 562 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      3.363 ms/op
     p(99.9000) =     22.381 ms/op
     p(99.9900) =     22.875 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 3.381 ±(99.9%) 0.077 ms/op
Iteration   1: 1.831 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   1.698 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.613 ms/op
                 getUser·p0.99:   3.081 ms/op
                 getUser·p0.999:  14.114 ms/op
                 getUser·p0.9999: 14.781 ms/op
                 getUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17573
  mean =      1.831 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 657 
    [ 1.250,  2.500) = 15640 
    [ 2.500,  3.750) = 1201 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.081 ms/op
     p(99.9000) =     14.114 ms/op
     p(99.9900) =     14.781 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.142 ms/op
Iteration   1: 3.647 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.828 ms/op
                 listUser·p0.999:  15.159 ms/op
                 listUser·p0.9999: 15.221 ms/op
                 listUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8776
  mean =      3.647 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 547 
    [ 2.500,  3.750) = 4674 
    [ 3.750,  5.000) = 3248 
    [ 5.000,  6.250) = 169 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.828 ms/op
     p(99.9000) =     15.159 ms/op
     p(99.9900) =     15.221 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.719          ops/ms
ClientSimple.existUser                       thrpt         12.037          ops/ms
ClientSimple.getUser                         thrpt         12.087          ops/ms
ClientSimple.listUser                        thrpt          7.479          ops/ms
ClientSimple.createUser                       avgt          2.195           ms/op
ClientSimple.existUser                        avgt          1.787           ms/op
ClientSimple.getUser                          avgt          2.048           ms/op
ClientSimple.listUser                         avgt          3.095           ms/op
ClientSimple.createUser                     sample  16056   1.994 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.432           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.804           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.384           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.528           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.563           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.653           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.663           ms/op
ClientSimple.existUser                      sample  17819   1.842 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.377           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.679           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.363           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.381           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.875           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.003           ms/op
ClientSimple.getUser                        sample  17573   1.831 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.707           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.698           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.081           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.114           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.781           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.893           ms/op
ClientSimple.listUser                       sample   8776   3.647 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.092           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.617           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.828           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.159           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.221           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.221           ms/op

Benchmark result is saved to 1721369165922.json
