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
# Warmup Iteration   1: 2.050 ops/ms
Iteration   1: 6.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.951 ops/ms


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
# Warmup Iteration   1: 6.267 ops/ms
Iteration   1: 12.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.229 ops/ms


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
# Warmup Iteration   1: 5.640 ops/ms
Iteration   1: 12.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.865 ops/ms


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
# Warmup Iteration   1: 5.683 ops/ms
Iteration   1: 8.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.711 ops/ms


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.081 ms/op
Iteration   1: 2.020 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.020 ms/op


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
# Warmup Iteration   1: 3.077 ±(99.9%) 0.045 ms/op
Iteration   1: 1.763 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.763 ms/op


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
# Warmup Iteration   1: 3.464 ±(99.9%) 0.057 ms/op
Iteration   1: 2.009 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.009 ms/op


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.106 ms/op
Iteration   1: 3.555 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.555 ms/op


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.110 ms/op
Iteration   1: 2.167 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.497 ms/op
                 createUser·p0.50:   2.009 ms/op
                 createUser·p0.90:   2.453 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   8.906 ms/op
                 createUser·p0.999:  14.349 ms/op
                 createUser·p0.9999: 15.663 ms/op
                 createUser·p1.00:   15.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14841
  mean =      2.167 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 13444 
    [ 2.500,  3.750) = 999 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.453 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      8.906 ms/op
     p(99.9000) =     14.349 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     15.663 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 3.000 ±(99.9%) 0.076 ms/op
Iteration   1: 2.176 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.236 ms/op
                 existUser·p0.90:   2.638 ms/op
                 existUser·p0.95:   2.806 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  11.977 ms/op
                 existUser·p0.9999: 12.274 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14704
  mean =      2.176 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 306 
    [ 1.250,  2.500) = 11853 
    [ 2.500,  3.750) = 2375 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 3 
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
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.236 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     12.274 ms/op
     p(99.9990) =     12.304 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


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
# Warmup Iteration   1: 3.608 ±(99.9%) 0.092 ms/op
Iteration   1: 2.052 ±(99.9%) 0.062 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   1.774 ms/op
                 getUser·p0.90:   2.462 ms/op
                 getUser·p0.95:   2.666 ms/op
                 getUser·p0.99:   3.582 ms/op
                 getUser·p0.999:  53.346 ms/op
                 getUser·p0.9999: 55.479 ms/op
                 getUser·p1.00:   55.771 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15568
  mean =      2.052 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15474 
    [ 5.000, 10.000) = 21 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      3.582 ms/op
     p(99.9000) =     53.346 ms/op
     p(99.9900) =     55.479 ms/op
     p(99.9990) =     55.771 ms/op
     p(99.9999) =     55.771 ms/op
    p(100.0000) =     55.771 ms/op


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.128 ms/op
Iteration   1: 3.048 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   2.757 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.185 ms/op
                 listUser·p0.999:  8.078 ms/op
                 listUser·p0.9999: 9.224 ms/op
                 listUser·p1.00:   9.224 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10583
  mean =      3.048 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 0 
    [ 1.500,  2.000) = 41 
    [ 2.000,  2.500) = 2311 
    [ 2.500,  3.000) = 4813 
    [ 3.000,  3.500) = 1169 
    [ 3.500,  4.000) = 804 
    [ 4.000,  4.500) = 860 
    [ 4.500,  5.000) = 298 
    [ 5.000,  5.500) = 66 
    [ 5.500,  6.000) = 61 
    [ 6.000,  6.500) = 73 
    [ 6.500,  7.000) = 8 
    [ 7.000,  7.500) = 32 
    [ 7.500,  8.000) = 27 
    [ 8.000,  8.500) = 18 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      2.757 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =      8.078 ms/op
     p(99.9900) =      9.224 ms/op
     p(99.9990) =      9.224 ms/op
     p(99.9999) =      9.224 ms/op
    p(100.0000) =      9.224 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.951          ops/ms
ClientSimple.existUser                       thrpt         12.229          ops/ms
ClientSimple.getUser                         thrpt         12.865          ops/ms
ClientSimple.listUser                        thrpt          8.711          ops/ms
ClientSimple.createUser                       avgt          2.020           ms/op
ClientSimple.existUser                        avgt          1.763           ms/op
ClientSimple.getUser                          avgt          2.009           ms/op
ClientSimple.listUser                         avgt          3.555           ms/op
ClientSimple.createUser                     sample  14841   2.167 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.497           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.009           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.453           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.906           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.349           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.663           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.663           ms/op
ClientSimple.existUser                      sample  14704   2.176 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.549           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.806           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.875           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.977           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.274           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.304           ms/op
ClientSimple.getUser                        sample  15568   2.052 ± 0.062   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.691           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.774           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.462           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.582           ms/op
ClientSimple.getUser:getUser·p0.999         sample         53.346           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         55.479           ms/op
ClientSimple.getUser:getUser·p1.00          sample         55.771           ms/op
ClientSimple.listUser                       sample  10583   3.048 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.542           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.757           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.185           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.078           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.224           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.224           ms/op

Benchmark result is saved to 1716250540955.json
