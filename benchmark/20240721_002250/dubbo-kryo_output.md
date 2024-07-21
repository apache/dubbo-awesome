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
# Warmup Iteration   1: 1.204 ops/ms
Iteration   1: 6.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.415 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.336 ops/ms
Iteration   1: 12.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.083 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.459 ops/ms
Iteration   1: 11.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.245 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ops/ms
Iteration   1: 8.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.396 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.863 ±(99.9%) 0.107 ms/op
Iteration   1: 2.416 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.416 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.246 ±(99.9%) 0.060 ms/op
Iteration   1: 1.930 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ±(99.9%) 0.074 ms/op
Iteration   1: 2.192 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.192 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.538 ±(99.9%) 0.142 ms/op
Iteration   1: 3.688 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.688 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.106 ms/op
Iteration   1: 2.589 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.331 ms/op
                 createUser·p0.90:   3.219 ms/op
                 createUser·p0.95:   3.547 ms/op
                 createUser·p0.99:   8.025 ms/op
                 createUser·p0.999:  36.504 ms/op
                 createUser·p0.9999: 36.619 ms/op
                 createUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12339
  mean =      2.589 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7411 
    [ 2.500,  5.000) = 4712 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.331 ms/op
     p(90.0000) =      3.219 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      8.025 ms/op
     p(99.9000) =     36.504 ms/op
     p(99.9900) =     36.619 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 3.520 ±(99.9%) 0.104 ms/op
Iteration   1: 1.924 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.810 ms/op
                 existUser·p0.99:   3.759 ms/op
                 existUser·p0.999:  12.894 ms/op
                 existUser·p0.9999: 13.195 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16630
  mean =      1.924 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 14871 
    [ 2.500,  3.750) = 1470 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      3.759 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     13.195 ms/op
     p(99.9990) =     13.206 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.090 ms/op
Iteration   1: 2.150 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   1.952 ms/op
                 getUser·p0.90:   2.679 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  22.708 ms/op
                 getUser·p0.9999: 22.823 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14986
  mean =      2.150 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12888 
    [ 2.500,  5.000) = 1966 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     22.823 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 5.131 ±(99.9%) 0.172 ms/op
Iteration   1: 3.499 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.084 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  22.048 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9148
  mean =      3.499 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1414 
    [ 2.500,  5.000) = 7243 
    [ 5.000,  7.500) = 386 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.084 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     22.048 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.415          ops/ms
ClientSimple.existUser                       thrpt         12.083          ops/ms
ClientSimple.getUser                         thrpt         11.245          ops/ms
ClientSimple.listUser                        thrpt          8.396          ops/ms
ClientSimple.createUser                       avgt          2.416           ms/op
ClientSimple.existUser                        avgt          1.930           ms/op
ClientSimple.getUser                          avgt          2.192           ms/op
ClientSimple.listUser                         avgt          3.688           ms/op
ClientSimple.createUser                     sample  12339   2.589 ± 0.061   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.856           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.331           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.219           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.547           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.025           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.504           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.619           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.635           ms/op
ClientSimple.existUser                      sample  16630   1.924 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.517           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.759           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.894           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.195           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.206           ms/op
ClientSimple.getUser                        sample  14986   2.150 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.807           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.952           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.084           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.407           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.708           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.823           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.839           ms/op
ClientSimple.listUser                       sample   9148   3.499 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.959           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.084           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.322           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.048           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.774           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.774           ms/op

Benchmark result is saved to 1721521108733.json
