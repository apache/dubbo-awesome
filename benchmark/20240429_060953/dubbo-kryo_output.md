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
# Warmup Iteration   1: 1.905 ops/ms
Iteration   1: 7.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.333 ops/ms


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
# Warmup Iteration   1: 7.567 ops/ms
Iteration   1: 13.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.326 ops/ms


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
# Warmup Iteration   1: 4.770 ops/ms
Iteration   1: 13.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.862 ops/ms


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
# Warmup Iteration   1: 5.079 ops/ms
Iteration   1: 8.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.908 ops/ms


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
# Warmup Iteration   1: 3.693 ±(99.9%) 0.066 ms/op
Iteration   1: 2.090 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.090 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.053 ms/op
Iteration   1: 1.947 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.947 ms/op


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
# Warmup Iteration   1: 3.143 ±(99.9%) 0.052 ms/op
Iteration   1: 1.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.951 ms/op


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.095 ms/op
Iteration   1: 3.694 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.694 ms/op


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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.118 ms/op
Iteration   1: 2.231 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.058 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.793 ms/op
                 createUser·p0.99:   5.459 ms/op
                 createUser·p0.999:  24.745 ms/op
                 createUser·p0.9999: 28.940 ms/op
                 createUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14459
  mean =      2.231 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12803 
    [ 2.500,  5.000) = 1499 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      5.459 ms/op
     p(99.9000) =     24.745 ms/op
     p(99.9900) =     28.940 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 2.914 ±(99.9%) 0.064 ms/op
Iteration   1: 1.972 ±(99.9%) 0.047 ms/op
                 existUser·p0.00:   0.239 ms/op
                 existUser·p0.50:   1.862 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  41.288 ms/op
                 existUser·p0.9999: 42.533 ms/op
                 existUser·p1.00:   42.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16201
  mean =      1.972 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16091 
    [ 5.000, 10.000) = 78 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.239 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =     41.288 ms/op
     p(99.9900) =     42.533 ms/op
     p(99.9990) =     42.533 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.108 ms/op
Iteration   1: 1.933 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   1.817 ms/op
                 getUser·p0.90:   2.327 ms/op
                 getUser·p0.95:   2.509 ms/op
                 getUser·p0.99:   3.892 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 12.348 ms/op
                 getUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16586
  mean =      1.933 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 228 
    [ 1.250,  2.500) = 15507 
    [ 2.500,  3.750) = 677 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.509 ms/op
     p(99.0000) =      3.892 ms/op
     p(99.9000) =     12.026 ms/op
     p(99.9900) =     12.348 ms/op
     p(99.9990) =     12.370 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.150 ms/op
Iteration   1: 3.755 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.288 ms/op
                 listUser·p0.99:   8.616 ms/op
                 listUser·p0.999:  20.365 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8510
  mean =      3.755 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 706 
    [ 2.500,  5.000) = 7283 
    [ 5.000,  7.500) = 420 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.288 ms/op
     p(99.0000) =      8.616 ms/op
     p(99.9000) =     20.365 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.333          ops/ms
ClientSimple.existUser                       thrpt         13.326          ops/ms
ClientSimple.getUser                         thrpt         13.862          ops/ms
ClientSimple.listUser                        thrpt          8.908          ops/ms
ClientSimple.createUser                       avgt          2.090           ms/op
ClientSimple.existUser                        avgt          1.947           ms/op
ClientSimple.getUser                          avgt          1.951           ms/op
ClientSimple.listUser                         avgt          3.694           ms/op
ClientSimple.createUser                     sample  14459   2.231 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.831           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.058           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.459           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.745           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.940           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.262           ms/op
ClientSimple.existUser                      sample  16201   1.972 ± 0.047   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.239           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.862           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.916           ms/op
ClientSimple.existUser:existUser·p0.999     sample         41.288           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         42.533           ms/op
ClientSimple.existUser:existUser·p1.00      sample         42.533           ms/op
ClientSimple.getUser                        sample  16586   1.933 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.737           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.817           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.509           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.892           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.026           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.348           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.370           ms/op
ClientSimple.listUser                       sample   8510   3.755 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.341           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.633           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.288           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.616           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.365           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.103           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.103           ms/op

Benchmark result is saved to 1714370727772.json
