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
# Warmup Iteration   1: 1.561 ops/ms
Iteration   1: 6.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.934 ops/ms


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
# Warmup Iteration   1: 6.800 ops/ms
Iteration   1: 12.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.878 ops/ms


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
# Warmup Iteration   1: 6.588 ops/ms
Iteration   1: 12.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.840 ops/ms


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
# Warmup Iteration   1: 5.229 ops/ms
Iteration   1: 9.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.731 ops/ms


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.065 ms/op
Iteration   1: 2.071 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.071 ms/op


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
# Warmup Iteration   1: 2.863 ±(99.9%) 0.049 ms/op
Iteration   1: 1.721 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.721 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.050 ms/op
Iteration   1: 1.965 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.965 ms/op


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.079 ms/op
Iteration   1: 3.028 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.028 ms/op


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
# Warmup Iteration   1: 3.480 ±(99.9%) 0.097 ms/op
Iteration   1: 2.082 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.425 ms/op
                 createUser·p0.95:   2.716 ms/op
                 createUser·p0.99:   7.122 ms/op
                 createUser·p0.999:  31.326 ms/op
                 createUser·p0.9999: 31.654 ms/op
                 createUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15357
  mean =      2.082 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14157 
    [ 2.500,  5.000) = 1033 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      7.122 ms/op
     p(99.9000) =     31.326 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     31.654 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 2.921 ±(99.9%) 0.071 ms/op
Iteration   1: 1.972 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.214 ms/op
                 existUser·p0.50:   1.823 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.188 ms/op
                 existUser·p0.999:  29.327 ms/op
                 existUser·p0.9999: 30.765 ms/op
                 existUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16331
  mean =      1.972 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15169 
    [ 2.500,  5.000) = 1088 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.214 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.188 ms/op
     p(99.9000) =     29.327 ms/op
     p(99.9900) =     30.765 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.078 ms/op
Iteration   1: 1.978 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   1.890 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.699 ms/op
                 getUser·p0.99:   3.495 ms/op
                 getUser·p0.999:  14.762 ms/op
                 getUser·p0.9999: 14.856 ms/op
                 getUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16164
  mean =      1.978 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 435 
    [ 1.250,  2.500) = 14221 
    [ 2.500,  3.750) = 1378 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.495 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     14.856 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.126 ms/op
Iteration   1: 3.615 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.591 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.202 ms/op
                 listUser·p0.999:  10.242 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8856
  mean =      3.615 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 568 
    [ 2.500,  3.750) = 4241 
    [ 3.750,  5.000) = 3573 
    [ 5.000,  6.250) = 282 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.202 ms/op
     p(99.9000) =     10.242 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.934          ops/ms
ClientSimple.existUser                       thrpt         12.878          ops/ms
ClientSimple.getUser                         thrpt         12.840          ops/ms
ClientSimple.listUser                        thrpt          9.731          ops/ms
ClientSimple.createUser                       avgt          2.071           ms/op
ClientSimple.existUser                        avgt          1.721           ms/op
ClientSimple.getUser                          avgt          1.965           ms/op
ClientSimple.listUser                         avgt          3.028           ms/op
ClientSimple.createUser                     sample  15357   2.082 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.708           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.425           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.122           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.326           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.654           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.654           ms/op
ClientSimple.existUser                      sample  16331   1.972 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.214           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.823           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.188           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.327           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.765           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.097           ms/op
ClientSimple.getUser                        sample  16164   1.978 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.653           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.890           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.495           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.762           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.856           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.877           ms/op
ClientSimple.listUser                       sample   8856   3.615 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.591           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.625           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.497           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.014           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.202           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.242           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.990           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.990           ms/op

Benchmark result is saved to 1715904931642.json
