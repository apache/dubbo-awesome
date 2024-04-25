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
# Warmup Iteration   1: 0.731 ops/ms
Iteration   1: 6.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.083 ops/ms


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
# Warmup Iteration   1: 6.514 ops/ms
Iteration   1: 11.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.133 ops/ms


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
# Warmup Iteration   1: 6.105 ops/ms
Iteration   1: 11.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.322 ops/ms


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
# Warmup Iteration   1: 4.803 ops/ms
Iteration   1: 8.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.772 ops/ms


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.074 ms/op
Iteration   1: 2.102 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.102 ms/op


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
# Warmup Iteration   1: 2.990 ±(99.9%) 0.044 ms/op
Iteration   1: 1.880 ±(99.9%) 0.023 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.082 ±(99.9%) 0.046 ms/op
Iteration   1: 2.043 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.043 ms/op


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
# Warmup Iteration   1: 4.805 ±(99.9%) 0.082 ms/op
Iteration   1: 3.376 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.376 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.091 ms/op
Iteration   1: 2.356 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   2.062 ms/op
                 createUser·p0.90:   2.720 ms/op
                 createUser·p0.95:   3.031 ms/op
                 createUser·p0.99:   11.753 ms/op
                 createUser·p0.999:  29.790 ms/op
                 createUser·p0.9999: 30.343 ms/op
                 createUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13555
  mean =      2.356 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11033 
    [ 2.500,  5.000) = 2238 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =     11.753 ms/op
     p(99.9000) =     29.790 ms/op
     p(99.9900) =     30.343 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.071 ms/op
Iteration   1: 1.838 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.404 ms/op
                 existUser·p0.50:   1.692 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   3.273 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 13.996 ms/op
                 existUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17455
  mean =      1.838 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 240 
    [ 1.250,  2.500) = 15775 
    [ 2.500,  3.750) = 1344 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.273 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     13.996 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.085 ms/op
Iteration   1: 2.170 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.488 ms/op
                 getUser·p0.50:   2.091 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.798 ms/op
                 getUser·p0.99:   3.861 ms/op
                 getUser·p0.999:  29.172 ms/op
                 getUser·p0.9999: 30.202 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14733
  mean =      2.170 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12457 
    [ 2.500,  5.000) = 2149 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      2.091 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.861 ms/op
     p(99.9000) =     29.172 ms/op
     p(99.9900) =     30.202 ms/op
     p(99.9990) =     30.310 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 4.728 ±(99.9%) 0.156 ms/op
Iteration   1: 3.458 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.657 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.524 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  19.325 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9253
  mean =      3.458 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 956 
    [ 2.500,  5.000) = 8018 
    [ 5.000,  7.500) = 232 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.524 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     19.325 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.083          ops/ms
ClientSimple.existUser                       thrpt         11.133          ops/ms
ClientSimple.getUser                         thrpt         11.322          ops/ms
ClientSimple.listUser                        thrpt          8.772          ops/ms
ClientSimple.createUser                       avgt          2.102           ms/op
ClientSimple.existUser                        avgt          1.880           ms/op
ClientSimple.getUser                          avgt          2.043           ms/op
ClientSimple.listUser                         avgt          3.376           ms/op
ClientSimple.createUser                     sample  13555   2.356 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.578           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.062           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.031           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.753           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.790           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.343           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.343           ms/op
ClientSimple.existUser                      sample  17455   1.838 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.404           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.692           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.273           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.746           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.996           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.008           ms/op
ClientSimple.getUser                        sample  14733   2.170 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.488           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.091           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.861           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.172           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.202           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.310           ms/op
ClientSimple.listUser                       sample   9253   3.458 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.657           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.524           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.963           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.325           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.234           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.234           ms/op

Benchmark result is saved to 1714004122327.json
