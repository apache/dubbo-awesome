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
# Warmup Iteration   1: 2.036 ops/ms
Iteration   1: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.448 ops/ms


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
# Warmup Iteration   1: 6.399 ops/ms
Iteration   1: 14.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.084 ops/ms


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
# Warmup Iteration   1: 6.928 ops/ms
Iteration   1: 13.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.780 ops/ms


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
# Warmup Iteration   1: 4.557 ops/ms
Iteration   1: 9.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.036 ops/ms


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
# Warmup Iteration   1: 3.552 ±(99.9%) 0.070 ms/op
Iteration   1: 2.331 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.331 ms/op


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
# Warmup Iteration   1: 3.410 ±(99.9%) 0.081 ms/op
Iteration   1: 2.083 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.083 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.071 ms/op
Iteration   1: 1.990 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.990 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.102 ms/op
Iteration   1: 3.577 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.577 ms/op


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
# Warmup Iteration   1: 3.563 ±(99.9%) 0.084 ms/op
Iteration   1: 2.237 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   1.994 ms/op
                 createUser·p0.90:   2.699 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   11.338 ms/op
                 createUser·p0.999:  28.246 ms/op
                 createUser·p0.9999: 29.252 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14288
  mean =      2.237 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11778 
    [ 2.500,  5.000) = 2218 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      1.994 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     28.246 ms/op
     p(99.9900) =     29.252 ms/op
     p(99.9990) =     29.393 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.082 ms/op
Iteration   1: 2.010 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   2.001 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   3.166 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 10.526 ms/op
                 existUser·p1.00:   10.584 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15883
  mean =      2.010 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 6 
    [ 1.000,  2.000) = 7926 
    [ 2.000,  3.000) = 7668 
    [ 3.000,  4.000) = 207 
    [ 4.000,  5.000) = 3 
    [ 5.000,  6.000) = 32 
    [ 6.000,  7.000) = 9 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.166 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     10.526 ms/op
     p(99.9990) =     10.584 ms/op
     p(99.9999) =     10.584 ms/op
    p(100.0000) =     10.584 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.083 ms/op
Iteration   1: 2.206 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.509 ms/op
                 getUser·p0.50:   2.097 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   4.049 ms/op
                 getUser·p0.999:  25.625 ms/op
                 getUser·p0.9999: 26.483 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14493
  mean =      2.206 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11336 
    [ 2.500,  5.000) = 3041 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      4.049 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     26.483 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.158 ms/op
Iteration   1: 3.448 ±(99.9%) 0.090 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.228 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   14.599 ms/op
                 listUser·p0.999:  41.805 ms/op
                 listUser·p0.9999: 44.630 ms/op
                 listUser·p1.00:   44.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9290
  mean =      3.448 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9046 
    [ 5.000, 10.000) = 148 
    [10.000, 15.000) = 5 
    [15.000, 20.000) = 56 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =     14.599 ms/op
     p(99.9000) =     41.805 ms/op
     p(99.9900) =     44.630 ms/op
     p(99.9990) =     44.630 ms/op
     p(99.9999) =     44.630 ms/op
    p(100.0000) =     44.630 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.448          ops/ms
ClientSimple.existUser                       thrpt         14.084          ops/ms
ClientSimple.getUser                         thrpt         13.780          ops/ms
ClientSimple.listUser                        thrpt          9.036          ops/ms
ClientSimple.createUser                       avgt          2.331           ms/op
ClientSimple.existUser                        avgt          2.083           ms/op
ClientSimple.getUser                          avgt          1.990           ms/op
ClientSimple.listUser                         avgt          3.577           ms/op
ClientSimple.createUser                     sample  14288   2.237 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.450           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.994           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.338           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.246           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.252           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.393           ms/op
ClientSimple.existUser                      sample  15883   2.010 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.710           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.001           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.166           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.945           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.526           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.584           ms/op
ClientSimple.getUser                        sample  14493   2.206 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.509           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.097           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.049           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.625           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.483           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.542           ms/op
ClientSimple.listUser                       sample   9290   3.448 ± 0.090   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.770           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.228           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample         14.599           ms/op
ClientSimple.listUser:listUser·p0.999       sample         41.805           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         44.630           ms/op
ClientSimple.listUser:listUser·p1.00        sample         44.630           ms/op

Benchmark result is saved to 1717653935369.json
