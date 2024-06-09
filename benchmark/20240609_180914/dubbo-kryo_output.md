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
# Warmup Iteration   1: 2.009 ops/ms
Iteration   1: 6.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.714 ops/ms


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
# Warmup Iteration   1: 6.659 ops/ms
Iteration   1: 13.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.611 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.632 ops/ms
Iteration   1: 14.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.760 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.915 ops/ms
Iteration   1: 7.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.986 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.068 ms/op
Iteration   1: 2.010 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.010 ms/op


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
# Warmup Iteration   1: 3.433 ±(99.9%) 0.095 ms/op
Iteration   1: 1.766 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.766 ms/op


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.059 ms/op
Iteration   1: 1.986 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.986 ms/op


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.109 ms/op
Iteration   1: 3.187 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.187 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.088 ms/op
Iteration   1: 1.993 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   1.815 ms/op
                 createUser·p0.90:   2.553 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   7.744 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 20.085 ms/op
                 createUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16036
  mean =      1.993 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14198 
    [ 2.500,  5.000) = 1637 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.553 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      7.744 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     20.085 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.165 ±(99.9%) 0.085 ms/op
Iteration   1: 1.929 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.404 ms/op
                 existUser·p0.50:   1.874 ms/op
                 existUser·p0.90:   2.568 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  12.510 ms/op
                 existUser·p0.9999: 13.414 ms/op
                 existUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16608
  mean =      1.929 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1579 
    [ 1.250,  2.500) = 13159 
    [ 2.500,  3.750) = 1673 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =     12.510 ms/op
     p(99.9900) =     13.414 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


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
# Warmup Iteration   1: 3.014 ±(99.9%) 0.072 ms/op
Iteration   1: 1.954 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   1.786 ms/op
                 getUser·p0.90:   2.343 ms/op
                 getUser·p0.95:   2.511 ms/op
                 getUser·p0.99:   5.539 ms/op
                 getUser·p0.999:  27.578 ms/op
                 getUser·p0.9999: 28.186 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16389
  mean =      1.954 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15528 
    [ 2.500,  5.000) = 679 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      5.539 ms/op
     p(99.9000) =     27.578 ms/op
     p(99.9900) =     28.186 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.123 ms/op
Iteration   1: 3.379 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.449 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.349 ms/op
                 listUser·p0.999:  5.755 ms/op
                 listUser·p0.9999: 7.209 ms/op
                 listUser·p1.00:   7.209 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9479
  mean =      3.379 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 12 
    [1.500, 2.000) = 80 
    [2.000, 2.500) = 1455 
    [2.500, 3.000) = 1734 
    [3.000, 3.500) = 1672 
    [3.500, 4.000) = 2321 
    [4.000, 4.500) = 1745 
    [4.500, 5.000) = 308 
    [5.000, 5.500) = 101 
    [5.500, 6.000) = 48 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      5.755 ms/op
     p(99.9900) =      7.209 ms/op
     p(99.9990) =      7.209 ms/op
     p(99.9999) =      7.209 ms/op
    p(100.0000) =      7.209 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.714          ops/ms
ClientSimple.existUser                       thrpt         13.611          ops/ms
ClientSimple.getUser                         thrpt         14.760          ops/ms
ClientSimple.listUser                        thrpt          7.986          ops/ms
ClientSimple.createUser                       avgt          2.010           ms/op
ClientSimple.existUser                        avgt          1.766           ms/op
ClientSimple.getUser                          avgt          1.986           ms/op
ClientSimple.listUser                         avgt          3.187           ms/op
ClientSimple.createUser                     sample  16036   1.993 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.775           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.815           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.553           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.744           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.236           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.085           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.382           ms/op
ClientSimple.existUser                      sample  16608   1.929 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.404           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.874           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.284           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.510           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.414           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.468           ms/op
ClientSimple.getUser                        sample  16389   1.954 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.500           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.786           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.343           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.539           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.578           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.186           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.312           ms/op
ClientSimple.listUser                       sample   9479   3.379 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.053           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.449           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.349           ms/op
ClientSimple.listUser:listUser·p0.999       sample          5.755           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.209           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.209           ms/op

Benchmark result is saved to 1717956291385.json
