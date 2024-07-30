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
# Warmup Iteration   1: 0.837 ops/ms
Iteration   1: 5.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.920 ops/ms


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
# Warmup Iteration   1: 4.836 ops/ms
Iteration   1: 9.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.995 ops/ms


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
# Warmup Iteration   1: 5.993 ops/ms
Iteration   1: 13.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.758 ops/ms


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
# Warmup Iteration   1: 4.070 ops/ms
Iteration   1: 8.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.666 ops/ms


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.074 ms/op
Iteration   1: 2.111 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.111 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.053 ms/op
Iteration   1: 2.095 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.095 ms/op


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
# Warmup Iteration   1: 3.470 ±(99.9%) 0.077 ms/op
Iteration   1: 1.930 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.930 ms/op


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
# Warmup Iteration   1: 5.146 ±(99.9%) 0.101 ms/op
Iteration   1: 3.858 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.858 ms/op


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
# Warmup Iteration   1: 3.551 ±(99.9%) 0.086 ms/op
Iteration   1: 2.333 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.495 ms/op
                 createUser·p0.50:   2.142 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   6.258 ms/op
                 createUser·p0.999:  18.229 ms/op
                 createUser·p0.9999: 18.567 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13703
  mean =      2.333 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 9366 
    [ 2.500,  3.750) = 3816 
    [ 3.750,  5.000) = 138 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      6.258 ms/op
     p(99.9000) =     18.229 ms/op
     p(99.9900) =     18.567 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 3.443 ±(99.9%) 0.088 ms/op
Iteration   1: 2.260 ±(99.9%) 0.045 ms/op
                 existUser·p0.00:   0.454 ms/op
                 existUser·p0.50:   2.126 ms/op
                 existUser·p0.90:   2.826 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   4.562 ms/op
                 existUser·p0.999:  32.565 ms/op
                 existUser·p0.9999: 32.670 ms/op
                 existUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14204
  mean =      2.260 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10899 
    [ 2.500,  5.000) = 3204 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      4.562 ms/op
     p(99.9000) =     32.565 ms/op
     p(99.9900) =     32.670 ms/op
     p(99.9990) =     32.670 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 3.475 ±(99.9%) 0.094 ms/op
Iteration   1: 2.265 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.492 ms/op
                 getUser·p0.50:   2.204 ms/op
                 getUser·p0.90:   2.810 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  17.163 ms/op
                 getUser·p0.9999: 18.557 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14232
  mean =      2.265 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 301 
    [ 1.250,  2.500) = 10336 
    [ 2.500,  3.750) = 3366 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =     17.163 ms/op
     p(99.9900) =     18.557 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.114 ms/op
Iteration   1: 3.203 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   4.021 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.045 ms/op
                 listUser·p0.999:  23.888 ms/op
                 listUser·p0.9999: 25.886 ms/op
                 listUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10002
  mean =      3.203 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1353 
    [ 2.500,  5.000) = 8388 
    [ 5.000,  7.500) = 225 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      4.021 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.045 ms/op
     p(99.9000) =     23.888 ms/op
     p(99.9900) =     25.886 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.920          ops/ms
ClientSimple.existUser                       thrpt          9.995          ops/ms
ClientSimple.getUser                         thrpt         13.758          ops/ms
ClientSimple.listUser                        thrpt          8.666          ops/ms
ClientSimple.createUser                       avgt          2.111           ms/op
ClientSimple.existUser                        avgt          2.095           ms/op
ClientSimple.getUser                          avgt          1.930           ms/op
ClientSimple.listUser                         avgt          3.858           ms/op
ClientSimple.createUser                     sample  13703   2.333 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.495           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.142           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.974           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.183           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.258           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.229           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.567           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.579           ms/op
ClientSimple.existUser                      sample  14204   2.260 ± 0.045   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.454           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.826           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.039           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.562           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.565           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.670           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.670           ms/op
ClientSimple.getUser                        sample  14232   2.265 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.492           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.204           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.850           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.163           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.557           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.612           ms/op
ClientSimple.listUser                       sample  10002   3.203 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.182           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.929           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.021           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.045           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.888           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.886           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.887           ms/op

Benchmark result is saved to 1722298621200.json
