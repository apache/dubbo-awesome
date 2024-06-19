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
# Warmup Iteration   1: 1.599 ops/ms
Iteration   1: 6.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.824 ops/ms


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
# Warmup Iteration   1: 6.723 ops/ms
Iteration   1: 12.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.812 ops/ms


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
# Warmup Iteration   1: 5.729 ops/ms
Iteration   1: 11.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.274 ops/ms


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
# Warmup Iteration   1: 6.161 ops/ms
Iteration   1: 8.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.863 ops/ms


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.083 ms/op
Iteration   1: 2.281 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.281 ms/op


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
# Warmup Iteration   1: 3.154 ±(99.9%) 0.060 ms/op
Iteration   1: 1.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.993 ms/op


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
# Warmup Iteration   1: 3.555 ±(99.9%) 0.071 ms/op
Iteration   1: 2.053 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.053 ms/op


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
# Warmup Iteration   1: 4.942 ±(99.9%) 0.116 ms/op
Iteration   1: 3.972 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.972 ms/op


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
# Warmup Iteration   1: 3.454 ±(99.9%) 0.084 ms/op
Iteration   1: 2.025 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   1.864 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  16.087 ms/op
                 createUser·p0.9999: 17.067 ms/op
                 createUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15778
  mean =      2.025 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 582 
    [ 1.250,  2.500) = 12710 
    [ 2.500,  3.750) = 2168 
    [ 3.750,  5.000) = 166 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =     16.087 ms/op
     p(99.9900) =     17.067 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 3.141 ±(99.9%) 0.079 ms/op
Iteration   1: 1.938 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.379 ms/op
                 existUser·p0.999:  16.769 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16501
  mean =      1.938 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 635 
    [ 1.250,  2.500) = 14571 
    [ 2.500,  3.750) = 1149 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.379 ms/op
     p(99.9000) =     16.769 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.313 ±(99.9%) 0.083 ms/op
Iteration   1: 1.872 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   1.726 ms/op
                 getUser·p0.90:   2.339 ms/op
                 getUser·p0.95:   2.540 ms/op
                 getUser·p0.99:   2.994 ms/op
                 getUser·p0.999:  15.430 ms/op
                 getUser·p0.9999: 15.743 ms/op
                 getUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17211
  mean =      1.872 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 188 
    [ 1.250,  2.500) = 16027 
    [ 2.500,  3.750) = 893 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      2.994 ms/op
     p(99.9000) =     15.430 ms/op
     p(99.9900) =     15.743 ms/op
     p(99.9990) =     15.991 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.139 ms/op
Iteration   1: 3.604 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.869 ms/op
                 listUser·p0.999:  7.419 ms/op
                 listUser·p0.9999: 7.594 ms/op
                 listUser·p1.00:   7.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8875
  mean =      3.604 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 2 
    [1.500, 2.000) = 102 
    [2.000, 2.500) = 633 
    [2.500, 3.000) = 811 
    [3.000, 3.500) = 1569 
    [3.500, 4.000) = 3635 
    [4.000, 4.500) = 1722 
    [4.500, 5.000) = 206 
    [5.000, 5.500) = 54 
    [5.500, 6.000) = 65 
    [6.000, 6.500) = 41 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.869 ms/op
     p(99.9000) =      7.419 ms/op
     p(99.9900) =      7.594 ms/op
     p(99.9990) =      7.594 ms/op
     p(99.9999) =      7.594 ms/op
    p(100.0000) =      7.594 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.824          ops/ms
ClientSimple.existUser                       thrpt         12.812          ops/ms
ClientSimple.getUser                         thrpt         11.274          ops/ms
ClientSimple.listUser                        thrpt          8.863          ops/ms
ClientSimple.createUser                       avgt          2.281           ms/op
ClientSimple.existUser                        avgt          1.993           ms/op
ClientSimple.getUser                          avgt          2.053           ms/op
ClientSimple.listUser                         avgt          3.972           ms/op
ClientSimple.createUser                     sample  15778   2.025 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.593           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.864           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.710           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.087           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.067           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.105           ms/op
ClientSimple.existUser                      sample  16501   1.938 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.536           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.379           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.769           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.974           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.974           ms/op
ClientSimple.getUser                        sample  17211   1.872 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.564           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.726           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.430           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.743           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.991           ms/op
ClientSimple.listUser                       sample   8875   3.604 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.276           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.686           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.869           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.419           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.594           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.594           ms/op

Benchmark result is saved to 1718798824493.json
