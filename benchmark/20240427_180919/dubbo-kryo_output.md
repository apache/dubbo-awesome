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
# Warmup Iteration   1: 1.663 ops/ms
Iteration   1: 6.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.842 ops/ms


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
# Warmup Iteration   1: 6.759 ops/ms
Iteration   1: 14.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.079 ops/ms


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
# Warmup Iteration   1: 5.589 ops/ms
Iteration   1: 12.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.650 ops/ms


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
# Warmup Iteration   1: 4.219 ops/ms
Iteration   1: 8.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.094 ops/ms


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.068 ms/op
Iteration   1: 2.202 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.202 ms/op


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
# Warmup Iteration   1: 2.978 ±(99.9%) 0.046 ms/op
Iteration   1: 1.945 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.945 ms/op


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
# Warmup Iteration   1: 3.443 ±(99.9%) 0.067 ms/op
Iteration   1: 2.051 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.051 ms/op


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.122 ms/op
Iteration   1: 3.313 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.313 ms/op


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
# Warmup Iteration   1: 3.686 ±(99.9%) 0.090 ms/op
Iteration   1: 2.274 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   2.191 ms/op
                 createUser·p0.90:   2.683 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   5.229 ms/op
                 createUser·p0.999:  14.712 ms/op
                 createUser·p0.9999: 15.424 ms/op
                 createUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14073
  mean =      2.274 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 11312 
    [ 2.500,  3.750) = 2468 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      5.229 ms/op
     p(99.9000) =     14.712 ms/op
     p(99.9900) =     15.424 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.069 ms/op
Iteration   1: 2.007 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.248 ms/op
                 existUser·p0.999:  20.120 ms/op
                 existUser·p0.9999: 20.283 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15921
  mean =      2.007 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14830 
    [ 2.500,  5.000) = 1054 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.248 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 3.443 ±(99.9%) 0.087 ms/op
Iteration   1: 2.132 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.536 ms/op
                 getUser·p0.50:   2.097 ms/op
                 getUser·p0.90:   2.486 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   4.051 ms/op
                 getUser·p0.999:  16.269 ms/op
                 getUser·p0.9999: 16.843 ms/op
                 getUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15007
  mean =      2.132 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 13477 
    [ 2.500,  3.750) = 1228 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.117 ms/op
Iteration   1: 3.383 ±(99.9%) 0.117 ms/op
                 listUser·p0.00:   0.595 ms/op
                 listUser·p0.50:   2.859 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.564 ms/op
                 listUser·p0.99:   15.182 ms/op
                 listUser·p0.999:  63.274 ms/op
                 listUser·p0.9999: 66.585 ms/op
                 listUser·p1.00:   66.585 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9516
  mean =      3.383 ±(99.9%) 0.117 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9184 
    [ 5.000, 10.000) = 223 
    [10.000, 15.000) = 10 
    [15.000, 20.000) = 61 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.564 ms/op
     p(99.0000) =     15.182 ms/op
     p(99.9000) =     63.274 ms/op
     p(99.9900) =     66.585 ms/op
     p(99.9990) =     66.585 ms/op
     p(99.9999) =     66.585 ms/op
    p(100.0000) =     66.585 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.842          ops/ms
ClientSimple.existUser                       thrpt         14.079          ops/ms
ClientSimple.getUser                         thrpt         12.650          ops/ms
ClientSimple.listUser                        thrpt          8.094          ops/ms
ClientSimple.createUser                       avgt          2.202           ms/op
ClientSimple.existUser                        avgt          1.945           ms/op
ClientSimple.getUser                          avgt          2.051           ms/op
ClientSimple.listUser                         avgt          3.313           ms/op
ClientSimple.createUser                     sample  14073   2.274 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.749           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.191           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.229           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.712           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.424           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.598           ms/op
ClientSimple.existUser                      sample  15921   2.007 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.450           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.964           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.248           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.120           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.283           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.283           ms/op
ClientSimple.getUser                        sample  15007   2.132 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.536           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.097           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.486           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.051           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.269           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.843           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.843           ms/op
ClientSimple.listUser                       sample   9516   3.383 ± 0.117   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.595           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.859           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.564           ms/op
ClientSimple.listUser:listUser·p0.99        sample         15.182           ms/op
ClientSimple.listUser:listUser·p0.999       sample         63.274           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         66.585           ms/op
ClientSimple.listUser:listUser·p1.00        sample         66.585           ms/op

Benchmark result is saved to 1714241079688.json
