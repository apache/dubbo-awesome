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
# Warmup Iteration   1: 1.870 ops/ms
Iteration   1: 6.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.266 ops/ms


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
# Warmup Iteration   1: 6.816 ops/ms
Iteration   1: 14.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.917 ops/ms


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
# Warmup Iteration   1: 4.652 ops/ms
Iteration   1: 11.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.285 ops/ms


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
# Warmup Iteration   1: 4.359 ops/ms
Iteration   1: 8.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.279 ops/ms


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.084 ms/op
Iteration   1: 2.381 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.381 ms/op


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
# Warmup Iteration   1: 3.365 ±(99.9%) 0.058 ms/op
Iteration   1: 1.853 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.853 ms/op


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
# Warmup Iteration   1: 3.402 ±(99.9%) 0.058 ms/op
Iteration   1: 2.155 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.155 ms/op


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.102 ms/op
Iteration   1: 3.418 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.418 ms/op


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.100 ms/op
Iteration   1: 2.133 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   1.872 ms/op
                 createUser·p0.90:   2.458 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   8.263 ms/op
                 createUser·p0.999:  34.472 ms/op
                 createUser·p0.9999: 36.864 ms/op
                 createUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14989
  mean =      2.133 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13607 
    [ 2.500,  5.000) = 1171 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      8.263 ms/op
     p(99.9000) =     34.472 ms/op
     p(99.9900) =     36.864 ms/op
     p(99.9990) =     37.093 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 3.120 ±(99.9%) 0.140 ms/op
Iteration   1: 2.094 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   1.974 ms/op
                 existUser·p0.90:   2.626 ms/op
                 existUser·p0.95:   2.871 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  13.611 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15264
  mean =      2.094 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 320 
    [ 1.250,  2.500) = 12458 
    [ 2.500,  3.750) = 2185 
    [ 3.750,  5.000) = 179 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =     13.611 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 3.424 ±(99.9%) 0.094 ms/op
Iteration   1: 1.953 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   1.894 ms/op
                 getUser·p0.90:   2.396 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   4.406 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 13.319 ms/op
                 getUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16412
  mean =      1.953 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 859 
    [ 1.250,  2.500) = 14418 
    [ 2.500,  3.750) = 900 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.406 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     13.319 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 4.592 ±(99.9%) 0.147 ms/op
Iteration   1: 3.169 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.965 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10089
  mean =      3.169 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 788 
    [ 2.500,  5.000) = 9135 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.965 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.266          ops/ms
ClientSimple.existUser                       thrpt         14.917          ops/ms
ClientSimple.getUser                         thrpt         11.285          ops/ms
ClientSimple.listUser                        thrpt          8.279          ops/ms
ClientSimple.createUser                       avgt          2.381           ms/op
ClientSimple.existUser                        avgt          1.853           ms/op
ClientSimple.getUser                          avgt          2.155           ms/op
ClientSimple.listUser                         avgt          3.418           ms/op
ClientSimple.createUser                     sample  14989   2.133 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.818           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.872           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.458           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.263           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.472           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.864           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.093           ms/op
ClientSimple.existUser                      sample  15264   2.094 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.440           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.974           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.871           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.669           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.611           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.812           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.812           ms/op
ClientSimple.getUser                        sample  16412   1.953 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.689           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.894           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.396           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.406           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.435           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.319           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.844           ms/op
ClientSimple.listUser                       sample  10089   3.169 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.886           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.970           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.916           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.965           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.201           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.430           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.430           ms/op

Benchmark result is saved to 1724263542936.json
