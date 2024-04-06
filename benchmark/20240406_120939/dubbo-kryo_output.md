# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.870 ops/ms
Iteration   1: 6.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.796 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.613 ops/ms
Iteration   1: 11.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.373 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.622 ops/ms
Iteration   1: 11.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.717 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.735 ops/ms
Iteration   1: 9.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.725 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ±(99.9%) 0.065 ms/op
Iteration   1: 2.280 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.280 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ±(99.9%) 0.091 ms/op
Iteration   1: 1.945 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.945 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.228 ±(99.9%) 0.053 ms/op
Iteration   1: 2.051 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.051 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.721 ±(99.9%) 0.141 ms/op
Iteration   1: 3.201 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.201 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ±(99.9%) 0.089 ms/op
Iteration   1: 2.355 ±(99.9%) 0.097 ms/op
                 createUser·p0.00:   0.388 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.437 ms/op
                 createUser·p0.95:   2.662 ms/op
                 createUser·p0.99:   17.105 ms/op
                 createUser·p0.999:  46.203 ms/op
                 createUser·p0.9999: 48.588 ms/op
                 createUser·p1.00:   49.086 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13805
  mean =      2.355 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13508 
    [ 5.000, 10.000) = 114 
    [10.000, 15.000) = 25 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 34 
    [40.000, 45.000) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =     17.105 ms/op
     p(99.9000) =     46.203 ms/op
     p(99.9900) =     48.588 ms/op
     p(99.9990) =     49.086 ms/op
     p(99.9999) =     49.086 ms/op
    p(100.0000) =     49.086 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.906 ±(99.9%) 0.062 ms/op
Iteration   1: 1.779 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.283 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   2.855 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 12.963 ms/op
                 existUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17995
  mean =      1.779 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 628 
    [ 1.250,  2.500) = 16841 
    [ 2.500,  3.750) = 431 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.283 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      2.855 ms/op
     p(99.9000) =     11.829 ms/op
     p(99.9900) =     12.963 ms/op
     p(99.9990) =     12.976 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.086 ±(99.9%) 0.090 ms/op
Iteration   1: 2.533 ±(99.9%) 0.167 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   1.933 ms/op
                 getUser·p0.90:   2.699 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   10.251 ms/op
                 getUser·p0.999:  90.148 ms/op
                 getUser·p0.9999: 121.333 ms/op
                 getUser·p1.00:   121.504 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12601
  mean =      2.533 ±(99.9%) 0.167 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 12510 
    [ 12.500,  25.000) = 6 
    [ 25.000,  37.500) = 3 
    [ 37.500,  50.000) = 6 
    [ 50.000,  62.500) = 35 
    [ 62.500,  75.000) = 20 
    [ 75.000,  87.500) = 8 
    [ 87.500, 100.000) = 3 
    [100.000, 112.500) = 4 
    [112.500, 125.000) = 6 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =     10.251 ms/op
     p(99.9000) =     90.148 ms/op
     p(99.9900) =    121.333 ms/op
     p(99.9990) =    121.504 ms/op
     p(99.9999) =    121.504 ms/op
    p(100.0000) =    121.504 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.126 ms/op
Iteration   1: 3.163 ±(99.9%) 0.059 ms/op
                 listUser·p0.00:   0.405 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   4.806 ms/op
                 listUser·p0.999:  33.485 ms/op
                 listUser·p0.9999: 34.078 ms/op
                 listUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10129
  mean =      3.163 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1009 
    [ 2.500,  5.000) = 9046 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.405 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      4.806 ms/op
     p(99.9000) =     33.485 ms/op
     p(99.9900) =     34.078 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.796          ops/ms
ClientSimple.existUser                       thrpt          11.373          ops/ms
ClientSimple.getUser                         thrpt          11.717          ops/ms
ClientSimple.listUser                        thrpt           9.725          ops/ms
ClientSimple.createUser                       avgt           2.280           ms/op
ClientSimple.existUser                        avgt           1.945           ms/op
ClientSimple.getUser                          avgt           2.051           ms/op
ClientSimple.listUser                         avgt           3.201           ms/op
ClientSimple.createUser                     sample  13805    2.355 ± 0.097   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.388           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.437           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.662           ms/op
ClientSimple.createUser:createUser·p0.99    sample          17.105           ms/op
ClientSimple.createUser:createUser·p0.999   sample          46.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          48.588           ms/op
ClientSimple.createUser:createUser·p1.00    sample          49.086           ms/op
ClientSimple.existUser                      sample  17995    1.779 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.283           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.681           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.437           ms/op
ClientSimple.existUser:existUser·p0.99      sample           2.855           ms/op
ClientSimple.existUser:existUser·p0.999     sample          11.829           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          12.963           ms/op
ClientSimple.existUser:existUser·p1.00      sample          12.976           ms/op
ClientSimple.getUser                        sample  12601    2.533 ± 0.167   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.933           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.699           ms/op
ClientSimple.getUser:getUser·p0.95          sample           3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          10.251           ms/op
ClientSimple.getUser:getUser·p0.999         sample          90.148           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         121.333           ms/op
ClientSimple.getUser:getUser·p1.00          sample         121.504           ms/op
ClientSimple.listUser                       sample  10129    3.163 ± 0.059   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.405           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.014           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample           4.806           ms/op
ClientSimple.listUser:listUser·p0.999       sample          33.485           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          34.078           ms/op
ClientSimple.listUser:listUser·p1.00        sample          34.079           ms/op

Benchmark result is saved to 1712405141686.json
