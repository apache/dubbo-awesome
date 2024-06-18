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
# Warmup Iteration   1: 2.119 ops/ms
Iteration   1: 7.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.675 ops/ms


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
# Warmup Iteration   1: 5.410 ops/ms
Iteration   1: 12.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.639 ops/ms


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
# Warmup Iteration   1: 6.678 ops/ms
Iteration   1: 14.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.025 ops/ms
Iteration   1: 8.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.573 ops/ms


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.088 ms/op
Iteration   1: 2.090 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.090 ms/op


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
# Warmup Iteration   1: 2.882 ±(99.9%) 0.047 ms/op
Iteration   1: 1.833 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.833 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.064 ms/op
Iteration   1: 2.048 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.048 ms/op


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.074 ms/op
Iteration   1: 3.001 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.001 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.077 ms/op
Iteration   1: 2.141 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   1.944 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.825 ms/op
                 createUser·p0.99:   3.918 ms/op
                 createUser·p0.999:  31.417 ms/op
                 createUser·p0.9999: 32.308 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15243
  mean =      2.141 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12827 
    [ 2.500,  5.000) = 2288 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.825 ms/op
     p(99.0000) =      3.918 ms/op
     p(99.9000) =     31.417 ms/op
     p(99.9900) =     32.308 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 3.019 ±(99.9%) 0.060 ms/op
Iteration   1: 1.708 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   1.599 ms/op
                 existUser·p0.90:   2.097 ms/op
                 existUser·p0.95:   2.257 ms/op
                 existUser·p0.99:   2.605 ms/op
                 existUser·p0.999:  15.799 ms/op
                 existUser·p0.9999: 16.550 ms/op
                 existUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18708
  mean =      1.708 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 18275 
    [ 2.500,  3.750) = 229 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      1.599 ms/op
     p(90.0000) =      2.097 ms/op
     p(95.0000) =      2.257 ms/op
     p(99.0000) =      2.605 ms/op
     p(99.9000) =     15.799 ms/op
     p(99.9900) =     16.550 ms/op
     p(99.9990) =     16.564 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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
# Warmup Iteration   1: 2.820 ±(99.9%) 0.069 ms/op
Iteration   1: 2.136 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   2.091 ms/op
                 getUser·p0.90:   2.699 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  16.482 ms/op
                 getUser·p0.9999: 17.007 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14964
  mean =      2.136 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 210 
    [ 1.250,  2.500) = 11885 
    [ 2.500,  3.750) = 2671 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.091 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.115 ms/op
Iteration   1: 3.225 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.698 ms/op
                 listUser·p0.999:  17.148 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9923
  mean =      3.225 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 879 
    [ 2.500,  3.750) = 6743 
    [ 3.750,  5.000) = 2119 
    [ 5.000,  6.250) = 116 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.698 ms/op
     p(99.9000) =     17.148 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.675          ops/ms
ClientSimple.existUser                       thrpt         12.639          ops/ms
ClientSimple.getUser                         thrpt         14.084          ops/ms
ClientSimple.listUser                        thrpt          8.573          ops/ms
ClientSimple.createUser                       avgt          2.090           ms/op
ClientSimple.existUser                        avgt          1.833           ms/op
ClientSimple.getUser                          avgt          2.048           ms/op
ClientSimple.listUser                         avgt          3.001           ms/op
ClientSimple.createUser                     sample  15243   2.141 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.633           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.944           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.825           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.918           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.417           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.308           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.342           ms/op
ClientSimple.existUser                      sample  18708   1.708 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.798           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.599           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.799           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.550           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.564           ms/op
ClientSimple.getUser                        sample  14964   2.136 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.647           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.091           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.309           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.482           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.007           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.039           ms/op
ClientSimple.listUser                       sample   9923   3.225 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.018           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.916           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.698           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.148           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.022           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.022           ms/op

Benchmark result is saved to 1718712390545.json
