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
# Warmup Iteration   1: 1.418 ops/ms
Iteration   1: 6.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.992 ops/ms


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
# Warmup Iteration   1: 6.318 ops/ms
Iteration   1: 12.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.636 ops/ms


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
# Warmup Iteration   1: 7.025 ops/ms
Iteration   1: 14.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.190 ops/ms


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
# Warmup Iteration   1: 5.172 ops/ms
Iteration   1: 9.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.557 ops/ms


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.071 ms/op
Iteration   1: 2.307 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.307 ms/op


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
# Warmup Iteration   1: 2.803 ±(99.9%) 0.040 ms/op
Iteration   1: 1.852 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.852 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.049 ms/op
Iteration   1: 2.223 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.223 ms/op


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
# Warmup Iteration   1: 4.553 ±(99.9%) 0.094 ms/op
Iteration   1: 3.139 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.139 ms/op


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.125 ms/op
Iteration   1: 2.305 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   2.134 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.465 ms/op
                 createUser·p0.99:   4.058 ms/op
                 createUser·p0.999:  11.815 ms/op
                 createUser·p0.9999: 12.040 ms/op
                 createUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13863
  mean =      2.305 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 9887 
    [ 2.500,  3.750) = 3697 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      4.058 ms/op
     p(99.9000) =     11.815 ms/op
     p(99.9900) =     12.040 ms/op
     p(99.9990) =     12.059 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


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
# Warmup Iteration   1: 2.943 ±(99.9%) 0.062 ms/op
Iteration   1: 1.852 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.283 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.189 ms/op
                 existUser·p0.999:  19.743 ms/op
                 existUser·p0.9999: 20.414 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17252
  mean =      1.852 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16421 
    [ 2.500,  5.000) = 763 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.283 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.189 ms/op
     p(99.9000) =     19.743 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.077 ms/op
Iteration   1: 1.855 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.386 ms/op
                 getUser·p0.50:   1.698 ms/op
                 getUser·p0.90:   2.355 ms/op
                 getUser·p0.95:   2.516 ms/op
                 getUser·p0.99:   4.586 ms/op
                 getUser·p0.999:  15.413 ms/op
                 getUser·p0.9999: 16.387 ms/op
                 getUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17253
  mean =      1.855 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 437 
    [ 1.250,  2.500) = 15895 
    [ 2.500,  3.750) = 743 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.516 ms/op
     p(99.0000) =      4.586 ms/op
     p(99.9000) =     15.413 ms/op
     p(99.9900) =     16.387 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 4.122 ±(99.9%) 0.111 ms/op
Iteration   1: 3.099 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.761 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  20.175 ms/op
                 listUser·p0.9999: 20.965 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10315
  mean =      3.099 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1082 
    [ 2.500,  5.000) = 9047 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     20.175 ms/op
     p(99.9900) =     20.965 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.992          ops/ms
ClientSimple.existUser                       thrpt         12.636          ops/ms
ClientSimple.getUser                         thrpt         14.190          ops/ms
ClientSimple.listUser                        thrpt          9.557          ops/ms
ClientSimple.createUser                       avgt          2.307           ms/op
ClientSimple.existUser                        avgt          1.852           ms/op
ClientSimple.getUser                          avgt          2.223           ms/op
ClientSimple.listUser                         avgt          3.139           ms/op
ClientSimple.createUser                     sample  13863   2.305 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.622           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.134           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.273           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.465           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.058           ms/op
ClientSimple.createUser:createUser·p0.999   sample         11.815           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.040           ms/op
ClientSimple.createUser:createUser·p1.00    sample         12.059           ms/op
ClientSimple.existUser                      sample  17252   1.852 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.283           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.189           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.743           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.414           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.414           ms/op
ClientSimple.getUser                        sample  17253   1.855 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.386           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.698           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.516           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.586           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.413           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.387           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.482           ms/op
ClientSimple.listUser                       sample  10315   3.099 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.893           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.761           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.965           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.824           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.175           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.965           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.972           ms/op

Benchmark result is saved to 1714306023844.json
