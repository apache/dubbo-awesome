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
# Warmup Iteration   1: 1.534 ops/ms
Iteration   1: 7.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.180 ops/ms


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
# Warmup Iteration   1: 5.889 ops/ms
Iteration   1: 13.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.361 ops/ms


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
# Warmup Iteration   1: 5.035 ops/ms
Iteration   1: 13.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.373 ops/ms


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
# Warmup Iteration   1: 4.420 ops/ms
Iteration   1: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.856 ops/ms


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.063 ms/op
Iteration   1: 2.617 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.617 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.049 ms/op
Iteration   1: 1.919 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.919 ms/op


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
# Warmup Iteration   1: 3.332 ±(99.9%) 0.060 ms/op
Iteration   1: 1.959 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.959 ms/op


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.091 ms/op
Iteration   1: 3.118 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.118 ms/op


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.128 ms/op
Iteration   1: 2.390 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   1.927 ms/op
                 createUser·p0.90:   2.822 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   13.402 ms/op
                 createUser·p0.999:  20.554 ms/op
                 createUser·p0.9999: 23.976 ms/op
                 createUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13373
  mean =      2.390 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10613 
    [ 2.500,  5.000) = 2210 
    [ 5.000,  7.500) = 132 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.927 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =     13.402 ms/op
     p(99.9000) =     20.554 ms/op
     p(99.9900) =     23.976 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 2.924 ±(99.9%) 0.057 ms/op
Iteration   1: 1.933 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.336 ms/op
                 existUser·p0.50:   1.726 ms/op
                 existUser·p0.90:   2.444 ms/op
                 existUser·p0.95:   2.699 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  26.739 ms/op
                 existUser·p0.9999: 27.197 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16591
  mean =      1.933 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15188 
    [ 2.500,  5.000) = 1306 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.444 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =     26.739 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.082 ms/op
Iteration   1: 1.933 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.493 ms/op
                 getUser·p0.50:   1.808 ms/op
                 getUser·p0.90:   2.437 ms/op
                 getUser·p0.95:   2.630 ms/op
                 getUser·p0.99:   2.948 ms/op
                 getUser·p0.999:  13.849 ms/op
                 getUser·p0.9999: 14.052 ms/op
                 getUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16721
  mean =      1.933 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 15247 
    [ 2.500,  3.750) = 1204 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      2.948 ms/op
     p(99.9000) =     13.849 ms/op
     p(99.9900) =     14.052 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.123 ms/op
Iteration   1: 3.225 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.283 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 15.041 ms/op
                 listUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9921
  mean =      3.225 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 390 
    [ 2.500,  3.750) = 7787 
    [ 3.750,  5.000) = 1481 
    [ 5.000,  6.250) = 158 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     15.041 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.180          ops/ms
ClientSimple.existUser                       thrpt         13.361          ops/ms
ClientSimple.getUser                         thrpt         13.373          ops/ms
ClientSimple.listUser                        thrpt          9.856          ops/ms
ClientSimple.createUser                       avgt          2.617           ms/op
ClientSimple.existUser                        avgt          1.919           ms/op
ClientSimple.getUser                          avgt          1.959           ms/op
ClientSimple.listUser                         avgt          3.118           ms/op
ClientSimple.createUser                     sample  13373   2.390 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.564           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.927           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.407           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.402           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.554           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.976           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.805           ms/op
ClientSimple.existUser                      sample  16591   1.933 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.336           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.726           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.444           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.834           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.739           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.197           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.197           ms/op
ClientSimple.getUser                        sample  16721   1.933 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.493           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.808           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.948           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.849           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.052           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.107           ms/op
ClientSimple.listUser                       sample   9921   3.225 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.763           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.957           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.121           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.283           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.959           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.041           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.041           ms/op

Benchmark result is saved to 1714954540781.json
