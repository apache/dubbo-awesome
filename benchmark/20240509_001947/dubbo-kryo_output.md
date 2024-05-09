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
# Warmup Iteration   1: 2.063 ops/ms
Iteration   1: 7.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.945 ops/ms


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
# Warmup Iteration   1: 5.798 ops/ms
Iteration   1: 11.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.683 ops/ms


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
# Warmup Iteration   1: 5.368 ops/ms
Iteration   1: 11.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.493 ops/ms


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
# Warmup Iteration   1: 5.415 ops/ms
Iteration   1: 8.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.133 ops/ms


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.067 ms/op
Iteration   1: 2.093 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.093 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.050 ms/op
Iteration   1: 1.862 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.862 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.051 ms/op
Iteration   1: 2.220 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.220 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.103 ms/op
Iteration   1: 3.123 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.123 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.097 ms/op
Iteration   1: 2.232 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  13.101 ms/op
                 createUser·p0.9999: 13.523 ms/op
                 createUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14350
  mean =      2.232 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 11507 
    [ 2.500,  3.750) = 2551 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     13.101 ms/op
     p(99.9900) =     13.523 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


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
# Warmup Iteration   1: 2.794 ±(99.9%) 0.067 ms/op
Iteration   1: 1.773 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   1.642 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   2.744 ms/op
                 existUser·p0.999:  13.894 ms/op
                 existUser·p0.9999: 15.047 ms/op
                 existUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18072
  mean =      1.773 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 17173 
    [ 2.500,  3.750) = 712 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      2.744 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     15.047 ms/op
     p(99.9990) =     15.073 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 3.152 ±(99.9%) 0.073 ms/op
Iteration   1: 1.906 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   1.784 ms/op
                 getUser·p0.90:   2.458 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   3.103 ms/op
                 getUser·p0.999:  26.346 ms/op
                 getUser·p0.9999: 27.345 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16968
  mean =      1.906 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15509 
    [ 2.500,  5.000) = 1357 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.103 ms/op
     p(99.9000) =     26.346 ms/op
     p(99.9900) =     27.345 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.130 ms/op
Iteration   1: 3.310 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.729 ms/op
                 listUser·p0.50:   3.170 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.665 ms/op
                 listUser·p0.999:  23.047 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9671
  mean =      3.310 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1139 
    [ 2.500,  5.000) = 8361 
    [ 5.000,  7.500) = 118 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.665 ms/op
     p(99.9000) =     23.047 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.945          ops/ms
ClientSimple.existUser                       thrpt         11.683          ops/ms
ClientSimple.getUser                         thrpt         11.493          ops/ms
ClientSimple.listUser                        thrpt          8.133          ops/ms
ClientSimple.createUser                       avgt          2.093           ms/op
ClientSimple.existUser                        avgt          1.862           ms/op
ClientSimple.getUser                          avgt          2.220           ms/op
ClientSimple.listUser                         avgt          3.123           ms/op
ClientSimple.createUser                     sample  14350   2.232 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.613           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.218           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.101           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.523           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.566           ms/op
ClientSimple.existUser                      sample  18072   1.773 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.440           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.642           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.894           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.047           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.073           ms/op
ClientSimple.getUser                        sample  16968   1.906 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.609           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.784           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.103           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.346           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.345           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.460           ms/op
ClientSimple.listUser                       sample   9671   3.310 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.729           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.170           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.994           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.665           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.047           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.069           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.069           ms/op

Benchmark result is saved to 1715213723470.json
