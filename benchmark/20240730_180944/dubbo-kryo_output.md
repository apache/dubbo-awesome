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
# Warmup Iteration   1: 1.623 ops/ms
Iteration   1: 6.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.676 ops/ms


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
# Warmup Iteration   1: 5.420 ops/ms
Iteration   1: 11.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.789 ops/ms


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
# Warmup Iteration   1: 5.742 ops/ms
Iteration   1: 12.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.707 ops/ms


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
# Warmup Iteration   1: 5.394 ops/ms
Iteration   1: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.637 ops/ms


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
# Warmup Iteration   1: 4.533 ±(99.9%) 0.084 ms/op
Iteration   1: 2.492 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.492 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.076 ms/op
Iteration   1: 1.810 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.810 ms/op


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
# Warmup Iteration   1: 3.439 ±(99.9%) 0.055 ms/op
Iteration   1: 2.007 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.007 ms/op


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
# Warmup Iteration   1: 4.606 ±(99.9%) 0.072 ms/op
Iteration   1: 3.716 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.716 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.085 ms/op
Iteration   1: 2.184 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   2.034 ms/op
                 createUser·p0.90:   2.564 ms/op
                 createUser·p0.95:   2.859 ms/op
                 createUser·p0.99:   9.322 ms/op
                 createUser·p0.999:  33.554 ms/op
                 createUser·p0.9999: 35.130 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14813
  mean =      2.184 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12900 
    [ 2.500,  5.000) = 1646 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     33.554 ms/op
     p(99.9900) =     35.130 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 3.031 ±(99.9%) 0.067 ms/op
Iteration   1: 2.046 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.525 ms/op
                 existUser·p0.50:   1.913 ms/op
                 existUser·p0.90:   2.621 ms/op
                 existUser·p0.95:   2.847 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  16.079 ms/op
                 existUser·p0.9999: 16.190 ms/op
                 existUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15636
  mean =      2.046 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 499 
    [ 1.250,  2.500) = 12668 
    [ 2.500,  3.750) = 2359 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      3.416 ms/op
     p(99.9000) =     16.079 ms/op
     p(99.9900) =     16.190 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.094 ms/op
Iteration   1: 2.118 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   2.011 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  10.860 ms/op
                 getUser·p0.9999: 11.606 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15150
  mean =      2.118 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 13070 
    [ 2.500,  3.750) = 1777 
    [ 3.750,  5.000) = 179 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =     10.860 ms/op
     p(99.9900) =     11.606 ms/op
     p(99.9990) =     11.665 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


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
# Warmup Iteration   1: 6.006 ±(99.9%) 0.151 ms/op
Iteration   1: 3.645 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   6.539 ms/op
                 listUser·p0.999:  24.790 ms/op
                 listUser·p0.9999: 28.738 ms/op
                 listUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8779
  mean =      3.645 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 691 
    [ 2.500,  5.000) = 7761 
    [ 5.000,  7.500) = 263 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.539 ms/op
     p(99.9000) =     24.790 ms/op
     p(99.9900) =     28.738 ms/op
     p(99.9990) =     28.738 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.676          ops/ms
ClientSimple.existUser                       thrpt         11.789          ops/ms
ClientSimple.getUser                         thrpt         12.707          ops/ms
ClientSimple.listUser                        thrpt          8.637          ops/ms
ClientSimple.createUser                       avgt          2.492           ms/op
ClientSimple.existUser                        avgt          1.810           ms/op
ClientSimple.getUser                          avgt          2.007           ms/op
ClientSimple.listUser                         avgt          3.716           ms/op
ClientSimple.createUser                     sample  14813   2.184 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.560           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.034           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.859           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.322           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.554           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.130           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.193           ms/op
ClientSimple.existUser                      sample  15636   2.046 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.525           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.913           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.847           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.416           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.079           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.190           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.237           ms/op
ClientSimple.getUser                        sample  15150   2.118 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.009           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.011           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.473           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.860           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.606           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.665           ms/op
ClientSimple.listUser                       sample   8779   3.645 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.948           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.768           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.539           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.790           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.738           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.738           ms/op

Benchmark result is saved to 1722362716246.json
