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
# Warmup Iteration   1: 2.130 ops/ms
Iteration   1: 7.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.521 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.029 ops/ms
Iteration   1: 10.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.821 ops/ms


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
# Warmup Iteration   1: 6.609 ops/ms
Iteration   1: 14.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.413 ops/ms


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
# Warmup Iteration   1: 4.778 ops/ms
Iteration   1: 8.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.176 ops/ms


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.082 ms/op
Iteration   1: 2.276 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.276 ms/op


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.058 ms/op
Iteration   1: 2.096 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.096 ms/op


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
# Warmup Iteration   1: 3.271 ±(99.9%) 0.048 ms/op
Iteration   1: 2.050 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.050 ms/op


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.093 ms/op
Iteration   1: 3.266 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.266 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.096 ms/op
Iteration   1: 2.076 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   0.425 ms/op
                 createUser·p0.50:   1.722 ms/op
                 createUser·p0.90:   2.466 ms/op
                 createUser·p0.95:   2.679 ms/op
                 createUser·p0.99:   10.781 ms/op
                 createUser·p0.999:  44.106 ms/op
                 createUser·p0.9999: 44.791 ms/op
                 createUser·p1.00:   44.827 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15397
  mean =      2.076 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15070 
    [ 5.000, 10.000) = 146 
    [10.000, 15.000) = 124 
    [15.000, 20.000) = 25 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     44.106 ms/op
     p(99.9900) =     44.791 ms/op
     p(99.9990) =     44.827 ms/op
     p(99.9999) =     44.827 ms/op
    p(100.0000) =     44.827 ms/op


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
# Warmup Iteration   1: 2.970 ±(99.9%) 0.061 ms/op
Iteration   1: 1.945 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.429 ms/op
                 existUser·p0.50:   1.886 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   4.298 ms/op
                 existUser·p0.999:  9.807 ms/op
                 existUser·p0.9999: 11.095 ms/op
                 existUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16435
  mean =      1.945 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 616 
    [ 1.250,  2.500) = 14506 
    [ 2.500,  3.750) = 1083 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      4.298 ms/op
     p(99.9000) =      9.807 ms/op
     p(99.9900) =     11.095 ms/op
     p(99.9990) =     11.190 ms/op
     p(99.9999) =     11.190 ms/op
    p(100.0000) =     11.190 ms/op


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
# Warmup Iteration   1: 3.481 ±(99.9%) 0.095 ms/op
Iteration   1: 2.039 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   1.847 ms/op
                 getUser·p0.90:   2.675 ms/op
                 getUser·p0.95:   2.949 ms/op
                 getUser·p0.99:   3.396 ms/op
                 getUser·p0.999:  11.141 ms/op
                 getUser·p0.9999: 11.392 ms/op
                 getUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15688
  mean =      2.039 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 200 
    [ 1.250,  2.500) = 13282 
    [ 2.500,  3.750) = 2113 
    [ 3.750,  5.000) = 16 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      3.396 ms/op
     p(99.9000) =     11.141 ms/op
     p(99.9900) =     11.392 ms/op
     p(99.9990) =     11.420 ms/op
     p(99.9999) =     11.420 ms/op
    p(100.0000) =     11.420 ms/op


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.125 ms/op
Iteration   1: 3.488 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.291 ms/op
                 listUser·p0.999:  15.775 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9178
  mean =      3.488 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 753 
    [ 2.500,  3.750) = 5330 
    [ 3.750,  5.000) = 2779 
    [ 5.000,  6.250) = 211 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     15.775 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.521          ops/ms
ClientSimple.existUser                       thrpt         10.821          ops/ms
ClientSimple.getUser                         thrpt         14.413          ops/ms
ClientSimple.listUser                        thrpt          8.176          ops/ms
ClientSimple.createUser                       avgt          2.276           ms/op
ClientSimple.existUser                        avgt          2.096           ms/op
ClientSimple.getUser                          avgt          2.050           ms/op
ClientSimple.listUser                         avgt          3.266           ms/op
ClientSimple.createUser                     sample  15397   2.076 ± 0.060   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.425           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.722           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.466           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.781           ms/op
ClientSimple.createUser:createUser·p0.999   sample         44.106           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         44.791           ms/op
ClientSimple.createUser:createUser·p1.00    sample         44.827           ms/op
ClientSimple.existUser                      sample  16435   1.945 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.429           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.886           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.298           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.807           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.095           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.190           ms/op
ClientSimple.getUser                        sample  15688   2.039 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.778           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.847           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.396           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.141           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.392           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.420           ms/op
ClientSimple.listUser                       sample   9178   3.488 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.925           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.518           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.291           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.775           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.843           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.843           ms/op

Benchmark result is saved to 1722837976635.json
