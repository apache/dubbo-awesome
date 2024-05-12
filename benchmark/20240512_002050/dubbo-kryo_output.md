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
# Warmup Iteration   1: 1.711 ops/ms
Iteration   1: 7.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.084 ops/ms


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
# Warmup Iteration   1: 6.220 ops/ms
Iteration   1: 14.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.319 ops/ms


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
# Warmup Iteration   1: 5.706 ops/ms
Iteration   1: 13.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.921 ops/ms


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
# Warmup Iteration   1: 4.949 ops/ms
Iteration   1: 9.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.447 ops/ms


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.073 ms/op
Iteration   1: 2.034 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.034 ms/op


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
# Warmup Iteration   1: 2.964 ±(99.9%) 0.049 ms/op
Iteration   1: 1.945 ±(99.9%) 0.005 ms/op


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
# Warmup Iteration   1: 3.129 ±(99.9%) 0.055 ms/op
Iteration   1: 1.758 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.758 ms/op


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
# Warmup Iteration   1: 4.439 ±(99.9%) 0.097 ms/op
Iteration   1: 3.373 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.373 ms/op


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.088 ms/op
Iteration   1: 2.158 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.001 ms/op
                 createUser·p0.90:   2.580 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   10.584 ms/op
                 createUser·p0.999:  14.942 ms/op
                 createUser·p0.9999: 16.466 ms/op
                 createUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14808
  mean =      2.158 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 12884 
    [ 2.500,  3.750) = 1555 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     16.466 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


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
# Warmup Iteration   1: 2.976 ±(99.9%) 0.064 ms/op
Iteration   1: 2.054 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   1.978 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.354 ms/op
                 existUser·p0.999:  24.750 ms/op
                 existUser·p0.9999: 25.785 ms/op
                 existUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15559
  mean =      2.054 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14486 
    [ 2.500,  5.000) = 975 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.354 ms/op
     p(99.9000) =     24.750 ms/op
     p(99.9900) =     25.785 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 3.292 ±(99.9%) 0.084 ms/op
Iteration   1: 1.934 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   1.815 ms/op
                 getUser·p0.90:   2.437 ms/op
                 getUser·p0.95:   2.646 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  11.034 ms/op
                 getUser·p0.9999: 11.163 ms/op
                 getUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16542
  mean =      1.934 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 291 
    [ 1.250,  2.500) = 14882 
    [ 2.500,  3.750) = 1196 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =     11.034 ms/op
     p(99.9900) =     11.163 ms/op
     p(99.9990) =     11.174 ms/op
     p(99.9999) =     11.174 ms/op
    p(100.0000) =     11.174 ms/op


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.119 ms/op
Iteration   1: 3.268 ±(99.9%) 0.103 ms/op
                 listUser·p0.00:   0.477 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.193 ms/op
                 listUser·p0.999:  54.016 ms/op
                 listUser·p0.9999: 72.090 ms/op
                 listUser·p1.00:   72.090 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9784
  mean =      3.268 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9568 
    [ 5.000, 10.000) = 152 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 26 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 4 
    [65.000, 70.000) = 1 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     54.016 ms/op
     p(99.9900) =     72.090 ms/op
     p(99.9990) =     72.090 ms/op
     p(99.9999) =     72.090 ms/op
    p(100.0000) =     72.090 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.084          ops/ms
ClientSimple.existUser                       thrpt         14.319          ops/ms
ClientSimple.getUser                         thrpt         13.921          ops/ms
ClientSimple.listUser                        thrpt          9.447          ops/ms
ClientSimple.createUser                       avgt          2.034           ms/op
ClientSimple.existUser                        avgt          1.945           ms/op
ClientSimple.getUser                          avgt          1.758           ms/op
ClientSimple.listUser                         avgt          3.373           ms/op
ClientSimple.createUser                     sample  14808   2.158 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.708           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.001           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.580           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.584           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.942           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.466           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.466           ms/op
ClientSimple.existUser                      sample  15559   2.054 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.686           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.978           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.354           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.750           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.785           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.821           ms/op
ClientSimple.getUser                        sample  16542   1.934 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.623           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.815           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.010           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.034           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.163           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.174           ms/op
ClientSimple.listUser                       sample   9784   3.268 ± 0.103   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.477           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.904           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.854           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.193           ms/op
ClientSimple.listUser:listUser·p0.999       sample         54.016           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         72.090           ms/op
ClientSimple.listUser:listUser·p1.00        sample         72.090           ms/op

Benchmark result is saved to 1715473003197.json
