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
# Warmup Iteration   1: 1.515 ops/ms
Iteration   1: 6.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.398 ops/ms


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
# Warmup Iteration   1: 5.985 ops/ms
Iteration   1: 12.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.919 ops/ms


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
# Warmup Iteration   1: 5.445 ops/ms
Iteration   1: 12.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.274 ops/ms


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
# Warmup Iteration   1: 4.852 ops/ms
Iteration   1: 8.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.101 ops/ms


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.079 ms/op
Iteration   1: 2.012 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.012 ms/op


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
# Warmup Iteration   1: 3.613 ±(99.9%) 0.066 ms/op
Iteration   1: 2.143 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.143 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.057 ms/op
Iteration   1: 1.933 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.933 ms/op


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.101 ms/op
Iteration   1: 3.506 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.506 ms/op


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.098 ms/op
Iteration   1: 2.207 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.875 ms/op
                 createUser·p0.99:   6.313 ms/op
                 createUser·p0.999:  19.923 ms/op
                 createUser·p0.9999: 20.465 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14510
  mean =      2.207 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12700 
    [ 2.500,  5.000) = 1586 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      6.313 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     20.465 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.067 ms/op
Iteration   1: 1.913 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.373 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.859 ms/op
                 existUser·p0.99:   3.725 ms/op
                 existUser·p0.999:  13.648 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16683
  mean =      1.913 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 14937 
    [ 2.500,  3.750) = 1458 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      3.725 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.097 ms/op
Iteration   1: 1.953 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   1.753 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 20.241 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16492
  mean =      1.953 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15227 
    [ 2.500,  5.000) = 1146 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     20.241 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.141 ms/op
Iteration   1: 3.785 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   9.536 ms/op
                 listUser·p0.999:  13.984 ms/op
                 listUser·p0.9999: 14.254 ms/op
                 listUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8493
  mean =      3.785 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 502 
    [ 2.500,  3.750) = 4022 
    [ 3.750,  5.000) = 3361 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      9.536 ms/op
     p(99.9000) =     13.984 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.398          ops/ms
ClientSimple.existUser                       thrpt         12.919          ops/ms
ClientSimple.getUser                         thrpt         12.274          ops/ms
ClientSimple.listUser                        thrpt          8.101          ops/ms
ClientSimple.createUser                       avgt          2.012           ms/op
ClientSimple.existUser                        avgt          2.143           ms/op
ClientSimple.getUser                          avgt          1.933           ms/op
ClientSimple.listUser                         avgt          3.506           ms/op
ClientSimple.createUser                     sample  14510   2.207 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.649           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.313           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.923           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.465           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.480           ms/op
ClientSimple.existUser                      sample  16683   1.913 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.373           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.747           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.859           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.725           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.648           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.992           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.992           ms/op
ClientSimple.getUser                        sample  16492   1.953 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.693           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.753           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.744           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.054           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.241           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.283           ms/op
ClientSimple.listUser                       sample   8493   3.785 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.403           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.695           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.536           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.984           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.254           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.254           ms/op

Benchmark result is saved to 1721650024678.json
