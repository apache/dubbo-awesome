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
# Warmup Iteration   1: 1.736 ops/ms
Iteration   1: 7.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.774 ops/ms


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
# Warmup Iteration   1: 6.223 ops/ms
Iteration   1: 13.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.018 ops/ms


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
# Warmup Iteration   1: 6.619 ops/ms
Iteration   1: 13.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.250 ops/ms


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
# Warmup Iteration   1: 3.980 ops/ms
Iteration   1: 8.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.306 ops/ms


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
# Warmup Iteration   1: 3.697 ±(99.9%) 0.073 ms/op
Iteration   1: 2.104 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.104 ms/op


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
# Warmup Iteration   1: 3.149 ±(99.9%) 0.058 ms/op
Iteration   1: 1.968 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.968 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.048 ms/op
Iteration   1: 1.976 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.976 ms/op


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.098 ms/op
Iteration   1: 2.969 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.969 ms/op


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.100 ms/op
Iteration   1: 1.969 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   1.831 ms/op
                 createUser·p0.90:   2.478 ms/op
                 createUser·p0.95:   2.658 ms/op
                 createUser·p0.99:   5.191 ms/op
                 createUser·p0.999:  13.812 ms/op
                 createUser·p0.9999: 14.510 ms/op
                 createUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16232
  mean =      1.969 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 239 
    [ 1.250,  2.500) = 14502 
    [ 2.500,  3.750) = 1204 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      5.191 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     14.510 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 2.962 ±(99.9%) 0.067 ms/op
Iteration   1: 1.886 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.305 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   3.090 ms/op
                 existUser·p0.999:  25.593 ms/op
                 existUser·p0.9999: 26.018 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16950
  mean =      1.886 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16354 
    [ 2.500,  5.000) = 525 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.305 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      3.090 ms/op
     p(99.9000) =     25.593 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.075 ms/op
Iteration   1: 1.962 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   1.935 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   3.117 ms/op
                 getUser·p0.999:  12.298 ms/op
                 getUser·p0.9999: 12.415 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16361
  mean =      1.962 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 379 
    [ 1.250,  2.500) = 14732 
    [ 2.500,  3.750) = 1140 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.117 ms/op
     p(99.9000) =     12.298 ms/op
     p(99.9900) =     12.415 ms/op
     p(99.9990) =     12.435 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


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
# Warmup Iteration   1: 5.245 ±(99.9%) 0.145 ms/op
Iteration   1: 3.755 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  16.351 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8496
  mean =      3.755 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 752 
    [ 2.500,  3.750) = 3877 
    [ 3.750,  5.000) = 3449 
    [ 5.000,  6.250) = 320 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.774          ops/ms
ClientSimple.existUser                       thrpt         13.018          ops/ms
ClientSimple.getUser                         thrpt         13.250          ops/ms
ClientSimple.listUser                        thrpt          8.306          ops/ms
ClientSimple.createUser                       avgt          2.104           ms/op
ClientSimple.existUser                        avgt          1.968           ms/op
ClientSimple.getUser                          avgt          1.976           ms/op
ClientSimple.listUser                         avgt          2.969           ms/op
ClientSimple.createUser                     sample  16232   1.969 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.769           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.831           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.478           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.191           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.812           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.510           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.664           ms/op
ClientSimple.existUser                      sample  16950   1.886 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.305           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.798           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.090           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.593           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.018           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.018           ms/op
ClientSimple.getUser                        sample  16361   1.962 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.753           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.935           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.117           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.298           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.415           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.435           ms/op
ClientSimple.listUser                       sample   8496   3.755 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.165           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.666           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.390           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.351           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.891           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.891           ms/op

Benchmark result is saved to 1715688391945.json
