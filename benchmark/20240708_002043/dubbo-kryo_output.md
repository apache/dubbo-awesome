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
# Warmup Iteration   1: 2.003 ops/ms
Iteration   1: 7.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.389 ops/ms


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
# Warmup Iteration   1: 6.494 ops/ms
Iteration   1: 12.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.509 ops/ms


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
# Warmup Iteration   1: 7.119 ops/ms
Iteration   1: 15.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.869 ops/ms


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
# Warmup Iteration   1: 5.441 ops/ms
Iteration   1: 8.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.997 ops/ms


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.068 ms/op
Iteration   1: 2.261 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.261 ms/op


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
# Warmup Iteration   1: 3.071 ±(99.9%) 0.051 ms/op
Iteration   1: 1.882 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.882 ms/op


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
# Warmup Iteration   1: 2.968 ±(99.9%) 0.056 ms/op
Iteration   1: 2.043 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.043 ms/op


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.102 ms/op
Iteration   1: 3.460 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.460 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.082 ms/op
Iteration   1: 2.425 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.847 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   9.830 ms/op
                 createUser·p0.999:  28.561 ms/op
                 createUser·p0.9999: 30.879 ms/op
                 createUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13188
  mean =      2.425 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9614 
    [ 2.500,  5.000) = 3316 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     28.561 ms/op
     p(99.9900) =     30.879 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.074 ms/op
Iteration   1: 1.549 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   1.503 ms/op
                 existUser·p0.90:   1.708 ms/op
                 existUser·p0.95:   1.835 ms/op
                 existUser·p0.99:   2.320 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 10.911 ms/op
                 existUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 20648
  mean =      1.549 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 405 
    [ 1.250,  2.500) = 20103 
    [ 2.500,  3.750) = 72 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      1.503 ms/op
     p(90.0000) =      1.708 ms/op
     p(95.0000) =      1.835 ms/op
     p(99.0000) =      2.320 ms/op
     p(99.9000) =     10.502 ms/op
     p(99.9900) =     10.911 ms/op
     p(99.9990) =     10.945 ms/op
     p(99.9999) =     10.945 ms/op
    p(100.0000) =     10.945 ms/op


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
# Warmup Iteration   1: 3.543 ±(99.9%) 0.087 ms/op
Iteration   1: 2.014 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   1.905 ms/op
                 getUser·p0.90:   2.454 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  23.167 ms/op
                 getUser·p0.9999: 24.462 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16393
  mean =      2.014 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14979 
    [ 2.500,  5.000) = 1310 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =     23.167 ms/op
     p(99.9900) =     24.462 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.273 ms/op
Iteration   1: 3.408 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.393 ms/op
                 listUser·p0.999:  16.113 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9390
  mean =      3.408 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 771 
    [ 2.500,  3.750) = 6358 
    [ 3.750,  5.000) = 2089 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.393 ms/op
     p(99.9000) =     16.113 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.389          ops/ms
ClientSimple.existUser                       thrpt         12.509          ops/ms
ClientSimple.getUser                         thrpt         15.869          ops/ms
ClientSimple.listUser                        thrpt          8.997          ops/ms
ClientSimple.createUser                       avgt          2.261           ms/op
ClientSimple.existUser                        avgt          1.882           ms/op
ClientSimple.getUser                          avgt          2.043           ms/op
ClientSimple.listUser                         avgt          3.460           ms/op
ClientSimple.createUser                     sample  13188   2.425 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.457           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.215           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.830           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.561           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.879           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.900           ms/op
ClientSimple.existUser                      sample  20648   1.549 ± 0.010   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.739           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.503           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.708           ms/op
ClientSimple.existUser:existUser·p0.95      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.320           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.502           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.911           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.945           ms/op
ClientSimple.getUser                        sample  16393   2.014 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.750           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.905           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.454           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.043           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.167           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.462           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.609           ms/op
ClientSimple.listUser                       sample   9390   3.408 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.124           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.051           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.393           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.113           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.777           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.777           ms/op

Benchmark result is saved to 1720397832205.json
