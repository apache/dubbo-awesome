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
# Warmup Iteration   1: 2.013 ops/ms
Iteration   1: 7.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.023 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.802 ops/ms
Iteration   1: 12.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.127 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.018 ops/ms
Iteration   1: 12.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.082 ops/ms


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
# Warmup Iteration   1: 4.741 ops/ms
Iteration   1: 8.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.408 ops/ms


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.091 ms/op
Iteration   1: 2.110 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.110 ms/op


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
# Warmup Iteration   1: 3.010 ±(99.9%) 0.052 ms/op
Iteration   1: 1.901 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.901 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.073 ms/op
Iteration   1: 2.142 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.142 ms/op


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.077 ms/op
Iteration   1: 3.236 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.236 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.128 ms/op
Iteration   1: 2.139 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.468 ms/op
                 createUser·p0.50:   1.878 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   3.343 ms/op
                 createUser·p0.99:   8.148 ms/op
                 createUser·p0.999:  31.449 ms/op
                 createUser·p0.9999: 32.370 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15237
  mean =      2.139 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13398 
    [ 2.500,  5.000) = 1512 
    [ 5.000,  7.500) = 157 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      3.343 ms/op
     p(99.0000) =      8.148 ms/op
     p(99.9000) =     31.449 ms/op
     p(99.9900) =     32.370 ms/op
     p(99.9990) =     32.834 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.223 ms/op
Iteration   1: 1.997 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.412 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.552 ms/op
                 existUser·p0.99:   5.118 ms/op
                 existUser·p0.999:  21.299 ms/op
                 existUser·p0.9999: 22.000 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16019
  mean =      1.997 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15114 
    [ 2.500,  5.000) = 710 
    [ 5.000,  7.500) = 130 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.552 ms/op
     p(99.0000) =      5.118 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     22.000 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.078 ms/op
Iteration   1: 2.101 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.362 ms/op
                 getUser·p0.50:   1.909 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   3.933 ms/op
                 getUser·p0.999:  30.391 ms/op
                 getUser·p0.9999: 31.995 ms/op
                 getUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15282
  mean =      2.101 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13833 
    [ 2.500,  5.000) = 1357 
    [ 5.000,  7.500) = 26 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.933 ms/op
     p(99.9000) =     30.391 ms/op
     p(99.9900) =     31.995 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.153 ms/op
Iteration   1: 3.643 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.533 ms/op
                 listUser·p0.999:  27.361 ms/op
                 listUser·p0.9999: 29.327 ms/op
                 listUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8839
  mean =      3.643 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 686 
    [ 2.500,  5.000) = 7903 
    [ 5.000,  7.500) = 159 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.533 ms/op
     p(99.9000) =     27.361 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.023          ops/ms
ClientSimple.existUser                       thrpt         12.127          ops/ms
ClientSimple.getUser                         thrpt         12.082          ops/ms
ClientSimple.listUser                        thrpt          8.408          ops/ms
ClientSimple.createUser                       avgt          2.110           ms/op
ClientSimple.existUser                        avgt          1.901           ms/op
ClientSimple.getUser                          avgt          2.142           ms/op
ClientSimple.listUser                         avgt          3.236           ms/op
ClientSimple.createUser                     sample  15237   2.139 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.468           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.878           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.343           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.148           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.449           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.370           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.834           ms/op
ClientSimple.existUser                      sample  16019   1.997 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.412           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.552           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.118           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.299           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.000           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.020           ms/op
ClientSimple.getUser                        sample  15282   2.101 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.362           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.909           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.933           ms/op
ClientSimple.getUser:getUser·p0.999         sample         30.391           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         31.995           ms/op
ClientSimple.getUser:getUser·p1.00          sample         32.047           ms/op
ClientSimple.listUser                       sample   8839   3.643 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.196           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.533           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.361           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.327           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.327           ms/op

Benchmark result is saved to 1715925947916.json
