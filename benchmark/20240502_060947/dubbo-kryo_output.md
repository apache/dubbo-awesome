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
# Warmup Iteration   1: 1.818 ops/ms
Iteration   1: 6.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.873 ops/ms


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
# Warmup Iteration   1: 6.203 ops/ms
Iteration   1: 13.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.432 ops/ms


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
# Warmup Iteration   1: 5.497 ops/ms
Iteration   1: 12.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.389 ops/ms


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
# Warmup Iteration   1: 5.336 ops/ms
Iteration   1: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.398 ops/ms


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.073 ms/op
Iteration   1: 2.041 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.041 ms/op


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
# Warmup Iteration   1: 2.987 ±(99.9%) 0.041 ms/op
Iteration   1: 1.945 ±(99.9%) 0.019 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.058 ms/op
Iteration   1: 1.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.987 ms/op


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.074 ms/op
Iteration   1: 3.142 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.142 ms/op


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
# Warmup Iteration   1: 3.422 ±(99.9%) 0.083 ms/op
Iteration   1: 2.426 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   2.253 ms/op
                 createUser·p0.90:   2.851 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   7.026 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 22.249 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13175
  mean =      2.426 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9543 
    [ 2.500,  5.000) = 3356 
    [ 5.000,  7.500) = 146 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      7.026 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 2.997 ±(99.9%) 0.066 ms/op
Iteration   1: 1.777 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.387 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   2.095 ms/op
                 existUser·p0.95:   2.253 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  28.312 ms/op
                 existUser·p0.9999: 29.223 ms/op
                 existUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17988
  mean =      1.777 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17535 
    [ 2.500,  5.000) = 338 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      2.095 ms/op
     p(95.0000) =      2.253 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =     28.312 ms/op
     p(99.9900) =     29.223 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.079 ms/op
Iteration   1: 1.879 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   1.776 ms/op
                 getUser·p0.90:   2.363 ms/op
                 getUser·p0.95:   2.626 ms/op
                 getUser·p0.99:   3.183 ms/op
                 getUser·p0.999:  15.270 ms/op
                 getUser·p0.9999: 15.794 ms/op
                 getUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16999
  mean =      1.879 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 232 
    [ 1.250,  2.500) = 15554 
    [ 2.500,  3.750) = 1132 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.183 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     15.794 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.128 ms/op
Iteration   1: 3.378 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.683 ms/op
                 listUser·p0.50:   3.281 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9497
  mean =      3.378 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 1205 
    [ 2.500,  3.750) = 5998 
    [ 3.750,  5.000) = 1778 
    [ 5.000,  6.250) = 353 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.873          ops/ms
ClientSimple.existUser                       thrpt         13.432          ops/ms
ClientSimple.getUser                         thrpt         12.389          ops/ms
ClientSimple.listUser                        thrpt          8.398          ops/ms
ClientSimple.createUser                       avgt          2.041           ms/op
ClientSimple.existUser                        avgt          1.945           ms/op
ClientSimple.getUser                          avgt          1.987           ms/op
ClientSimple.listUser                         avgt          3.142           ms/op
ClientSimple.createUser                     sample  13175   2.426 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.652           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.253           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.150           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.026           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.840           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.249           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.249           ms/op
ClientSimple.existUser                      sample  17988   1.777 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.387           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.620           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.095           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.253           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.100           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.312           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.223           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.327           ms/op
ClientSimple.getUser                        sample  16999   1.879 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.735           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.776           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.363           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.183           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.270           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.794           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.024           ms/op
ClientSimple.listUser                       sample   9497   3.378 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.683           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.281           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.104           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.988           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.253           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.072           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.072           ms/op

Benchmark result is saved to 1714629925983.json
