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
# Warmup Iteration   1: 1.762 ops/ms
Iteration   1: 6.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.650 ops/ms


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
# Warmup Iteration   1: 5.937 ops/ms
Iteration   1: 12.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.563 ops/ms


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
# Warmup Iteration   1: 5.871 ops/ms
Iteration   1: 11.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.272 ops/ms


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
# Warmup Iteration   1: 5.078 ops/ms
Iteration   1: 7.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.730 ops/ms


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
# Warmup Iteration   1: 3.786 ±(99.9%) 0.069 ms/op
Iteration   1: 2.157 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.157 ms/op


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
# Warmup Iteration   1: 3.460 ±(99.9%) 0.053 ms/op
Iteration   1: 1.804 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.804 ms/op


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
# Warmup Iteration   1: 3.218 ±(99.9%) 0.068 ms/op
Iteration   1: 1.872 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.872 ms/op


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
# Warmup Iteration   1: 5.045 ±(99.9%) 0.108 ms/op
Iteration   1: 3.660 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.660 ms/op


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
# Warmup Iteration   1: 3.695 ±(99.9%) 0.097 ms/op
Iteration   1: 2.174 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   1.905 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  14.451 ms/op
                 createUser·p0.9999: 14.525 ms/op
                 createUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14709
  mean =      2.174 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 187 
    [ 1.250,  2.500) = 10319 
    [ 2.500,  3.750) = 3910 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     14.525 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.047 ±(99.9%) 0.062 ms/op
Iteration   1: 1.777 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   2.118 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   2.746 ms/op
                 existUser·p0.999:  34.996 ms/op
                 existUser·p0.9999: 36.005 ms/op
                 existUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18067
  mean =      1.777 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17547 
    [ 2.500,  5.000) = 456 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      2.746 ms/op
     p(99.9000) =     34.996 ms/op
     p(99.9900) =     36.005 ms/op
     p(99.9990) =     36.110 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.337 ±(99.9%) 0.082 ms/op
Iteration   1: 2.257 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.474 ms/op
                 getUser·p0.50:   2.163 ms/op
                 getUser·p0.90:   2.830 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.790 ms/op
                 getUser·p0.999:  12.171 ms/op
                 getUser·p0.9999: 12.281 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14144
  mean =      2.257 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 11307 
    [ 2.500,  3.750) = 2543 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      2.163 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.790 ms/op
     p(99.9000) =     12.171 ms/op
     p(99.9900) =     12.281 ms/op
     p(99.9990) =     12.288 ms/op
     p(99.9999) =     12.288 ms/op
    p(100.0000) =     12.288 ms/op


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
# Warmup Iteration   1: 4.884 ±(99.9%) 0.172 ms/op
Iteration   1: 3.421 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.387 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.621 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9480
  mean =      3.421 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1320 
    [ 2.500,  3.750) = 5086 
    [ 3.750,  5.000) = 2856 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.621 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.650          ops/ms
ClientSimple.existUser                       thrpt         12.563          ops/ms
ClientSimple.getUser                         thrpt         11.272          ops/ms
ClientSimple.listUser                        thrpt          7.730          ops/ms
ClientSimple.createUser                       avgt          2.157           ms/op
ClientSimple.existUser                        avgt          1.804           ms/op
ClientSimple.getUser                          avgt          1.872           ms/op
ClientSimple.listUser                         avgt          3.660           ms/op
ClientSimple.createUser                     sample  14709   2.174 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.699           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.905           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.056           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.330           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.448           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.451           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.525           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.533           ms/op
ClientSimple.existUser                      sample  18067   1.777 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.618           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.620           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.746           ms/op
ClientSimple.existUser:existUser·p0.999     sample         34.996           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         36.005           ms/op
ClientSimple.existUser:existUser·p1.00      sample         36.110           ms/op
ClientSimple.getUser                        sample  14144   2.257 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.474           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.163           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.195           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.790           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.171           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.281           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.288           ms/op
ClientSimple.listUser                       sample   9480   3.421 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.133           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.387           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.621           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.104           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.792           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.792           ms/op

Benchmark result is saved to 1714975556696.json
