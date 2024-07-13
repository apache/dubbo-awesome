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
# Warmup Iteration   1: 1.762 ops/ms
Iteration   1: 6.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.935 ops/ms


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
# Warmup Iteration   1: 6.295 ops/ms
Iteration   1: 12.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.186 ops/ms


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
# Warmup Iteration   1: 5.895 ops/ms
Iteration   1: 13.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.690 ops/ms


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
# Warmup Iteration   1: 5.151 ops/ms
Iteration   1: 8.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.696 ops/ms


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.060 ms/op
Iteration   1: 2.076 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.076 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.827 ±(99.9%) 0.051 ms/op
Iteration   1: 1.693 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.693 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.332 ±(99.9%) 0.059 ms/op
Iteration   1: 1.901 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.901 ms/op


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
# Warmup Iteration   1: 5.075 ±(99.9%) 0.091 ms/op
Iteration   1: 3.581 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.581 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.096 ms/op
Iteration   1: 2.381 ±(99.9%) 0.169 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   1.935 ms/op
                 createUser·p0.90:   2.429 ms/op
                 createUser·p0.95:   2.793 ms/op
                 createUser·p0.99:   9.187 ms/op
                 createUser·p0.999:  121.111 ms/op
                 createUser·p0.9999: 122.552 ms/op
                 createUser·p1.00:   122.552 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13423
  mean =      2.381 ±(99.9%) 0.169 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 13327 
    [ 12.500,  25.000) = 64 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 32 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      9.187 ms/op
     p(99.9000) =    121.111 ms/op
     p(99.9900) =    122.552 ms/op
     p(99.9990) =    122.552 ms/op
     p(99.9999) =    122.552 ms/op
    p(100.0000) =    122.552 ms/op


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
# Warmup Iteration   1: 2.793 ±(99.9%) 0.060 ms/op
Iteration   1: 1.656 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   1.520 ms/op
                 existUser·p0.90:   1.989 ms/op
                 existUser·p0.95:   2.150 ms/op
                 existUser·p0.99:   3.157 ms/op
                 existUser·p0.999:  22.753 ms/op
                 existUser·p0.9999: 23.497 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19311
  mean =      1.656 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18963 
    [ 2.500,  5.000) = 235 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      1.520 ms/op
     p(90.0000) =      1.989 ms/op
     p(95.0000) =      2.150 ms/op
     p(99.0000) =      3.157 ms/op
     p(99.9000) =     22.753 ms/op
     p(99.9900) =     23.497 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 3.581 ±(99.9%) 0.085 ms/op
Iteration   1: 1.872 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   1.751 ms/op
                 getUser·p0.90:   2.376 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   3.158 ms/op
                 getUser·p0.999:  11.223 ms/op
                 getUser·p0.9999: 11.363 ms/op
                 getUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17208
  mean =      1.872 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 15899 
    [ 2.500,  3.750) = 1024 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.158 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     11.363 ms/op
     p(99.9990) =     11.387 ms/op
     p(99.9999) =     11.387 ms/op
    p(100.0000) =     11.387 ms/op


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.129 ms/op
Iteration   1: 3.301 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.174 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.308 ms/op
                 listUser·p0.99:   6.091 ms/op
                 listUser·p0.999:  13.652 ms/op
                 listUser·p0.9999: 14.418 ms/op
                 listUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9722
  mean =      3.301 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 528 
    [ 2.500,  3.750) = 7016 
    [ 3.750,  5.000) = 1966 
    [ 5.000,  6.250) = 126 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.308 ms/op
     p(99.0000) =      6.091 ms/op
     p(99.9000) =     13.652 ms/op
     p(99.9900) =     14.418 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.935          ops/ms
ClientSimple.existUser                       thrpt          12.186          ops/ms
ClientSimple.getUser                         thrpt          13.690          ops/ms
ClientSimple.listUser                        thrpt           8.696          ops/ms
ClientSimple.createUser                       avgt           2.076           ms/op
ClientSimple.existUser                        avgt           1.693           ms/op
ClientSimple.getUser                          avgt           1.901           ms/op
ClientSimple.listUser                         avgt           3.581           ms/op
ClientSimple.createUser                     sample  13423    2.381 ± 0.169   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.634           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.935           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.429           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.793           ms/op
ClientSimple.createUser:createUser·p0.99    sample           9.187           ms/op
ClientSimple.createUser:createUser·p0.999   sample         121.111           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         122.552           ms/op
ClientSimple.createUser:createUser·p1.00    sample         122.552           ms/op
ClientSimple.existUser                      sample  19311    1.656 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.562           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.520           ms/op
ClientSimple.existUser:existUser·p0.90      sample           1.989           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.150           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.157           ms/op
ClientSimple.existUser:existUser·p0.999     sample          22.753           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          23.497           ms/op
ClientSimple.existUser:existUser·p1.00      sample          23.527           ms/op
ClientSimple.getUser                        sample  17208    1.872 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.545           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.751           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.376           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.158           ms/op
ClientSimple.getUser:getUser·p0.999         sample          11.223           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          11.363           ms/op
ClientSimple.getUser:getUser·p1.00          sample          11.387           ms/op
ClientSimple.listUser                       sample   9722    3.301 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.952           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.174           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.308           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.091           ms/op
ClientSimple.listUser:listUser·p0.999       sample          13.652           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          14.418           ms/op
ClientSimple.listUser:listUser·p1.00        sample          14.418           ms/op

Benchmark result is saved to 1720850707567.json
