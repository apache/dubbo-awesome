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
# Warmup Iteration   1: 0.977 ops/ms
Iteration   1: 7.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.432 ops/ms


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
# Warmup Iteration   1: 5.920 ops/ms
Iteration   1: 13.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.416 ops/ms


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
# Warmup Iteration   1: 5.399 ops/ms
Iteration   1: 14.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.176 ops/ms


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
# Warmup Iteration   1: 4.438 ops/ms
Iteration   1: 8.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.255 ops/ms


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.077 ms/op
Iteration   1: 2.207 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.207 ms/op


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
# Warmup Iteration   1: 3.332 ±(99.9%) 0.053 ms/op
Iteration   1: 2.110 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ±(99.9%) 0.066 ms/op
Iteration   1: 2.116 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.116 ms/op


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.088 ms/op
Iteration   1: 3.383 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.383 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.077 ms/op
Iteration   1: 2.194 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.465 ms/op
                 createUser·p0.50:   2.009 ms/op
                 createUser·p0.90:   2.748 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  14.376 ms/op
                 createUser·p0.9999: 14.549 ms/op
                 createUser·p1.00:   14.549 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14567
  mean =      2.194 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 183 
    [ 1.250,  2.500) = 11408 
    [ 2.500,  3.750) = 2600 
    [ 3.750,  5.000) = 191 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     14.376 ms/op
     p(99.9900) =     14.549 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.139 ±(99.9%) 0.074 ms/op
Iteration   1: 1.868 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   1.808 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.211 ms/op
                 existUser·p0.999:  12.449 ms/op
                 existUser·p0.9999: 13.487 ms/op
                 existUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17092
  mean =      1.868 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 597 
    [ 1.250,  2.500) = 15899 
    [ 2.500,  3.750) = 514 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.211 ms/op
     p(99.9000) =     12.449 ms/op
     p(99.9900) =     13.487 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.080 ms/op
Iteration   1: 1.853 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   1.751 ms/op
                 getUser·p0.90:   2.339 ms/op
                 getUser·p0.95:   2.572 ms/op
                 getUser·p0.99:   4.701 ms/op
                 getUser·p0.999:  22.051 ms/op
                 getUser·p0.9999: 23.471 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17212
  mean =      1.853 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16173 
    [ 2.500,  5.000) = 897 
    [ 5.000,  7.500) = 81 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      4.701 ms/op
     p(99.9000) =     22.051 ms/op
     p(99.9900) =     23.471 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.150 ms/op
Iteration   1: 3.403 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.363 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  11.895 ms/op
                 listUser·p0.9999: 15.614 ms/op
                 listUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9405
  mean =      3.403 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 1144 
    [ 2.500,  3.750) = 5569 
    [ 3.750,  5.000) = 2424 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     15.614 ms/op
     p(99.9990) =     15.614 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.432          ops/ms
ClientSimple.existUser                       thrpt         13.416          ops/ms
ClientSimple.getUser                         thrpt         14.176          ops/ms
ClientSimple.listUser                        thrpt          8.255          ops/ms
ClientSimple.createUser                       avgt          2.207           ms/op
ClientSimple.existUser                        avgt          2.110           ms/op
ClientSimple.getUser                          avgt          2.116           ms/op
ClientSimple.listUser                         avgt          3.383           ms/op
ClientSimple.createUser                     sample  14567   2.194 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.465           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.009           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.275           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.376           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.549           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.549           ms/op
ClientSimple.existUser                      sample  17092   1.868 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.549           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.808           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.211           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.449           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.487           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.533           ms/op
ClientSimple.getUser                        sample  17212   1.853 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.669           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.751           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.701           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.051           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.471           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.495           ms/op
ClientSimple.listUser                       sample   9405   3.403 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.014           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.363           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.487           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.895           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.614           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.614           ms/op

Benchmark result is saved to 1714759491752.json
