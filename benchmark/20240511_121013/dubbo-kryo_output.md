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
# Warmup Iteration   1: 1.685 ops/ms
Iteration   1: 7.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.033 ops/ms


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
# Warmup Iteration   1: 5.658 ops/ms
Iteration   1: 12.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.647 ops/ms


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
# Warmup Iteration   1: 4.900 ops/ms
Iteration   1: 12.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.956 ops/ms


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
# Warmup Iteration   1: 4.734 ops/ms
Iteration   1: 9.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.138 ops/ms


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.056 ms/op
Iteration   1: 2.026 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.026 ms/op


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
# Warmup Iteration   1: 3.503 ±(99.9%) 0.058 ms/op
Iteration   1: 1.909 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.909 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.081 ms/op
Iteration   1: 2.046 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.046 ms/op


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.093 ms/op
Iteration   1: 2.973 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.973 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.085 ms/op
Iteration   1: 2.561 ±(99.9%) 0.071 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   2.281 ms/op
                 createUser·p0.90:   2.896 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   11.982 ms/op
                 createUser·p0.999:  41.073 ms/op
                 createUser·p0.9999: 41.860 ms/op
                 createUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12634
  mean =      2.561 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12346 
    [ 5.000, 10.000) = 70 
    [10.000, 15.000) = 154 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.281 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =     11.982 ms/op
     p(99.9000) =     41.073 ms/op
     p(99.9900) =     41.860 ms/op
     p(99.9990) =     41.878 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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
# Warmup Iteration   1: 2.944 ±(99.9%) 0.073 ms/op
Iteration   1: 2.028 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   2.050 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   3.355 ms/op
                 existUser·p0.999:  9.650 ms/op
                 existUser·p0.9999: 10.026 ms/op
                 existUser·p1.00:   10.158 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15761
  mean =      2.028 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 122 
    [ 1.000,  2.000) = 6873 
    [ 2.000,  3.000) = 8569 
    [ 3.000,  4.000) = 129 
    [ 4.000,  5.000) = 2 
    [ 5.000,  6.000) = 32 
    [ 6.000,  7.000) = 1 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.355 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     10.026 ms/op
     p(99.9990) =     10.158 ms/op
     p(99.9999) =     10.158 ms/op
    p(100.0000) =     10.158 ms/op


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
# Warmup Iteration   1: 3.158 ±(99.9%) 0.083 ms/op
Iteration   1: 2.285 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.187 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.876 ms/op
                 getUser·p0.999:  11.370 ms/op
                 getUser·p0.9999: 12.409 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13986
  mean =      2.285 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 9742 
    [ 2.500,  3.750) = 4028 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.876 ms/op
     p(99.9000) =     11.370 ms/op
     p(99.9900) =     12.409 ms/op
     p(99.9990) =     12.468 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.148 ms/op
Iteration   1: 3.441 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.183 ms/op
                 listUser·p0.90:   4.124 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  21.823 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9320
  mean =      3.441 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 274 
    [ 2.500,  5.000) = 8881 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.124 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     21.823 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.033          ops/ms
ClientSimple.existUser                       thrpt         12.647          ops/ms
ClientSimple.getUser                         thrpt         12.956          ops/ms
ClientSimple.listUser                        thrpt          9.138          ops/ms
ClientSimple.createUser                       avgt          2.026           ms/op
ClientSimple.existUser                        avgt          1.909           ms/op
ClientSimple.getUser                          avgt          2.046           ms/op
ClientSimple.listUser                         avgt          2.973           ms/op
ClientSimple.createUser                     sample  12634   2.561 ± 0.071   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.584           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.281           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.178           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.982           ms/op
ClientSimple.createUser:createUser·p0.999   sample         41.073           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         41.860           ms/op
ClientSimple.createUser:createUser·p1.00    sample         41.878           ms/op
ClientSimple.existUser                      sample  15761   2.028 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.601           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.050           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.355           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.650           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.026           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.158           ms/op
ClientSimple.getUser                        sample  13986   2.285 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.643           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.187           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.953           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.146           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.876           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.370           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.409           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.468           ms/op
ClientSimple.listUser                       sample   9320   3.441 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.114           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.183           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.124           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.291           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.823           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.577           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.577           ms/op

Benchmark result is saved to 1715429149176.json
