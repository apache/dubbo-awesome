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
# Warmup Iteration   1: 1.860 ops/ms
Iteration   1: 6.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.997 ops/ms


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
# Warmup Iteration   1: 6.142 ops/ms
Iteration   1: 13.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.455 ops/ms


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
# Warmup Iteration   1: 6.853 ops/ms
Iteration   1: 15.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.519 ops/ms


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
# Warmup Iteration   1: 5.454 ops/ms
Iteration   1: 9.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.103 ops/ms


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.061 ms/op
Iteration   1: 2.214 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.214 ms/op


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
# Warmup Iteration   1: 2.766 ±(99.9%) 0.043 ms/op
Iteration   1: 1.614 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.614 ms/op


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
# Warmup Iteration   1: 3.152 ±(99.9%) 0.049 ms/op
Iteration   1: 1.875 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.875 ms/op


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.062 ms/op
Iteration   1: 3.670 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.670 ms/op


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
# Warmup Iteration   1: 3.394 ±(99.9%) 0.074 ms/op
Iteration   1: 1.868 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.534 ms/op
                 createUser·p0.50:   1.604 ms/op
                 createUser·p0.90:   2.367 ms/op
                 createUser·p0.95:   2.593 ms/op
                 createUser·p0.99:   6.669 ms/op
                 createUser·p0.999:  37.159 ms/op
                 createUser·p0.9999: 37.618 ms/op
                 createUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17096
  mean =      1.868 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15974 
    [ 2.500,  5.000) = 868 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.604 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      6.669 ms/op
     p(99.9000) =     37.159 ms/op
     p(99.9900) =     37.618 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.075 ms/op
Iteration   1: 1.754 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.306 ms/op
                 existUser·p0.50:   1.632 ms/op
                 existUser·p0.90:   2.163 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 14.058 ms/op
                 existUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18219
  mean =      1.754 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1664 
    [ 1.250,  2.500) = 15311 
    [ 2.500,  3.750) = 1052 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.306 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      2.163 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     14.058 ms/op
     p(99.9990) =     15.122 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.088 ms/op
Iteration   1: 2.110 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.011 ms/op
                 getUser·p0.90:   2.666 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   3.289 ms/op
                 getUser·p0.999:  12.861 ms/op
                 getUser·p0.9999: 13.212 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15160
  mean =      2.110 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 12362 
    [ 2.500,  3.750) = 2574 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      3.289 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     13.212 ms/op
     p(99.9990) =     13.255 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.192 ms/op
Iteration   1: 3.399 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.183 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  28.606 ms/op
                 listUser·p0.9999: 28.836 ms/op
                 listUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9416
  mean =      3.399 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 671 
    [ 2.500,  5.000) = 8561 
    [ 5.000,  7.500) = 87 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     28.606 ms/op
     p(99.9900) =     28.836 ms/op
     p(99.9990) =     28.836 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.997          ops/ms
ClientSimple.existUser                       thrpt         13.455          ops/ms
ClientSimple.getUser                         thrpt         15.519          ops/ms
ClientSimple.listUser                        thrpt          9.103          ops/ms
ClientSimple.createUser                       avgt          2.214           ms/op
ClientSimple.existUser                        avgt          1.614           ms/op
ClientSimple.getUser                          avgt          1.875           ms/op
ClientSimple.listUser                         avgt          3.670           ms/op
ClientSimple.createUser                     sample  17096   1.868 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.534           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.604           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.367           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.669           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.159           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.618           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.618           ms/op
ClientSimple.existUser                      sample  18219   1.754 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.306           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.632           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.163           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.030           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.845           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.058           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.122           ms/op
ClientSimple.getUser                        sample  15160   2.110 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.899           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.011           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.289           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.861           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.212           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.255           ms/op
ClientSimple.listUser                       sample   9416   3.399 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.094           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.183           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.076           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.454           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.606           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.836           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.836           ms/op

Benchmark result is saved to 1714716313399.json
