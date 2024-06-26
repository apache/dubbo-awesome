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
# Warmup Iteration   1: 1.463 ops/ms
Iteration   1: 6.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.394 ops/ms


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
# Warmup Iteration   1: 5.605 ops/ms
Iteration   1: 11.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.577 ops/ms


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
# Warmup Iteration   1: 5.743 ops/ms
Iteration   1: 12.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.999 ops/ms


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
# Warmup Iteration   1: 5.148 ops/ms
Iteration   1: 7.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.699 ops/ms


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.085 ms/op
Iteration   1: 2.166 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.089 ±(99.9%) 0.045 ms/op
Iteration   1: 1.748 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.748 ms/op


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
# Warmup Iteration   1: 3.309 ±(99.9%) 0.067 ms/op
Iteration   1: 2.272 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.272 ms/op


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
# Warmup Iteration   1: 5.172 ±(99.9%) 0.102 ms/op
Iteration   1: 3.693 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.693 ms/op


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.095 ms/op
Iteration   1: 2.121 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   1.866 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   2.970 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  18.940 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15214
  mean =      2.121 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 12619 
    [ 2.500,  3.750) = 2252 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.219 ±(99.9%) 0.093 ms/op
Iteration   1: 1.921 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  16.564 ms/op
                 existUser·p0.9999: 16.723 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16624
  mean =      1.921 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 554 
    [ 1.250,  2.500) = 14802 
    [ 2.500,  3.750) = 992 
    [ 3.750,  5.000) = 145 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     16.723 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.099 ms/op
Iteration   1: 1.905 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   1.794 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   3.527 ms/op
                 getUser·p0.999:  15.172 ms/op
                 getUser·p0.9999: 15.558 ms/op
                 getUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16966
  mean =      1.905 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 555 
    [ 1.250,  2.500) = 14788 
    [ 2.500,  3.750) = 1501 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     15.558 ms/op
     p(99.9990) =     15.581 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 5.186 ±(99.9%) 0.175 ms/op
Iteration   1: 3.630 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.696 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.300 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8841
  mean =      3.630 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 630 
    [ 2.500,  3.750) = 4734 
    [ 3.750,  5.000) = 3146 
    [ 5.000,  6.250) = 215 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.394          ops/ms
ClientSimple.existUser                       thrpt         11.577          ops/ms
ClientSimple.getUser                         thrpt         12.999          ops/ms
ClientSimple.listUser                        thrpt          7.699          ops/ms
ClientSimple.createUser                       avgt          2.166           ms/op
ClientSimple.existUser                        avgt          1.748           ms/op
ClientSimple.getUser                          avgt          2.272           ms/op
ClientSimple.listUser                         avgt          3.693           ms/op
ClientSimple.createUser                     sample  15214   2.121 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.779           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.866           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.970           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.520           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.940           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.038           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.038           ms/op
ClientSimple.existUser                      sample  16624   1.921 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.719           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.637           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.564           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.723           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.777           ms/op
ClientSimple.getUser                        sample  16966   1.905 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.604           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.794           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.527           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.172           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.558           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.581           ms/op
ClientSimple.listUser                       sample   8841   3.630 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.696           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.617           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.300           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.629           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.859           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.859           ms/op

Benchmark result is saved to 1719403632898.json
