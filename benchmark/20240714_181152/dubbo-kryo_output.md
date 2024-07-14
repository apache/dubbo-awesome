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
# Warmup Iteration   1: 0.956 ops/ms
Iteration   1: 6.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.081 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.574 ops/ms
Iteration   1: 12.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.296 ops/ms


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
# Warmup Iteration   1: 6.115 ops/ms
Iteration   1: 13.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.914 ops/ms


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
# Warmup Iteration   1: 4.836 ops/ms
Iteration   1: 8.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.418 ops/ms


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.077 ms/op
Iteration   1: 2.266 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.266 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.069 ms/op
Iteration   1: 2.225 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.225 ms/op


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
# Warmup Iteration   1: 3.292 ±(99.9%) 0.060 ms/op
Iteration   1: 2.201 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.201 ms/op


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
# Warmup Iteration   1: 4.899 ±(99.9%) 0.095 ms/op
Iteration   1: 3.425 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.425 ms/op


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
# Warmup Iteration   1: 3.729 ±(99.9%) 0.089 ms/op
Iteration   1: 2.289 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   2.093 ms/op
                 createUser·p0.90:   2.781 ms/op
                 createUser·p0.95:   2.966 ms/op
                 createUser·p0.99:   8.071 ms/op
                 createUser·p0.999:  29.164 ms/op
                 createUser·p0.9999: 30.311 ms/op
                 createUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13976
  mean =      2.289 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10797 
    [ 2.500,  5.000) = 2942 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      8.071 ms/op
     p(99.9000) =     29.164 ms/op
     p(99.9900) =     30.311 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 2.833 ±(99.9%) 0.065 ms/op
Iteration   1: 2.064 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.541 ms/op
                 existUser·p0.50:   1.954 ms/op
                 existUser·p0.90:   2.540 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  25.639 ms/op
                 existUser·p0.9999: 25.919 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15562
  mean =      2.064 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13666 
    [ 2.500,  5.000) = 1788 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =     25.639 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 3.353 ±(99.9%) 0.084 ms/op
Iteration   1: 2.166 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.474 ms/op
                 getUser·p0.50:   2.083 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.785 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  17.536 ms/op
                 getUser·p0.9999: 18.253 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14838
  mean =      2.166 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 12353 
    [ 2.500,  3.750) = 2187 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =     17.536 ms/op
     p(99.9900) =     18.253 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.125 ms/op
Iteration   1: 3.352 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.712 ms/op
                 listUser·p0.50:   3.178 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.486 ms/op
                 listUser·p0.99:   5.699 ms/op
                 listUser·p0.999:  17.088 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9526
  mean =      3.352 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 764 
    [ 2.500,  3.750) = 5711 
    [ 3.750,  5.000) = 2833 
    [ 5.000,  6.250) = 141 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.486 ms/op
     p(99.0000) =      5.699 ms/op
     p(99.9000) =     17.088 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.081          ops/ms
ClientSimple.existUser                       thrpt         12.296          ops/ms
ClientSimple.getUser                         thrpt         13.914          ops/ms
ClientSimple.listUser                        thrpt          8.418          ops/ms
ClientSimple.createUser                       avgt          2.266           ms/op
ClientSimple.existUser                        avgt          2.225           ms/op
ClientSimple.getUser                          avgt          2.201           ms/op
ClientSimple.listUser                         avgt          3.425           ms/op
ClientSimple.createUser                     sample  13976   2.289 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.641           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.093           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.071           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.164           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.311           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.376           ms/op
ClientSimple.existUser                      sample  15562   2.064 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.541           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.954           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.834           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.639           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.919           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.919           ms/op
ClientSimple.getUser                        sample  14838   2.166 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.474           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.083           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.785           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.932           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.536           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.253           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.285           ms/op
ClientSimple.listUser                       sample   9526   3.352 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.712           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.178           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.186           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.486           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.699           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.088           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.727           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.727           ms/op

Benchmark result is saved to 1720980458346.json
