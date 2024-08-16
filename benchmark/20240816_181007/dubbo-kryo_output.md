# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.382 ops/ms
Iteration   1: 6.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.618 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.863 ops/ms
Iteration   1: 11.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.281 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.871 ops/ms
Iteration   1: 13.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.232 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.092 ops/ms
Iteration   1: 9.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.133 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.683 ±(99.9%) 0.069 ms/op
Iteration   1: 2.114 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.114 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.310 ±(99.9%) 0.092 ms/op
Iteration   1: 1.680 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.680 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.250 ±(99.9%) 0.057 ms/op
Iteration   1: 1.862 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.862 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.520 ±(99.9%) 0.117 ms/op
Iteration   1: 3.234 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.234 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.712 ±(99.9%) 0.127 ms/op
Iteration   1: 2.280 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.904 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   7.493 ms/op
                 createUser·p0.999:  15.073 ms/op
                 createUser·p0.9999: 15.830 ms/op
                 createUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14010
  mean =      2.280 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 212 
    [ 1.250,  2.500) = 10519 
    [ 2.500,  3.750) = 2753 
    [ 3.750,  5.000) = 170 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      7.493 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     15.830 ms/op
     p(99.9990) =     15.876 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.164 ±(99.9%) 0.076 ms/op
Iteration   1: 1.887 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.423 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  26.575 ms/op
                 existUser·p0.9999: 27.436 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17064
  mean =      1.887 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15609 
    [ 2.500,  5.000) = 1380 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.494 ms/op
     p(99.9000) =     26.575 ms/op
     p(99.9900) =     27.436 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.266 ±(99.9%) 0.081 ms/op
Iteration   1: 1.906 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   1.755 ms/op
                 getUser·p0.90:   2.337 ms/op
                 getUser·p0.95:   2.666 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  14.959 ms/op
                 getUser·p0.9999: 15.545 ms/op
                 getUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16854
  mean =      1.906 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 15510 
    [ 2.500,  3.750) = 1069 
    [ 3.750,  5.000) = 135 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      1.755 ms/op
     p(90.0000) =      2.337 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     15.545 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.441 ±(99.9%) 0.121 ms/op
Iteration   1: 3.515 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.713 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.349 ms/op
                 listUser·p0.999:  20.149 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9096
  mean =      3.515 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1385 
    [ 2.500,  5.000) = 7449 
    [ 5.000,  7.500) = 229 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     20.149 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.618          ops/ms
ClientSimple.existUser                       thrpt         11.281          ops/ms
ClientSimple.getUser                         thrpt         13.232          ops/ms
ClientSimple.listUser                        thrpt          9.133          ops/ms
ClientSimple.createUser                       avgt          2.114           ms/op
ClientSimple.existUser                        avgt          1.680           ms/op
ClientSimple.getUser                          avgt          1.862           ms/op
ClientSimple.listUser                         avgt          3.234           ms/op
ClientSimple.createUser                     sample  14010   2.280 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.542           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.244           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.493           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.073           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.830           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.876           ms/op
ClientSimple.existUser                      sample  17064   1.887 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.423           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.667           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.494           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.575           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.436           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.460           ms/op
ClientSimple.getUser                        sample  16854   1.906 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.773           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.755           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.337           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.801           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.959           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.545           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.679           ms/op
ClientSimple.listUser                       sample   9096   3.515 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.713           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.559           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.349           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.149           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.150           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.150           ms/op

Benchmark result is saved to 1723831561999.json
