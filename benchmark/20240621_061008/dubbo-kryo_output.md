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
# Warmup Iteration   1: 1.755 ops/ms
Iteration   1: 6.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.851 ops/ms


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
# Warmup Iteration   1: 6.294 ops/ms
Iteration   1: 15.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.283 ops/ms


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
# Warmup Iteration   1: 5.586 ops/ms
Iteration   1: 12.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.419 ops/ms


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
# Warmup Iteration   1: 5.461 ops/ms
Iteration   1: 8.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.750 ops/ms


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
# Warmup Iteration   1: 3.821 ±(99.9%) 0.074 ms/op
Iteration   1: 2.155 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.155 ms/op


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
# Warmup Iteration   1: 3.444 ±(99.9%) 0.069 ms/op
Iteration   1: 2.313 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.083 ±(99.9%) 0.059 ms/op
Iteration   1: 1.869 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.869 ms/op


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.118 ms/op
Iteration   1: 3.600 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.600 ms/op


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
# Warmup Iteration   1: 3.625 ±(99.9%) 0.094 ms/op
Iteration   1: 2.184 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   1.911 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  30.617 ms/op
                 createUser·p0.9999: 31.773 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14637
  mean =      2.184 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12412 
    [ 2.500,  5.000) = 2013 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     30.617 ms/op
     p(99.9900) =     31.773 ms/op
     p(99.9990) =     32.244 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 3.439 ±(99.9%) 0.082 ms/op
Iteration   1: 2.011 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   1.913 ms/op
                 existUser·p0.90:   2.666 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   4.195 ms/op
                 existUser·p0.999:  10.355 ms/op
                 existUser·p0.9999: 12.233 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15996
  mean =      2.011 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 328 
    [ 1.250,  2.500) = 13682 
    [ 2.500,  3.750) = 1752 
    [ 3.750,  5.000) = 132 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      4.195 ms/op
     p(99.9000) =     10.355 ms/op
     p(99.9900) =     12.233 ms/op
     p(99.9990) =     12.812 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.094 ms/op
Iteration   1: 2.079 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.492 ms/op
                 getUser·p0.50:   1.878 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   3.015 ms/op
                 getUser·p0.99:   5.552 ms/op
                 getUser·p0.999:  30.507 ms/op
                 getUser·p0.9999: 31.206 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15327
  mean =      2.079 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13484 
    [ 2.500,  5.000) = 1657 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      5.552 ms/op
     p(99.9000) =     30.507 ms/op
     p(99.9900) =     31.206 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.132 ms/op
Iteration   1: 3.642 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   8.355 ms/op
                 listUser·p0.999:  19.923 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8803
  mean =      3.642 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 485 
    [ 2.500,  5.000) = 7966 
    [ 5.000,  7.500) = 246 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      8.355 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.851          ops/ms
ClientSimple.existUser                       thrpt         15.283          ops/ms
ClientSimple.getUser                         thrpt         12.419          ops/ms
ClientSimple.listUser                        thrpt          8.750          ops/ms
ClientSimple.createUser                       avgt          2.155           ms/op
ClientSimple.existUser                        avgt          2.313           ms/op
ClientSimple.getUser                          avgt          1.869           ms/op
ClientSimple.listUser                         avgt          3.600           ms/op
ClientSimple.createUser                     sample  14637   2.184 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.886           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.911           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.684           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.617           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.773           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.244           ms/op
ClientSimple.existUser                      sample  15996   2.011 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.647           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.913           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.666           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.023           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.195           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.355           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.233           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.812           ms/op
ClientSimple.getUser                        sample  15327   2.079 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.492           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.878           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.015           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.552           ms/op
ClientSimple.getUser:getUser·p0.999         sample         30.507           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         31.206           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.293           ms/op
ClientSimple.listUser                       sample   8803   3.642 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.939           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.355           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.923           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.594           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.594           ms/op

Benchmark result is saved to 1718949943542.json
