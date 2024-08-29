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
# Warmup Iteration   1: 1.812 ops/ms
Iteration   1: 7.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.504 ops/ms


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
# Warmup Iteration   1: 5.445 ops/ms
Iteration   1: 13.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.408 ops/ms


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
# Warmup Iteration   1: 5.152 ops/ms
Iteration   1: 13.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.891 ops/ms


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
# Warmup Iteration   1: 5.340 ops/ms
Iteration   1: 9.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.276 ops/ms


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.079 ms/op
Iteration   1: 2.321 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.321 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.055 ms/op
Iteration   1: 1.874 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.874 ms/op


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
# Warmup Iteration   1: 2.865 ±(99.9%) 0.055 ms/op
Iteration   1: 1.843 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.843 ms/op


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
# Warmup Iteration   1: 4.608 ±(99.9%) 0.075 ms/op
Iteration   1: 3.422 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.422 ms/op


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
# Warmup Iteration   1: 3.530 ±(99.9%) 0.092 ms/op
Iteration   1: 2.284 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   2.126 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   3.002 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  13.746 ms/op
                 createUser·p0.9999: 13.930 ms/op
                 createUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13994
  mean =      2.284 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 11788 
    [ 2.500,  3.750) = 1730 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     13.930 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.479 ±(99.9%) 0.091 ms/op
Iteration   1: 2.016 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   1.872 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.769 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  27.370 ms/op
                 existUser·p0.9999: 28.090 ms/op
                 existUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15862
  mean =      2.016 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14475 
    [ 2.500,  5.000) = 1221 
    [ 5.000,  7.500) = 102 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     27.370 ms/op
     p(99.9900) =     28.090 ms/op
     p(99.9990) =     28.148 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.080 ms/op
Iteration   1: 1.850 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   1.776 ms/op
                 getUser·p0.90:   2.208 ms/op
                 getUser·p0.95:   2.494 ms/op
                 getUser·p0.99:   3.068 ms/op
                 getUser·p0.999:  12.330 ms/op
                 getUser·p0.9999: 13.104 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17435
  mean =      1.850 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 16459 
    [ 2.500,  3.750) = 779 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.068 ms/op
     p(99.9000) =     12.330 ms/op
     p(99.9900) =     13.104 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 4.798 ±(99.9%) 0.140 ms/op
Iteration   1: 3.260 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.426 ms/op
                 listUser·p0.999:  23.599 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9817
  mean =      3.260 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1933 
    [ 2.500,  5.000) = 7635 
    [ 5.000,  7.500) = 198 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.426 ms/op
     p(99.9000) =     23.599 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.504          ops/ms
ClientSimple.existUser                       thrpt         13.408          ops/ms
ClientSimple.getUser                         thrpt         13.891          ops/ms
ClientSimple.listUser                        thrpt          9.276          ops/ms
ClientSimple.createUser                       avgt          2.321           ms/op
ClientSimple.existUser                        avgt          1.874           ms/op
ClientSimple.getUser                          avgt          1.843           ms/op
ClientSimple.listUser                         avgt          3.422           ms/op
ClientSimple.createUser                     sample  13994   2.284 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.653           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.126           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.002           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.111           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.746           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.930           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.943           ms/op
ClientSimple.existUser                      sample  15862   2.016 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.622           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.872           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.769           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.317           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.370           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.090           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.148           ms/op
ClientSimple.getUser                        sample  17435   1.850 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.925           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.776           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.208           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.068           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.330           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.104           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.189           ms/op
ClientSimple.listUser                       sample   9817   3.260 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.035           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.031           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.426           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.599           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.723           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.723           ms/op

Benchmark result is saved to 1724911578301.json
