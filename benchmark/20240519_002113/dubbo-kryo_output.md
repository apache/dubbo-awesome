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
# Warmup Iteration   1: 2.021 ops/ms
Iteration   1: 8.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.835 ops/ms


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
# Warmup Iteration   1: 5.554 ops/ms
Iteration   1: 11.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.568 ops/ms


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
# Warmup Iteration   1: 5.254 ops/ms
Iteration   1: 11.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.671 ops/ms


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
# Warmup Iteration   1: 4.859 ops/ms
Iteration   1: 9.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.199 ops/ms


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.074 ms/op
Iteration   1: 2.101 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.101 ms/op


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
# Warmup Iteration   1: 3.049 ±(99.9%) 0.052 ms/op
Iteration   1: 1.913 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.913 ms/op


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
# Warmup Iteration   1: 3.520 ±(99.9%) 0.053 ms/op
Iteration   1: 2.116 ±(99.9%) 0.006 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ±(99.9%) 0.103 ms/op
Iteration   1: 3.096 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.096 ms/op


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
# Warmup Iteration   1: 3.575 ±(99.9%) 0.092 ms/op
Iteration   1: 2.321 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   2.040 ms/op
                 createUser·p0.90:   2.580 ms/op
                 createUser·p0.95:   2.785 ms/op
                 createUser·p0.99:   12.288 ms/op
                 createUser·p0.999:  23.855 ms/op
                 createUser·p0.9999: 35.305 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13909
  mean =      2.321 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12054 
    [ 2.500,  5.000) = 1608 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     35.305 ms/op
     p(99.9990) =     36.766 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 2.911 ±(99.9%) 0.095 ms/op
Iteration   1: 1.950 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.544 ms/op
                 existUser·p0.99:   5.126 ms/op
                 existUser·p0.999:  20.120 ms/op
                 existUser·p0.9999: 20.197 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16389
  mean =      1.950 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15492 
    [ 2.500,  5.000) = 732 
    [ 5.000,  7.500) = 101 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      5.126 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     20.197 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 3.005 ±(99.9%) 0.070 ms/op
Iteration   1: 1.920 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   1.786 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.646 ms/op
                 getUser·p0.99:   4.270 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 12.348 ms/op
                 getUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16674
  mean =      1.920 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 15227 
    [ 2.500,  3.750) = 1040 
    [ 3.750,  5.000) = 141 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      4.270 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     12.348 ms/op
     p(99.9990) =     12.370 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


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
# Warmup Iteration   1: 4.844 ±(99.9%) 0.193 ms/op
Iteration   1: 3.955 ±(99.9%) 0.066 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  24.113 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8127
  mean =      3.955 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 407 
    [ 2.500,  5.000) = 7321 
    [ 5.000,  7.500) = 334 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     24.113 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.835          ops/ms
ClientSimple.existUser                       thrpt         11.568          ops/ms
ClientSimple.getUser                         thrpt         11.671          ops/ms
ClientSimple.listUser                        thrpt          9.199          ops/ms
ClientSimple.createUser                       avgt          2.101           ms/op
ClientSimple.existUser                        avgt          1.913           ms/op
ClientSimple.getUser                          avgt          2.116           ms/op
ClientSimple.listUser                         avgt          3.096           ms/op
ClientSimple.createUser                     sample  13909   2.321 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.644           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.040           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.580           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.785           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.288           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.855           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.305           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.766           ms/op
ClientSimple.existUser                      sample  16389   1.950 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.898           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.772           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.126           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.120           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.197           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.218           ms/op
ClientSimple.getUser                        sample  16674   1.920 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.700           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.786           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.270           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.075           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.348           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.370           ms/op
ClientSimple.listUser                       sample   8127   3.955 ± 0.066   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.047           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.826           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.997           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.143           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.113           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.248           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.248           ms/op

Benchmark result is saved to 1716077812535.json
