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
# Warmup Iteration   1: 1.688 ops/ms
Iteration   1: 6.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.143 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.511 ops/ms
Iteration   1: 12.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.339 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.548 ops/ms
Iteration   1: 11.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.560 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.197 ops/ms
Iteration   1: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.216 ops/ms


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
# Warmup Iteration   1: 4.308 ±(99.9%) 0.102 ms/op
Iteration   1: 2.212 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.212 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.064 ms/op
Iteration   1: 1.880 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.880 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.065 ms/op
Iteration   1: 2.276 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.276 ms/op


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
# Warmup Iteration   1: 5.138 ±(99.9%) 0.118 ms/op
Iteration   1: 3.443 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.443 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.094 ms/op
Iteration   1: 2.242 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   2.019 ms/op
                 createUser·p0.90:   2.699 ms/op
                 createUser·p0.95:   2.929 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  27.591 ms/op
                 createUser·p0.9999: 28.499 ms/op
                 createUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14293
  mean =      2.242 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11809 
    [ 2.500,  5.000) = 2259 
    [ 5.000,  7.500) = 129 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     27.591 ms/op
     p(99.9900) =     28.499 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 2.955 ±(99.9%) 0.072 ms/op
Iteration   1: 1.913 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.420 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.983 ms/op
                 existUser·p0.999:  14.645 ms/op
                 existUser·p0.9999: 14.750 ms/op
                 existUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17169
  mean =      1.913 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 201 
    [ 1.250,  2.500) = 15627 
    [ 2.500,  3.750) = 1165 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.983 ms/op
     p(99.9000) =     14.645 ms/op
     p(99.9900) =     14.750 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.415 ±(99.9%) 0.101 ms/op
Iteration   1: 2.071 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   1.923 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   3.002 ms/op
                 getUser·p0.99:   3.638 ms/op
                 getUser·p0.999:  10.969 ms/op
                 getUser·p0.9999: 11.017 ms/op
                 getUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15480
  mean =      2.071 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 12891 
    [ 2.500,  3.750) = 2304 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.638 ms/op
     p(99.9000) =     10.969 ms/op
     p(99.9900) =     11.017 ms/op
     p(99.9990) =     11.026 ms/op
     p(99.9999) =     11.026 ms/op
    p(100.0000) =     11.026 ms/op


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.127 ms/op
Iteration   1: 3.612 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.018 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8849
  mean =      3.612 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 441 
    [ 2.500,  3.750) = 4956 
    [ 3.750,  5.000) = 3007 
    [ 5.000,  6.250) = 298 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.018 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.143          ops/ms
ClientSimple.existUser                       thrpt         12.339          ops/ms
ClientSimple.getUser                         thrpt         11.560          ops/ms
ClientSimple.listUser                        thrpt          8.216          ops/ms
ClientSimple.createUser                       avgt          2.212           ms/op
ClientSimple.existUser                        avgt          1.880           ms/op
ClientSimple.getUser                          avgt          2.276           ms/op
ClientSimple.listUser                         avgt          3.443           ms/op
ClientSimple.createUser                     sample  14293   2.242 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.675           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.019           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.439           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.591           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.499           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.639           ms/op
ClientSimple.existUser                      sample  17169   1.913 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.420           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.729           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.983           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.645           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.750           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.762           ms/op
ClientSimple.getUser                        sample  15480   2.071 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.717           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.923           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.002           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.638           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.969           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.017           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.026           ms/op
ClientSimple.listUser                       sample   8849   3.612 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.339           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.018           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.021           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.628           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.923           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.923           ms/op

Benchmark result is saved to 1720202735087.json
