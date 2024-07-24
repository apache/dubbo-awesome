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
# Warmup Iteration   1: 1.006 ops/ms
Iteration   1: 6.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.369 ops/ms


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
# Warmup Iteration   1: 5.737 ops/ms
Iteration   1: 12.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.072 ops/ms


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
# Warmup Iteration   1: 6.023 ops/ms
Iteration   1: 13.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.850 ops/ms


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
# Warmup Iteration   1: 5.378 ops/ms
Iteration   1: 8.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.569 ops/ms


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.069 ms/op
Iteration   1: 2.256 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.256 ms/op


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
# Warmup Iteration   1: 2.915 ±(99.9%) 0.040 ms/op
Iteration   1: 1.714 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.714 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.053 ms/op
Iteration   1: 1.985 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.985 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.075 ms/op
Iteration   1: 3.613 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.613 ms/op


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
# Warmup Iteration   1: 3.396 ±(99.9%) 0.079 ms/op
Iteration   1: 2.314 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   0.480 ms/op
                 createUser·p0.50:   2.058 ms/op
                 createUser·p0.90:   2.689 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   5.960 ms/op
                 createUser·p0.999:  46.739 ms/op
                 createUser·p0.9999: 49.292 ms/op
                 createUser·p1.00:   50.070 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13824
  mean =      2.314 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13626 
    [ 5.000, 10.000) = 68 
    [10.000, 15.000) = 65 
    [15.000, 20.000) = 30 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 31 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.689 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      5.960 ms/op
     p(99.9000) =     46.739 ms/op
     p(99.9900) =     49.292 ms/op
     p(99.9990) =     50.070 ms/op
     p(99.9999) =     50.070 ms/op
    p(100.0000) =     50.070 ms/op


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
# Warmup Iteration   1: 3.127 ±(99.9%) 0.077 ms/op
Iteration   1: 1.867 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.763 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  14.015 ms/op
                 existUser·p0.9999: 14.395 ms/op
                 existUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17290
  mean =      1.867 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 605 
    [ 1.250,  2.500) = 15227 
    [ 2.500,  3.750) = 1372 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.763 ms/op
     p(99.0000) =      3.449 ms/op
     p(99.9000) =     14.015 ms/op
     p(99.9900) =     14.395 ms/op
     p(99.9990) =     14.467 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.417 ±(99.9%) 0.097 ms/op
Iteration   1: 2.027 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   1.841 ms/op
                 getUser·p0.90:   2.658 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   5.524 ms/op
                 getUser·p0.999:  27.901 ms/op
                 getUser·p0.9999: 28.320 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15763
  mean =      2.027 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13226 
    [ 2.500,  5.000) = 2376 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.524 ms/op
     p(99.9000) =     27.901 ms/op
     p(99.9900) =     28.320 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 5.045 ±(99.9%) 0.159 ms/op
Iteration   1: 3.420 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.260 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.608 ms/op
                 listUser·p0.99:   6.115 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9350
  mean =      3.420 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 193 
    [ 2.500,  3.750) = 6785 
    [ 3.750,  5.000) = 2033 
    [ 5.000,  6.250) = 251 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.608 ms/op
     p(99.0000) =      6.115 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.369          ops/ms
ClientSimple.existUser                       thrpt         12.072          ops/ms
ClientSimple.getUser                         thrpt         13.850          ops/ms
ClientSimple.listUser                        thrpt          8.569          ops/ms
ClientSimple.createUser                       avgt          2.256           ms/op
ClientSimple.existUser                        avgt          1.714           ms/op
ClientSimple.getUser                          avgt          1.985           ms/op
ClientSimple.listUser                         avgt          3.613           ms/op
ClientSimple.createUser                     sample  13824   2.314 ± 0.068   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.480           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.058           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.689           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.960           ms/op
ClientSimple.createUser:createUser·p0.999   sample         46.739           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         49.292           ms/op
ClientSimple.createUser:createUser·p1.00    sample         50.070           ms/op
ClientSimple.existUser                      sample  17290   1.867 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.523           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.763           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.449           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.015           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.395           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.467           ms/op
ClientSimple.getUser                        sample  15763   2.027 ± 0.041   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.606           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.841           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.524           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.901           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.320           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.377           ms/op
ClientSimple.listUser                       sample   9350   3.420 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.122           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.260           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.178           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.608           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.115           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.416           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.514           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.514           ms/op

Benchmark result is saved to 1721801148264.json
