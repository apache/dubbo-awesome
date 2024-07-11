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
# Warmup Iteration   1: 1.799 ops/ms
Iteration   1: 7.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.809 ops/ms


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
# Warmup Iteration   1: 5.597 ops/ms
Iteration   1: 12.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.405 ops/ms


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
# Warmup Iteration   1: 5.354 ops/ms
Iteration   1: 12.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.692 ops/ms


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
# Warmup Iteration   1: 4.855 ops/ms
Iteration   1: 8.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.814 ops/ms


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.070 ms/op
Iteration   1: 2.345 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.345 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.047 ms/op
Iteration   1: 2.128 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.128 ms/op


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
# Warmup Iteration   1: 3.488 ±(99.9%) 0.057 ms/op
Iteration   1: 1.878 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.878 ms/op


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.089 ms/op
Iteration   1: 3.393 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.393 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.074 ms/op
Iteration   1: 2.227 ±(99.9%) 0.062 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   1.935 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  35.869 ms/op
                 createUser·p0.9999: 36.971 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14341
  mean =      2.227 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12446 
    [ 2.500,  5.000) = 1607 
    [ 5.000,  7.500) = 165 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     35.869 ms/op
     p(99.9900) =     36.971 ms/op
     p(99.9990) =     37.028 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 2.917 ±(99.9%) 0.065 ms/op
Iteration   1: 1.709 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   1.624 ms/op
                 existUser·p0.90:   2.025 ms/op
                 existUser·p0.95:   2.228 ms/op
                 existUser·p0.99:   2.769 ms/op
                 existUser·p0.999:  11.600 ms/op
                 existUser·p0.9999: 12.284 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18709
  mean =      1.709 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 208 
    [ 1.250,  2.500) = 18131 
    [ 2.500,  3.750) = 280 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      1.624 ms/op
     p(90.0000) =      2.025 ms/op
     p(95.0000) =      2.228 ms/op
     p(99.0000) =      2.769 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     12.284 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.172 ±(99.9%) 0.080 ms/op
Iteration   1: 1.839 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   1.688 ms/op
                 getUser·p0.90:   2.310 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   3.314 ms/op
                 getUser·p0.999:  14.090 ms/op
                 getUser·p0.9999: 14.765 ms/op
                 getUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17510
  mean =      1.839 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 16219 
    [ 2.500,  3.750) = 994 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.314 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     14.765 ms/op
     p(99.9990) =     15.172 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 5.881 ±(99.9%) 0.182 ms/op
Iteration   1: 3.490 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.524 ms/op
                 listUser·p0.50:   3.408 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   8.935 ms/op
                 listUser·p0.999:  12.577 ms/op
                 listUser·p0.9999: 13.631 ms/op
                 listUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9167
  mean =      3.490 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 804 
    [ 2.500,  3.750) = 5706 
    [ 3.750,  5.000) = 2274 
    [ 5.000,  6.250) = 185 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      8.935 ms/op
     p(99.9000) =     12.577 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     13.631 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.809          ops/ms
ClientSimple.existUser                       thrpt         12.405          ops/ms
ClientSimple.getUser                         thrpt         12.692          ops/ms
ClientSimple.listUser                        thrpt          8.814          ops/ms
ClientSimple.createUser                       avgt          2.345           ms/op
ClientSimple.existUser                        avgt          2.128           ms/op
ClientSimple.getUser                          avgt          1.878           ms/op
ClientSimple.listUser                         avgt          3.393           ms/op
ClientSimple.createUser                     sample  14341   2.227 ± 0.062   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.572           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.935           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.088           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.315           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.869           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.971           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.028           ms/op
ClientSimple.existUser                      sample  18709   1.709 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.610           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.624           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.025           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.769           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.600           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.284           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.370           ms/op
ClientSimple.getUser                        sample  17510   1.839 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.750           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.688           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.310           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.314           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.090           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.765           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.172           ms/op
ClientSimple.listUser                       sample   9167   3.490 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.524           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.408           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.817           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.935           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.577           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.631           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.631           ms/op

Benchmark result is saved to 1720699610171.json
