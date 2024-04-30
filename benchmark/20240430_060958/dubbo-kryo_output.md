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
# Warmup Iteration   1: 1.964 ops/ms
Iteration   1: 6.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.848 ops/ms


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
# Warmup Iteration   1: 5.443 ops/ms
Iteration   1: 12.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.642 ops/ms


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
# Warmup Iteration   1: 6.028 ops/ms
Iteration   1: 11.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.719 ops/ms


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
# Warmup Iteration   1: 4.705 ops/ms
Iteration   1: 8.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.213 ops/ms


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.068 ms/op
Iteration   1: 2.189 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.189 ms/op


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
# Warmup Iteration   1: 2.838 ±(99.9%) 0.052 ms/op
Iteration   1: 1.895 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.895 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.053 ms/op
Iteration   1: 2.060 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.060 ms/op


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
# Warmup Iteration   1: 5.015 ±(99.9%) 0.124 ms/op
Iteration   1: 3.236 ±(99.9%) 0.015 ms/op


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
# Warmup Iteration   1: 3.415 ±(99.9%) 0.078 ms/op
Iteration   1: 2.220 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   1.968 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   9.340 ms/op
                 createUser·p0.999:  27.250 ms/op
                 createUser·p0.9999: 28.233 ms/op
                 createUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14393
  mean =      2.220 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12857 
    [ 2.500,  5.000) = 1299 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      9.340 ms/op
     p(99.9000) =     27.250 ms/op
     p(99.9900) =     28.233 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 2.929 ±(99.9%) 0.069 ms/op
Iteration   1: 1.827 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   3.292 ms/op
                 existUser·p0.999:  16.794 ms/op
                 existUser·p0.9999: 17.220 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17483
  mean =      1.827 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 278 
    [ 1.250,  2.500) = 16611 
    [ 2.500,  3.750) = 463 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      3.292 ms/op
     p(99.9000) =     16.794 ms/op
     p(99.9900) =     17.220 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 3.127 ±(99.9%) 0.072 ms/op
Iteration   1: 1.940 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   1.849 ms/op
                 getUser·p0.90:   2.413 ms/op
                 getUser·p0.95:   2.621 ms/op
                 getUser·p0.99:   3.186 ms/op
                 getUser·p0.999:  16.843 ms/op
                 getUser·p0.9999: 18.068 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16509
  mean =      1.940 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 395 
    [ 1.250,  2.500) = 14912 
    [ 2.500,  3.750) = 1086 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.186 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     18.068 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.364 ±(99.9%) 0.113 ms/op
Iteration   1: 3.840 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  8.858 ms/op
                 listUser·p0.9999: 9.896 ms/op
                 listUser·p1.00:   9.896 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8336
  mean =      3.840 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 13 
    [ 1.500,  2.000) = 129 
    [ 2.000,  2.500) = 471 
    [ 2.500,  3.000) = 567 
    [ 3.000,  3.500) = 1110 
    [ 3.500,  4.000) = 2521 
    [ 4.000,  4.500) = 2125 
    [ 4.500,  5.000) = 939 
    [ 5.000,  5.500) = 305 
    [ 5.500,  6.000) = 84 
    [ 6.000,  6.500) = 40 
    [ 6.500,  7.000) = 16 
    [ 7.000,  7.500) = 3 
    [ 7.500,  8.000) = 1 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 9 
    [ 9.000,  9.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =      8.858 ms/op
     p(99.9900) =      9.896 ms/op
     p(99.9990) =      9.896 ms/op
     p(99.9999) =      9.896 ms/op
    p(100.0000) =      9.896 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.848          ops/ms
ClientSimple.existUser                       thrpt         12.642          ops/ms
ClientSimple.getUser                         thrpt         11.719          ops/ms
ClientSimple.listUser                        thrpt          8.213          ops/ms
ClientSimple.createUser                       avgt          2.189           ms/op
ClientSimple.existUser                        avgt          1.895           ms/op
ClientSimple.getUser                          avgt          2.060           ms/op
ClientSimple.listUser                         avgt          3.236           ms/op
ClientSimple.createUser                     sample  14393   2.220 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.659           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.968           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.340           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.250           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.233           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.377           ms/op
ClientSimple.existUser                      sample  17483   1.827 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.551           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.292           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.794           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.220           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.367           ms/op
ClientSimple.getUser                        sample  16509   1.940 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.821           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.849           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.186           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.843           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.068           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.153           ms/op
ClientSimple.listUser                       sample   8336   3.840 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.096           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.891           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.079           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.898           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.858           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.896           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.896           ms/op

Benchmark result is saved to 1714457118902.json
