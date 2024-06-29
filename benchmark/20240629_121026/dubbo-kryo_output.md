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
# Warmup Iteration   1: 1.725 ops/ms
Iteration   1: 7.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.260 ops/ms


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
# Warmup Iteration   1: 7.204 ops/ms
Iteration   1: 11.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.655 ops/ms


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
# Warmup Iteration   1: 7.049 ops/ms
Iteration   1: 14.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.327 ops/ms


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
# Warmup Iteration   1: 4.833 ops/ms
Iteration   1: 8.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.833 ops/ms


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.071 ms/op
Iteration   1: 2.326 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.326 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.052 ms/op
Iteration   1: 1.782 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.782 ms/op


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
# Warmup Iteration   1: 3.203 ±(99.9%) 0.053 ms/op
Iteration   1: 2.150 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.150 ms/op


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.110 ms/op
Iteration   1: 3.449 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.449 ms/op


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.101 ms/op
Iteration   1: 2.193 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   1.974 ms/op
                 createUser·p0.90:   2.732 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   7.589 ms/op
                 createUser·p0.999:  15.237 ms/op
                 createUser·p0.9999: 15.434 ms/op
                 createUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14754
  mean =      2.193 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 12019 
    [ 2.500,  3.750) = 2325 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      7.589 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     15.434 ms/op
     p(99.9990) =     15.434 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 2.835 ±(99.9%) 0.064 ms/op
Iteration   1: 1.798 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   1.712 ms/op
                 existUser·p0.90:   2.028 ms/op
                 existUser·p0.95:   2.236 ms/op
                 existUser·p0.99:   3.861 ms/op
                 existUser·p0.999:  26.542 ms/op
                 existUser·p0.9999: 27.238 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17773
  mean =      1.798 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17273 
    [ 2.500,  5.000) = 390 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.028 ms/op
     p(95.0000) =      2.236 ms/op
     p(99.0000) =      3.861 ms/op
     p(99.9000) =     26.542 ms/op
     p(99.9900) =     27.238 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.092 ms/op
Iteration   1: 1.868 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   1.780 ms/op
                 getUser·p0.90:   2.118 ms/op
                 getUser·p0.95:   2.318 ms/op
                 getUser·p0.99:   3.072 ms/op
                 getUser·p0.999:  10.371 ms/op
                 getUser·p0.9999: 10.666 ms/op
                 getUser·p1.00:   10.666 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17188
  mean =      1.868 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 14480 
    [ 2.000,  3.000) = 2500 
    [ 3.000,  4.000) = 92 
    [ 4.000,  5.000) = 34 
    [ 5.000,  6.000) = 7 
    [ 6.000,  7.000) = 3 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 33 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.318 ms/op
     p(99.0000) =      3.072 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     10.666 ms/op
     p(99.9990) =     10.666 ms/op
     p(99.9999) =     10.666 ms/op
    p(100.0000) =     10.666 ms/op


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
# Warmup Iteration   1: 4.710 ±(99.9%) 0.142 ms/op
Iteration   1: 3.405 ±(99.9%) 0.096 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   3.097 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  47.946 ms/op
                 listUser·p0.9999: 51.577 ms/op
                 listUser·p1.00:   51.577 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9394
  mean =      3.405 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9188 
    [ 5.000, 10.000) = 132 
    [10.000, 15.000) = 4 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 36 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 18 
    [50.000, 55.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     47.946 ms/op
     p(99.9900) =     51.577 ms/op
     p(99.9990) =     51.577 ms/op
     p(99.9999) =     51.577 ms/op
    p(100.0000) =     51.577 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.260          ops/ms
ClientSimple.existUser                       thrpt         11.655          ops/ms
ClientSimple.getUser                         thrpt         14.327          ops/ms
ClientSimple.listUser                        thrpt          8.833          ops/ms
ClientSimple.createUser                       avgt          2.326           ms/op
ClientSimple.existUser                        avgt          1.782           ms/op
ClientSimple.getUser                          avgt          2.150           ms/op
ClientSimple.listUser                         avgt          3.449           ms/op
ClientSimple.createUser                     sample  14754   2.193 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.757           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.974           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.589           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.237           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.434           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.434           ms/op
ClientSimple.existUser                      sample  17773   1.798 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.539           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.712           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.028           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.861           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.542           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.238           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.263           ms/op
ClientSimple.getUser                        sample  17188   1.868 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.871           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.780           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.318           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.072           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.371           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.666           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.666           ms/op
ClientSimple.listUser                       sample   9394   3.405 ± 0.096   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.870           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.097           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.010           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.561           ms/op
ClientSimple.listUser:listUser·p0.999       sample         47.946           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         51.577           ms/op
ClientSimple.listUser:listUser·p1.00        sample         51.577           ms/op

Benchmark result is saved to 1719662772600.json
