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
Iteration   1: 7.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.119 ops/ms


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
# Warmup Iteration   1: 6.782 ops/ms
Iteration   1: 13.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.388 ops/ms


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
# Warmup Iteration   1: 5.789 ops/ms
Iteration   1: 13.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.262 ops/ms


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
# Warmup Iteration   1: 5.057 ops/ms
Iteration   1: 6.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  6.501 ops/ms


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.063 ms/op
Iteration   1: 2.170 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.170 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.053 ms/op
Iteration   1: 1.972 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.972 ms/op


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.073 ms/op
Iteration   1: 2.184 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.184 ms/op


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.150 ms/op
Iteration   1: 3.241 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.241 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.092 ms/op
Iteration   1: 2.323 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   2.777 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  34.800 ms/op
                 createUser·p0.9999: 35.168 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13760
  mean =      2.323 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10863 
    [ 2.500,  5.000) = 2651 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =     11.108 ms/op
     p(99.9000) =     34.800 ms/op
     p(99.9900) =     35.168 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 2.926 ±(99.9%) 0.076 ms/op
Iteration   1: 2.082 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.017 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.732 ms/op
                 existUser·p0.99:   3.953 ms/op
                 existUser·p0.999:  11.266 ms/op
                 existUser·p0.9999: 11.464 ms/op
                 existUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15400
  mean =      2.082 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 199 
    [ 1.250,  2.500) = 13412 
    [ 2.500,  3.750) = 1614 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =     11.266 ms/op
     p(99.9900) =     11.464 ms/op
     p(99.9990) =     11.534 ms/op
     p(99.9999) =     11.534 ms/op
    p(100.0000) =     11.534 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.098 ms/op
Iteration   1: 2.010 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   1.907 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 12.612 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15986
  mean =      2.010 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 14517 
    [ 2.500,  3.750) = 1279 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     12.612 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.152 ms/op
Iteration   1: 3.269 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.670 ms/op
                 listUser·p0.999:  14.602 ms/op
                 listUser·p0.9999: 14.778 ms/op
                 listUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9783
  mean =      3.269 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1383 
    [ 2.500,  3.750) = 6694 
    [ 3.750,  5.000) = 1373 
    [ 5.000,  6.250) = 153 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.670 ms/op
     p(99.9000) =     14.602 ms/op
     p(99.9900) =     14.778 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.119          ops/ms
ClientSimple.existUser                       thrpt         13.388          ops/ms
ClientSimple.getUser                         thrpt         13.262          ops/ms
ClientSimple.listUser                        thrpt          6.501          ops/ms
ClientSimple.createUser                       avgt          2.170           ms/op
ClientSimple.existUser                        avgt          1.972           ms/op
ClientSimple.getUser                          avgt          2.184           ms/op
ClientSimple.listUser                         avgt          3.241           ms/op
ClientSimple.createUser                     sample  13760   2.323 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.524           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.052           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.108           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.800           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.168           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.193           ms/op
ClientSimple.existUser                      sample  15400   2.082 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.711           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.017           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.732           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.953           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.266           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.464           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.534           ms/op
ClientSimple.getUser                        sample  15986   2.010 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.974           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.907           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.678           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.435           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.612           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.632           ms/op
ClientSimple.listUser                       sample   9783   3.269 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.798           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.064           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.035           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.670           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.602           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.778           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.778           ms/op

Benchmark result is saved to 1717546544077.json
