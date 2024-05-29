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
# Warmup Iteration   1: 1.898 ops/ms
Iteration   1: 6.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.747 ops/ms


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
# Warmup Iteration   1: 6.013 ops/ms
Iteration   1: 13.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.257 ops/ms


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
# Warmup Iteration   1: 6.754 ops/ms
Iteration   1: 13.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.418 ops/ms


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
# Warmup Iteration   1: 5.084 ops/ms
Iteration   1: 8.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.855 ops/ms


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.054 ms/op
Iteration   1: 1.967 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.967 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.046 ms/op
Iteration   1: 1.894 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.894 ms/op


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
# Warmup Iteration   1: 3.093 ±(99.9%) 0.053 ms/op
Iteration   1: 2.002 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.002 ms/op


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
# Warmup Iteration   1: 4.482 ±(99.9%) 0.108 ms/op
Iteration   1: 3.252 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.252 ms/op


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.120 ms/op
Iteration   1: 1.985 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   1.812 ms/op
                 createUser·p0.90:   2.392 ms/op
                 createUser·p0.95:   2.675 ms/op
                 createUser·p0.99:   5.783 ms/op
                 createUser·p0.999:  15.303 ms/op
                 createUser·p0.9999: 15.859 ms/op
                 createUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16104
  mean =      1.985 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 14653 
    [ 2.500,  3.750) = 925 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      5.783 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     15.859 ms/op
     p(99.9990) =     16.269 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 3.157 ±(99.9%) 0.076 ms/op
Iteration   1: 1.941 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   1.903 ms/op
                 existUser·p0.90:   2.646 ms/op
                 existUser·p0.95:   2.843 ms/op
                 existUser·p0.99:   3.421 ms/op
                 existUser·p0.999:  13.296 ms/op
                 existUser·p0.9999: 13.780 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16472
  mean =      1.941 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1936 
    [ 1.250,  2.500) = 12277 
    [ 2.500,  3.750) = 2185 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      3.421 ms/op
     p(99.9000) =     13.296 ms/op
     p(99.9900) =     13.780 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 3.379 ±(99.9%) 0.084 ms/op
Iteration   1: 1.909 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   1.817 ms/op
                 getUser·p0.90:   2.126 ms/op
                 getUser·p0.95:   2.376 ms/op
                 getUser·p0.99:   3.459 ms/op
                 getUser·p0.999:  17.572 ms/op
                 getUser·p0.9999: 19.658 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16747
  mean =      1.909 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 16081 
    [ 2.500,  3.750) = 444 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.459 ms/op
     p(99.9000) =     17.572 ms/op
     p(99.9900) =     19.658 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.125 ms/op
Iteration   1: 3.480 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.224 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   7.956 ms/op
                 listUser·p0.999:  12.157 ms/op
                 listUser·p0.9999: 13.074 ms/op
                 listUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9183
  mean =      3.480 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1530 
    [ 2.500,  3.750) = 4130 
    [ 3.750,  5.000) = 2809 
    [ 5.000,  6.250) = 546 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.956 ms/op
     p(99.9000) =     12.157 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     13.074 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.747          ops/ms
ClientSimple.existUser                       thrpt         13.257          ops/ms
ClientSimple.getUser                         thrpt         13.418          ops/ms
ClientSimple.listUser                        thrpt          8.855          ops/ms
ClientSimple.createUser                       avgt          1.967           ms/op
ClientSimple.existUser                        avgt          1.894           ms/op
ClientSimple.getUser                          avgt          2.002           ms/op
ClientSimple.listUser                         avgt          3.252           ms/op
ClientSimple.createUser                     sample  16104   1.985 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.755           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.812           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.392           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.675           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.783           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.303           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.859           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.269           ms/op
ClientSimple.existUser                      sample  16472   1.941 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.547           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.903           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.843           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.421           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.296           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.780           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.812           ms/op
ClientSimple.getUser                        sample  16747   1.909 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.730           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.817           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.126           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.459           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.572           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.658           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.857           ms/op
ClientSimple.listUser                       sample   9183   3.480 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.978           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.224           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.956           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.157           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.074           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.074           ms/op

Benchmark result is saved to 1716941777649.json
