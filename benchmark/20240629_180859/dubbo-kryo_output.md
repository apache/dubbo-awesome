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
# Warmup Iteration   1: 1.999 ops/ms
Iteration   1: 7.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.800 ops/ms


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
# Warmup Iteration   1: 5.727 ops/ms
Iteration   1: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.776 ops/ms


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
# Warmup Iteration   1: 5.489 ops/ms
Iteration   1: 12.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.998 ops/ms


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
# Warmup Iteration   1: 5.962 ops/ms
Iteration   1: 9.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.087 ops/ms


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.087 ms/op
Iteration   1: 2.355 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.355 ms/op


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
# Warmup Iteration   1: 3.219 ±(99.9%) 0.049 ms/op
Iteration   1: 1.835 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.835 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.064 ms/op
Iteration   1: 2.166 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.166 ms/op


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
# Warmup Iteration   1: 4.901 ±(99.9%) 0.104 ms/op
Iteration   1: 3.475 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.475 ms/op


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
# Warmup Iteration   1: 3.530 ±(99.9%) 0.108 ms/op
Iteration   1: 2.275 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.381 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   6.599 ms/op
                 createUser·p0.999:  33.386 ms/op
                 createUser·p0.9999: 35.656 ms/op
                 createUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14048
  mean =      2.275 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11078 
    [ 2.500,  5.000) = 2784 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      6.599 ms/op
     p(99.9000) =     33.386 ms/op
     p(99.9900) =     35.656 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 2.845 ±(99.9%) 0.072 ms/op
Iteration   1: 1.697 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.429 ms/op
                 existUser·p0.50:   1.616 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.281 ms/op
                 existUser·p0.99:   2.933 ms/op
                 existUser·p0.999:  13.238 ms/op
                 existUser·p0.9999: 14.010 ms/op
                 existUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18846
  mean =      1.697 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 881 
    [ 1.250,  2.500) = 17640 
    [ 2.500,  3.750) = 230 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      1.616 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.281 ms/op
     p(99.0000) =      2.933 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     14.010 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.080 ms/op
Iteration   1: 1.921 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.225 ms/op
                 getUser·p0.50:   1.864 ms/op
                 getUser·p0.90:   2.425 ms/op
                 getUser·p0.95:   2.568 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  12.616 ms/op
                 getUser·p0.9999: 13.387 ms/op
                 getUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16806
  mean =      1.921 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1200 
    [ 1.250,  2.500) = 14450 
    [ 2.500,  3.750) = 976 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.225 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =     12.616 ms/op
     p(99.9900) =     13.387 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.123 ms/op
Iteration   1: 3.285 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 15.794 ms/op
                 listUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9864
  mean =      3.285 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 242 
    [ 2.500,  3.750) = 7969 
    [ 3.750,  5.000) = 1350 
    [ 5.000,  6.250) = 139 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     15.630 ms/op
     p(99.9900) =     15.794 ms/op
     p(99.9990) =     15.794 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.800          ops/ms
ClientSimple.existUser                       thrpt         12.776          ops/ms
ClientSimple.getUser                         thrpt         12.998          ops/ms
ClientSimple.listUser                        thrpt          9.087          ops/ms
ClientSimple.createUser                       avgt          2.355           ms/op
ClientSimple.existUser                        avgt          1.835           ms/op
ClientSimple.getUser                          avgt          2.166           ms/op
ClientSimple.listUser                         avgt          3.475           ms/op
ClientSimple.createUser                     sample  14048   2.275 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.381           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.599           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.386           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.656           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.372           ms/op
ClientSimple.existUser                      sample  18846   1.697 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.429           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.616           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.933           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.238           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.010           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.025           ms/op
ClientSimple.getUser                        sample  16806   1.921 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.225           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.864           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.425           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.764           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.616           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.387           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.599           ms/op
ClientSimple.listUser                       sample   9864   3.285 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.157           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.986           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.039           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.414           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.630           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.794           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.794           ms/op

Benchmark result is saved to 1719684282846.json
