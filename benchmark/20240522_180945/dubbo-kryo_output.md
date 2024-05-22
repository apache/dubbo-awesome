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
# Warmup Iteration   1: 1.747 ops/ms
Iteration   1: 6.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.237 ops/ms


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
# Warmup Iteration   1: 6.337 ops/ms
Iteration   1: 12.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.447 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.422 ops/ms
Iteration   1: 12.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.670 ops/ms


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
# Warmup Iteration   1: 5.099 ops/ms
Iteration   1: 8.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.607 ops/ms


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
# Warmup Iteration   1: 4.474 ±(99.9%) 0.088 ms/op
Iteration   1: 2.313 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.313 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.059 ms/op
Iteration   1: 1.875 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.875 ms/op


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
# Warmup Iteration   1: 3.139 ±(99.9%) 0.046 ms/op
Iteration   1: 2.192 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.192 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.082 ms/op
Iteration   1: 3.548 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.548 ms/op


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.095 ms/op
Iteration   1: 2.107 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   1.968 ms/op
                 createUser·p0.90:   2.503 ms/op
                 createUser·p0.95:   2.712 ms/op
                 createUser·p0.99:   7.646 ms/op
                 createUser·p0.999:  17.608 ms/op
                 createUser·p0.9999: 18.090 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15159
  mean =      2.107 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 13463 
    [ 2.500,  3.750) = 1321 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      7.646 ms/op
     p(99.9000) =     17.608 ms/op
     p(99.9900) =     18.090 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.072 ms/op
Iteration   1: 1.847 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.388 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  15.870 ms/op
                 existUser·p0.9999: 17.631 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17398
  mean =      1.847 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 999 
    [ 1.250,  2.500) = 15829 
    [ 2.500,  3.750) = 340 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.388 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     15.870 ms/op
     p(99.9900) =     17.631 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.106 ±(99.9%) 0.075 ms/op
Iteration   1: 2.026 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.463 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.691 ms/op
                 getUser·p0.99:   3.207 ms/op
                 getUser·p0.999:  15.970 ms/op
                 getUser·p0.9999: 16.908 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15809
  mean =      2.026 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 339 
    [ 1.250,  2.500) = 13718 
    [ 2.500,  3.750) = 1674 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      3.207 ms/op
     p(99.9000) =     15.970 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 4.608 ±(99.9%) 0.138 ms/op
Iteration   1: 3.173 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   4.901 ms/op
                 listUser·p0.999:  6.012 ms/op
                 listUser·p0.9999: 6.496 ms/op
                 listUser·p1.00:   6.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10085
  mean =      3.173 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 18 
    [1.500, 2.000) = 80 
    [2.000, 2.500) = 1380 
    [2.500, 3.000) = 3608 
    [3.000, 3.500) = 1744 
    [3.500, 4.000) = 1902 
    [4.000, 4.500) = 1040 
    [4.500, 5.000) = 234 
    [5.000, 5.500) = 48 
    [5.500, 6.000) = 18 
    [6.000, 6.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      4.901 ms/op
     p(99.9000) =      6.012 ms/op
     p(99.9900) =      6.496 ms/op
     p(99.9990) =      6.496 ms/op
     p(99.9999) =      6.496 ms/op
    p(100.0000) =      6.496 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.237          ops/ms
ClientSimple.existUser                       thrpt         12.447          ops/ms
ClientSimple.getUser                         thrpt         12.670          ops/ms
ClientSimple.listUser                        thrpt          8.607          ops/ms
ClientSimple.createUser                       avgt          2.313           ms/op
ClientSimple.existUser                        avgt          1.875           ms/op
ClientSimple.getUser                          avgt          2.192           ms/op
ClientSimple.listUser                         avgt          3.548           ms/op
ClientSimple.createUser                     sample  15159   2.107 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.762           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.968           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.503           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.646           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.608           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.090           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.547           ms/op
ClientSimple.existUser                      sample  17398   1.847 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.587           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.858           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.870           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.631           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.727           ms/op
ClientSimple.getUser                        sample  15809   2.026 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.463           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.207           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.970           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.908           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.203           ms/op
ClientSimple.listUser                       sample  10085   3.173 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.978           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.990           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.096           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.901           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.012           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.496           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.496           ms/op

Benchmark result is saved to 1716401125609.json
