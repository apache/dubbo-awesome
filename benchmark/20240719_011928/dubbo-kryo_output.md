# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.756 ops/ms
Iteration   1: 7.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.764 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.448 ops/ms
Iteration   1: 14.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.025 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.879 ops/ms
Iteration   1: 12.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.417 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.318 ops/ms
Iteration   1: 8.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.485 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.997 ±(99.9%) 0.068 ms/op
Iteration   1: 2.407 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.407 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.036 ±(99.9%) 0.052 ms/op
Iteration   1: 2.128 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.128 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.333 ±(99.9%) 0.051 ms/op
Iteration   1: 2.108 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.108 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.540 ±(99.9%) 0.090 ms/op
Iteration   1: 3.410 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.805 ±(99.9%) 0.127 ms/op
Iteration   1: 2.027 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.288 ms/op
                 createUser·p0.50:   1.925 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.859 ms/op
                 createUser·p0.99:   6.867 ms/op
                 createUser·p0.999:  12.141 ms/op
                 createUser·p0.9999: 13.064 ms/op
                 createUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15786
  mean =      2.027 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 437 
    [ 1.250,  2.500) = 13649 
    [ 2.500,  3.750) = 1431 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      6.867 ms/op
     p(99.9000) =     12.141 ms/op
     p(99.9900) =     13.064 ms/op
     p(99.9990) =     13.320 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.062 ±(99.9%) 0.070 ms/op
Iteration   1: 1.789 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   1.978 ms/op
                 existUser·p0.95:   2.200 ms/op
                 existUser·p0.99:   3.462 ms/op
                 existUser·p0.999:  13.910 ms/op
                 existUser·p0.9999: 14.689 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17859
  mean =      1.789 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 17411 
    [ 2.500,  3.750) = 153 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      1.978 ms/op
     p(95.0000) =      2.200 ms/op
     p(99.0000) =      3.462 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     14.689 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.178 ±(99.9%) 0.072 ms/op
Iteration   1: 2.038 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   1.831 ms/op
                 getUser·p0.90:   2.511 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   3.983 ms/op
                 getUser·p0.999:  18.940 ms/op
                 getUser·p0.9999: 20.172 ms/op
                 getUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15694
  mean =      2.038 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14070 
    [ 2.500,  5.000) = 1482 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      3.983 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     20.172 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ±(99.9%) 0.134 ms/op
Iteration   1: 3.312 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.229 ms/op
                 listUser·p0.999:  15.527 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9657
  mean =      3.312 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1841 
    [ 2.500,  3.750) = 4997 
    [ 3.750,  5.000) = 2426 
    [ 5.000,  6.250) = 245 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.229 ms/op
     p(99.9000) =     15.527 ms/op
     p(99.9900) =     16.286 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.764          ops/ms
ClientSimple.existUser                       thrpt         14.025          ops/ms
ClientSimple.getUser                         thrpt         12.417          ops/ms
ClientSimple.listUser                        thrpt          8.485          ops/ms
ClientSimple.createUser                       avgt          2.407           ms/op
ClientSimple.existUser                        avgt          2.128           ms/op
ClientSimple.getUser                          avgt          2.108           ms/op
ClientSimple.listUser                         avgt          3.410           ms/op
ClientSimple.createUser                     sample  15786   2.027 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.288           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.925           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.859           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.867           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.141           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.064           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.320           ms/op
ClientSimple.existUser                      sample  17859   1.789 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.829           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.702           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.978           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.462           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.910           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.689           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.844           ms/op
ClientSimple.getUser                        sample  15694   2.038 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.781           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.831           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.983           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.940           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.172           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.414           ms/op
ClientSimple.listUser                       sample   9657   3.312 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.017           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.912           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.229           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.527           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.286           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.286           ms/op

Benchmark result is saved to 1721351482288.json
