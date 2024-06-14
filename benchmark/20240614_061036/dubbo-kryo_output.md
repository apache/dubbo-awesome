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
# Warmup Iteration   1: 1.562 ops/ms
Iteration   1: 5.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.925 ops/ms


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
# Warmup Iteration   1: 5.422 ops/ms
Iteration   1: 11.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.420 ops/ms


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
# Warmup Iteration   1: 6.031 ops/ms
Iteration   1: 12.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.881 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ops/ms
Iteration   1: 8.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.716 ops/ms


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
# Warmup Iteration   1: 4.107 ±(99.9%) 0.078 ms/op
Iteration   1: 2.020 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.020 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.072 ms/op
Iteration   1: 1.874 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.874 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.084 ms/op
Iteration   1: 2.199 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.199 ms/op


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.101 ms/op
Iteration   1: 3.211 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.211 ms/op


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
# Warmup Iteration   1: 3.651 ±(99.9%) 0.095 ms/op
Iteration   1: 2.325 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.834 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   5.019 ms/op
                 createUser·p0.999:  18.809 ms/op
                 createUser·p0.9999: 25.133 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13734
  mean =      2.325 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10221 
    [ 2.500,  5.000) = 3374 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      5.019 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 2.883 ±(99.9%) 0.066 ms/op
Iteration   1: 1.908 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.249 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.769 ms/op
                 existUser·p0.99:   10.846 ms/op
                 existUser·p0.999:  15.684 ms/op
                 existUser·p0.9999: 16.940 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16753
  mean =      1.908 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2858 
    [ 1.250,  2.500) = 12373 
    [ 2.500,  3.750) = 1047 
    [ 3.750,  5.000) = 141 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.249 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     15.684 ms/op
     p(99.9900) =     16.940 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.093 ms/op
Iteration   1: 2.257 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   2.154 ms/op
                 getUser·p0.90:   2.839 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.840 ms/op
                 getUser·p0.999:  14.921 ms/op
                 getUser·p0.9999: 15.490 ms/op
                 getUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14159
  mean =      2.257 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 10670 
    [ 2.500,  3.750) = 2945 
    [ 3.750,  5.000) = 265 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.840 ms/op
     p(99.9000) =     14.921 ms/op
     p(99.9900) =     15.490 ms/op
     p(99.9990) =     15.565 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 5.626 ±(99.9%) 0.164 ms/op
Iteration   1: 3.830 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   12.895 ms/op
                 listUser·p0.999:  20.236 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8364
  mean =      3.830 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 662 
    [ 2.500,  5.000) = 7226 
    [ 5.000,  7.500) = 297 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =     12.895 ms/op
     p(99.9000) =     20.236 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.925          ops/ms
ClientSimple.existUser                       thrpt         11.420          ops/ms
ClientSimple.getUser                         thrpt         12.881          ops/ms
ClientSimple.listUser                        thrpt          8.716          ops/ms
ClientSimple.createUser                       avgt          2.020           ms/op
ClientSimple.existUser                        avgt          1.874           ms/op
ClientSimple.getUser                          avgt          2.199           ms/op
ClientSimple.listUser                         avgt          3.211           ms/op
ClientSimple.createUser                     sample  13734   2.325 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.864           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.035           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.019           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.809           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.133           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.231           ms/op
ClientSimple.existUser                      sample  16753   1.908 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.249           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.681           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.769           ms/op
ClientSimple.existUser:existUser·p0.99      sample         10.846           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.684           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.940           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.007           ms/op
ClientSimple.getUser                        sample  14159   2.257 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.680           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.154           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.191           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.840           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.921           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.490           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.565           ms/op
ClientSimple.listUser                       sample   8364   3.830 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.979           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.678           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.087           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.895           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.236           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.234           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.234           ms/op

Benchmark result is saved to 1718345180235.json
