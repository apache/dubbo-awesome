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
# Warmup Iteration   1: 2.062 ops/ms
Iteration   1: 6.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.682 ops/ms


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
# Warmup Iteration   1: 5.954 ops/ms
Iteration   1: 12.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.816 ops/ms


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
# Warmup Iteration   1: 6.016 ops/ms
Iteration   1: 12.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.069 ops/ms


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
# Warmup Iteration   1: 4.263 ops/ms
Iteration   1: 8.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.561 ops/ms


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
# Warmup Iteration   1: 4.652 ±(99.9%) 0.090 ms/op
Iteration   1: 2.207 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.207 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.054 ms/op
Iteration   1: 1.857 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.857 ms/op


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
# Warmup Iteration   1: 3.167 ±(99.9%) 0.053 ms/op
Iteration   1: 1.896 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.896 ms/op


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
# Warmup Iteration   1: 5.529 ±(99.9%) 0.114 ms/op
Iteration   1: 3.719 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.719 ms/op


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
# Warmup Iteration   1: 3.422 ±(99.9%) 0.081 ms/op
Iteration   1: 2.006 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.452 ms/op
                 createUser·p0.50:   1.831 ms/op
                 createUser·p0.90:   2.216 ms/op
                 createUser·p0.95:   2.548 ms/op
                 createUser·p0.99:   8.475 ms/op
                 createUser·p0.999:  16.679 ms/op
                 createUser·p0.9999: 17.334 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16070
  mean =      2.006 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 384 
    [ 1.250,  2.500) = 14834 
    [ 2.500,  3.750) = 479 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      8.475 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 2.939 ±(99.9%) 0.065 ms/op
Iteration   1: 1.956 ±(99.9%) 0.058 ms/op
                 existUser·p0.00:   0.477 ms/op
                 existUser·p0.50:   1.706 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  52.232 ms/op
                 existUser·p0.9999: 55.271 ms/op
                 existUser·p1.00:   55.312 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16342
  mean =      1.956 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16224 
    [ 5.000, 10.000) = 10 
    [10.000, 15.000) = 68 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 5 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =     52.232 ms/op
     p(99.9900) =     55.271 ms/op
     p(99.9990) =     55.312 ms/op
     p(99.9999) =     55.312 ms/op
    p(100.0000) =     55.312 ms/op


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
# Warmup Iteration   1: 3.515 ±(99.9%) 0.086 ms/op
Iteration   1: 2.026 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   1.925 ms/op
                 getUser·p0.90:   2.421 ms/op
                 getUser·p0.95:   2.630 ms/op
                 getUser·p0.99:   3.256 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 17.809 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15850
  mean =      2.026 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 14581 
    [ 2.500,  3.750) = 1167 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.256 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     17.809 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 5.400 ±(99.9%) 0.203 ms/op
Iteration   1: 3.668 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   6.160 ms/op
                 listUser·p0.999:  27.292 ms/op
                 listUser·p0.9999: 28.508 ms/op
                 listUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8705
  mean =      3.668 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 475 
    [ 2.500,  5.000) = 7780 
    [ 5.000,  7.500) = 408 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     27.292 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.682          ops/ms
ClientSimple.existUser                       thrpt         12.816          ops/ms
ClientSimple.getUser                         thrpt         12.069          ops/ms
ClientSimple.listUser                        thrpt          8.561          ops/ms
ClientSimple.createUser                       avgt          2.207           ms/op
ClientSimple.existUser                        avgt          1.857           ms/op
ClientSimple.getUser                          avgt          1.896           ms/op
ClientSimple.listUser                         avgt          3.719           ms/op
ClientSimple.createUser                     sample  16070   2.006 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.452           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.831           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.216           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.548           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.475           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.679           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.334           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.334           ms/op
ClientSimple.existUser                      sample  16342   1.956 ± 0.058   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.477           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.706           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.301           ms/op
ClientSimple.existUser:existUser·p0.999     sample         52.232           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         55.271           ms/op
ClientSimple.existUser:existUser·p1.00      sample         55.312           ms/op
ClientSimple.getUser                        sample  15850   2.026 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.693           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.925           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.256           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.908           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.809           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.924           ms/op
ClientSimple.listUser                       sample   8705   3.668 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.403           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.572           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.022           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.160           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.292           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.508           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.508           ms/op

Benchmark result is saved to 1716444330819.json
