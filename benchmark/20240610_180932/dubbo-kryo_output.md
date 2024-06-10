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
# Warmup Iteration   1: 2.313 ops/ms
Iteration   1: 6.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.286 ops/ms


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
# Warmup Iteration   1: 6.197 ops/ms
Iteration   1: 13.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.425 ops/ms


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
# Warmup Iteration   1: 5.546 ops/ms
Iteration   1: 14.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.081 ops/ms


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
# Warmup Iteration   1: 6.147 ops/ms
Iteration   1: 8.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.376 ops/ms


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.096 ms/op
Iteration   1: 2.158 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.158 ms/op


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
# Warmup Iteration   1: 3.278 ±(99.9%) 0.058 ms/op
Iteration   1: 1.720 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.720 ms/op


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.085 ms/op
Iteration   1: 2.086 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.086 ms/op


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
# Warmup Iteration   1: 4.682 ±(99.9%) 0.099 ms/op
Iteration   1: 3.380 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.380 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.082 ms/op
Iteration   1: 2.144 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.040 ms/op
                 createUser·p0.90:   2.580 ms/op
                 createUser·p0.95:   2.753 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  18.782 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14904
  mean =      2.144 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12828 
    [ 2.500,  5.000) = 1941 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =     18.782 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.071 ms/op
Iteration   1: 1.870 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.445 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   2.990 ms/op
                 existUser·p0.999:  11.892 ms/op
                 existUser·p0.9999: 12.164 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17148
  mean =      1.870 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 405 
    [ 1.250,  2.500) = 15688 
    [ 2.500,  3.750) = 1006 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
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
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      2.990 ms/op
     p(99.9000) =     11.892 ms/op
     p(99.9900) =     12.164 ms/op
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
# Warmup Iteration   1: 3.660 ±(99.9%) 0.107 ms/op
Iteration   1: 2.056 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   1.849 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.785 ms/op
                 getUser·p0.99:   3.331 ms/op
                 getUser·p0.999:  22.872 ms/op
                 getUser·p0.9999: 22.952 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15568
  mean =      2.056 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13745 
    [ 2.500,  5.000) = 1748 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      3.331 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     22.952 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.115 ms/op
Iteration   1: 3.553 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  17.132 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9185
  mean =      3.553 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 651 
    [ 2.500,  3.750) = 5285 
    [ 3.750,  5.000) = 2838 
    [ 5.000,  6.250) = 222 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     17.132 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.286          ops/ms
ClientSimple.existUser                       thrpt         13.425          ops/ms
ClientSimple.getUser                         thrpt         14.081          ops/ms
ClientSimple.listUser                        thrpt          8.376          ops/ms
ClientSimple.createUser                       avgt          2.158           ms/op
ClientSimple.existUser                        avgt          1.720           ms/op
ClientSimple.getUser                          avgt          2.086           ms/op
ClientSimple.listUser                         avgt          3.380           ms/op
ClientSimple.createUser                     sample  14904   2.144 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.908           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.040           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.580           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.833           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.782           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.840           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.840           ms/op
ClientSimple.existUser                      sample  17148   1.870 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.445           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.747           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.990           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.892           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.164           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.304           ms/op
ClientSimple.getUser                        sample  15568   2.056 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.642           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.849           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.785           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.331           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.872           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.952           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.970           ms/op
ClientSimple.listUser                       sample   9185   3.553 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.905           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.559           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.234           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.132           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.907           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.907           ms/op

Benchmark result is saved to 1718042722800.json
