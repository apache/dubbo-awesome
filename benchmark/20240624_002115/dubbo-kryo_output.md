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
# Warmup Iteration   1: 1.388 ops/ms
Iteration   1: 6.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.558 ops/ms


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
# Warmup Iteration   1: 5.904 ops/ms
Iteration   1: 12.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.249 ops/ms


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
# Warmup Iteration   1: 4.853 ops/ms
Iteration   1: 12.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.528 ops/ms


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
# Warmup Iteration   1: 5.347 ops/ms
Iteration   1: 8.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.664 ops/ms


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
# Warmup Iteration   1: 3.667 ±(99.9%) 0.059 ms/op
Iteration   1: 1.910 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.910 ms/op


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
# Warmup Iteration   1: 3.222 ±(99.9%) 0.054 ms/op
Iteration   1: 1.866 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.866 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.054 ms/op
Iteration   1: 2.113 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.113 ms/op


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.100 ms/op
Iteration   1: 3.665 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.665 ms/op


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.089 ms/op
Iteration   1: 2.176 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   2.056 ms/op
                 createUser·p0.90:   2.580 ms/op
                 createUser·p0.95:   2.896 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  18.547 ms/op
                 createUser·p0.9999: 19.155 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14693
  mean =      2.176 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 12640 
    [ 2.500,  3.750) = 1696 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     19.155 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 2.911 ±(99.9%) 0.067 ms/op
Iteration   1: 2.050 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  19.117 ms/op
                 existUser·p0.9999: 19.610 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15594
  mean =      2.050 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 382 
    [ 1.250,  2.500) = 13566 
    [ 2.500,  3.750) = 1453 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =     19.117 ms/op
     p(99.9900) =     19.610 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 3.269 ±(99.9%) 0.088 ms/op
Iteration   1: 2.147 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   2.025 ms/op
                 getUser·p0.90:   2.574 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  23.724 ms/op
                 getUser·p0.9999: 25.412 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14916
  mean =      2.147 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13016 
    [ 2.500,  5.000) = 1723 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.574 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     23.724 ms/op
     p(99.9900) =     25.412 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.124 ms/op
Iteration   1: 3.795 ±(99.9%) 0.064 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   8.968 ms/op
                 listUser·p0.999:  27.988 ms/op
                 listUser·p0.9999: 28.967 ms/op
                 listUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8432
  mean =      3.795 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 790 
    [ 2.500,  5.000) = 7259 
    [ 5.000,  7.500) = 223 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      8.968 ms/op
     p(99.9000) =     27.988 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.558          ops/ms
ClientSimple.existUser                       thrpt         12.249          ops/ms
ClientSimple.getUser                         thrpt         12.528          ops/ms
ClientSimple.listUser                        thrpt          8.664          ops/ms
ClientSimple.createUser                       avgt          1.910           ms/op
ClientSimple.existUser                        avgt          1.866           ms/op
ClientSimple.getUser                          avgt          2.113           ms/op
ClientSimple.listUser                         avgt          3.665           ms/op
ClientSimple.createUser                     sample  14693   2.176 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.775           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.056           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.580           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.603           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.547           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.155           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.431           ms/op
ClientSimple.existUser                      sample  15594   2.050 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.623           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.923           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.112           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.117           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.610           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.628           ms/op
ClientSimple.getUser                        sample  14916   2.147 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.599           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.025           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.574           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.186           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.724           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.412           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.428           ms/op
ClientSimple.listUser                       sample   8432   3.795 ± 0.064   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.208           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.777           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.968           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.988           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.967           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.967           ms/op

Benchmark result is saved to 1719188241226.json
