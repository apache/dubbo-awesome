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
# Warmup Iteration   1: 1.705 ops/ms
Iteration   1: 6.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.993 ops/ms


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
# Warmup Iteration   1: 5.997 ops/ms
Iteration   1: 12.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.412 ops/ms


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
# Warmup Iteration   1: 5.194 ops/ms
Iteration   1: 12.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.797 ops/ms


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
# Warmup Iteration   1: 5.277 ops/ms
Iteration   1: 8.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.780 ops/ms


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.078 ms/op
Iteration   1: 2.296 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.296 ms/op


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
# Warmup Iteration   1: 2.903 ±(99.9%) 0.044 ms/op
Iteration   1: 2.132 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.132 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.047 ms/op
Iteration   1: 1.926 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.926 ms/op


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.101 ms/op
Iteration   1: 3.401 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.401 ms/op


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
# Warmup Iteration   1: 3.543 ±(99.9%) 0.099 ms/op
Iteration   1: 2.147 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.473 ms/op
                 createUser·p0.50:   2.013 ms/op
                 createUser·p0.90:   2.526 ms/op
                 createUser·p0.95:   2.716 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  19.207 ms/op
                 createUser·p0.9999: 20.635 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14862
  mean =      2.147 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13231 
    [ 2.500,  5.000) = 1481 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.526 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     19.207 ms/op
     p(99.9900) =     20.635 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 3.021 ±(99.9%) 0.067 ms/op
Iteration   1: 1.910 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   3.522 ms/op
                 existUser·p0.999:  18.121 ms/op
                 existUser·p0.9999: 18.809 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16750
  mean =      1.910 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 409 
    [ 1.250,  2.500) = 15127 
    [ 2.500,  3.750) = 1060 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.522 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 3.072 ±(99.9%) 0.082 ms/op
Iteration   1: 1.994 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.421 ms/op
                 getUser·p0.50:   1.890 ms/op
                 getUser·p0.90:   2.486 ms/op
                 getUser·p0.95:   2.658 ms/op
                 getUser·p0.99:   4.704 ms/op
                 getUser·p0.999:  15.559 ms/op
                 getUser·p0.9999: 16.159 ms/op
                 getUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16191
  mean =      1.994 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 446 
    [ 1.250,  2.500) = 14213 
    [ 2.500,  3.750) = 1351 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      4.704 ms/op
     p(99.9000) =     15.559 ms/op
     p(99.9900) =     16.159 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 4.669 ±(99.9%) 0.120 ms/op
Iteration   1: 3.251 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   3.088 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.381 ms/op
                 listUser·p0.99:   7.911 ms/op
                 listUser·p0.999:  21.009 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9843
  mean =      3.251 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2413 
    [ 2.500,  5.000) = 7109 
    [ 5.000,  7.500) = 203 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.381 ms/op
     p(99.0000) =      7.911 ms/op
     p(99.9000) =     21.009 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.993          ops/ms
ClientSimple.existUser                       thrpt         12.412          ops/ms
ClientSimple.getUser                         thrpt         12.797          ops/ms
ClientSimple.listUser                        thrpt          8.780          ops/ms
ClientSimple.createUser                       avgt          2.296           ms/op
ClientSimple.existUser                        avgt          2.132           ms/op
ClientSimple.getUser                          avgt          1.926           ms/op
ClientSimple.listUser                         avgt          3.401           ms/op
ClientSimple.createUser                     sample  14862   2.147 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.473           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.013           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.526           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.005           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.207           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.635           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.906           ms/op
ClientSimple.existUser                      sample  16750   1.910 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.712           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.522           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.121           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.809           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.809           ms/op
ClientSimple.getUser                        sample  16191   1.994 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.421           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.890           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.486           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.704           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.559           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.159           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.433           ms/op
ClientSimple.listUser                       sample   9843   3.251 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.870           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.088           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.381           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.911           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.009           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.381           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.381           ms/op

Benchmark result is saved to 1723205217735.json
