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
# Warmup Iteration   1: 1.760 ops/ms
Iteration   1: 8.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.606 ops/ms


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
# Warmup Iteration   1: 6.006 ops/ms
Iteration   1: 14.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.106 ops/ms


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
# Warmup Iteration   1: 5.956 ops/ms
Iteration   1: 12.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.542 ops/ms


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
# Warmup Iteration   1: 5.077 ops/ms
Iteration   1: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.725 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ±(99.9%) 0.066 ms/op
Iteration   1: 2.072 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.072 ms/op


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
# Warmup Iteration   1: 3.027 ±(99.9%) 0.068 ms/op
Iteration   1: 2.210 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.210 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.060 ms/op
Iteration   1: 1.839 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.839 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ±(99.9%) 0.101 ms/op
Iteration   1: 3.222 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.222 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.185 ±(99.9%) 0.097 ms/op
Iteration   1: 2.378 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   1.974 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   4.535 ms/op
                 createUser·p0.99:   9.699 ms/op
                 createUser·p0.999:  35.915 ms/op
                 createUser·p0.9999: 37.831 ms/op
                 createUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13488
  mean =      2.378 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10292 
    [ 2.500,  5.000) = 2596 
    [ 5.000,  7.500) = 378 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      4.535 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     35.915 ms/op
     p(99.9900) =     37.831 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 3.313 ±(99.9%) 0.086 ms/op
Iteration   1: 1.862 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   1.737 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.224 ms/op
                 existUser·p0.999:  14.451 ms/op
                 existUser·p0.9999: 15.102 ms/op
                 existUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17247
  mean =      1.862 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 16309 
    [ 2.500,  3.750) = 675 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.224 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     15.102 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 3.220 ±(99.9%) 0.078 ms/op
Iteration   1: 2.225 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.519 ms/op
                 getUser·p0.50:   2.097 ms/op
                 getUser·p0.90:   2.789 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 20.746 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14400
  mean =      2.225 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11527 
    [ 2.500,  5.000) = 2775 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     20.746 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 4.464 ±(99.9%) 0.134 ms/op
Iteration   1: 3.370 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.981 ms/op
                 listUser·p0.999:  7.688 ms/op
                 listUser·p0.9999: 9.077 ms/op
                 listUser·p1.00:   9.077 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9484
  mean =      3.370 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 88 
    [ 2.000,  3.000) = 3303 
    [ 3.000,  4.000) = 4692 
    [ 4.000,  5.000) = 1159 
    [ 5.000,  6.000) = 148 
    [ 6.000,  7.000) = 50 
    [ 7.000,  8.000) = 38 
    [ 8.000,  9.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.981 ms/op
     p(99.9000) =      7.688 ms/op
     p(99.9900) =      9.077 ms/op
     p(99.9990) =      9.077 ms/op
     p(99.9999) =      9.077 ms/op
    p(100.0000) =      9.077 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.606          ops/ms
ClientSimple.existUser                       thrpt         14.106          ops/ms
ClientSimple.getUser                         thrpt         12.542          ops/ms
ClientSimple.listUser                        thrpt          8.725          ops/ms
ClientSimple.createUser                       avgt          2.072           ms/op
ClientSimple.existUser                        avgt          2.210           ms/op
ClientSimple.getUser                          avgt          1.839           ms/op
ClientSimple.listUser                         avgt          3.222           ms/op
ClientSimple.createUser                     sample  13488   2.378 ± 0.059   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.508           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.974           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.535           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.699           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.915           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.831           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.945           ms/op
ClientSimple.existUser                      sample  17247   1.862 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.690           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.737           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.224           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.451           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.102           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.221           ms/op
ClientSimple.getUser                        sample  14400   2.225 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.519           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.097           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.084           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.243           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.152           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.746           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.775           ms/op
ClientSimple.listUser                       sample   9484   3.370 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.762           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.981           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.688           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.077           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.077           ms/op

Benchmark result is saved to 1717028176837.json
