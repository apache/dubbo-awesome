# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.897 ops/ms
Iteration   1: 7.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.057 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.627 ops/ms
Iteration   1: 12.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.864 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.221 ops/ms
Iteration   1: 15.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.061 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.621 ops/ms
Iteration   1: 8.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.464 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.998 ±(99.9%) 0.079 ms/op
Iteration   1: 2.106 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.468 ±(99.9%) 0.054 ms/op
Iteration   1: 2.052 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.052 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.007 ±(99.9%) 0.049 ms/op
Iteration   1: 1.922 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.922 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.666 ±(99.9%) 0.117 ms/op
Iteration   1: 3.819 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.819 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.490 ±(99.9%) 0.086 ms/op
Iteration   1: 2.090 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   1.876 ms/op
                 createUser·p0.90:   2.482 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  20.120 ms/op
                 createUser·p0.9999: 20.411 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15298
  mean =      2.090 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13856 
    [ 2.500,  5.000) = 1262 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     20.411 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ±(99.9%) 0.066 ms/op
Iteration   1: 2.142 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.044 ms/op
                 existUser·p0.90:   2.552 ms/op
                 existUser·p0.95:   2.699 ms/op
                 existUser·p0.99:   3.913 ms/op
                 existUser·p0.999:  21.791 ms/op
                 existUser·p0.9999: 22.415 ms/op
                 existUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14929
  mean =      2.142 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12990 
    [ 2.500,  5.000) = 1802 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.044 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.913 ms/op
     p(99.9000) =     21.791 ms/op
     p(99.9900) =     22.415 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.266 ±(99.9%) 0.090 ms/op
Iteration   1: 2.043 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   1.978 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 12.284 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15668
  mean =      2.043 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 643 
    [ 1.250,  2.500) = 12873 
    [ 2.500,  3.750) = 1958 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     12.284 ms/op
     p(99.9990) =     12.321 ms/op
     p(99.9999) =     12.321 ms/op
    p(100.0000) =     12.321 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.266 ±(99.9%) 0.113 ms/op
Iteration   1: 3.324 ±(99.9%) 0.081 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.133 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  40.591 ms/op
                 listUser·p0.9999: 42.336 ms/op
                 listUser·p1.00:   42.336 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9623
  mean =      3.324 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9468 
    [ 5.000, 10.000) = 91 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 14 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     40.591 ms/op
     p(99.9900) =     42.336 ms/op
     p(99.9990) =     42.336 ms/op
     p(99.9999) =     42.336 ms/op
    p(100.0000) =     42.336 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.057          ops/ms
ClientSimple.existUser                       thrpt         12.864          ops/ms
ClientSimple.getUser                         thrpt         15.061          ops/ms
ClientSimple.listUser                        thrpt          8.464          ops/ms
ClientSimple.createUser                       avgt          2.106           ms/op
ClientSimple.existUser                        avgt          2.052           ms/op
ClientSimple.getUser                          avgt          1.922           ms/op
ClientSimple.listUser                         avgt          3.819           ms/op
ClientSimple.createUser                     sample  15298   2.090 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.118           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.876           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.482           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.054           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.120           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.411           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.480           ms/op
ClientSimple.existUser                      sample  14929   2.142 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.440           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.044           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.552           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.913           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.791           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.415           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.544           ms/op
ClientSimple.getUser                        sample  15668   2.043 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.490           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.978           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.481           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.091           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.284           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.321           ms/op
ClientSimple.listUser                       sample   9623   3.324 ± 0.081   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.861           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.023           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.908           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.133           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.743           ms/op
ClientSimple.listUser:listUser·p0.999       sample         40.591           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         42.336           ms/op
ClientSimple.listUser:listUser·p1.00        sample         42.336           ms/op

Benchmark result is saved to 1718690749341.json
