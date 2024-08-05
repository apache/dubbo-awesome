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
# Warmup Iteration   1: 1.795 ops/ms
Iteration   1: 6.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.375 ops/ms


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
# Warmup Iteration   1: 6.760 ops/ms
Iteration   1: 11.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.896 ops/ms


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
# Warmup Iteration   1: 5.273 ops/ms
Iteration   1: 12.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.648 ops/ms


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
# Warmup Iteration   1: 4.863 ops/ms
Iteration   1: 9.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.080 ops/ms


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.071 ms/op
Iteration   1: 2.044 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.044 ms/op


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
# Warmup Iteration   1: 3.123 ±(99.9%) 0.060 ms/op
Iteration   1: 2.027 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.027 ms/op


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
# Warmup Iteration   1: 2.877 ±(99.9%) 0.048 ms/op
Iteration   1: 1.879 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.879 ms/op


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
# Warmup Iteration   1: 5.173 ±(99.9%) 0.158 ms/op
Iteration   1: 3.565 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.565 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.076 ms/op
Iteration   1: 2.208 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   2.064 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  28.067 ms/op
                 createUser·p0.9999: 30.422 ms/op
                 createUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14473
  mean =      2.208 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12059 
    [ 2.500,  5.000) = 2219 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     28.067 ms/op
     p(99.9900) =     30.422 ms/op
     p(99.9990) =     30.540 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 2.955 ±(99.9%) 0.071 ms/op
Iteration   1: 1.876 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   1.700 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   4.484 ms/op
                 existUser·p0.999:  26.903 ms/op
                 existUser·p0.9999: 28.393 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17032
  mean =      1.876 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15950 
    [ 2.500,  5.000) = 938 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      4.484 ms/op
     p(99.9000) =     26.903 ms/op
     p(99.9900) =     28.393 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 3.373 ±(99.9%) 0.094 ms/op
Iteration   1: 1.817 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   1.683 ms/op
                 getUser·p0.90:   2.339 ms/op
                 getUser·p0.95:   2.564 ms/op
                 getUser·p0.99:   3.831 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 12.456 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17660
  mean =      1.817 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 723 
    [ 1.250,  2.500) = 15893 
    [ 2.500,  3.750) = 862 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 16 
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
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.831 ms/op
     p(99.9000) =     12.026 ms/op
     p(99.9900) =     12.456 ms/op
     p(99.9990) =     12.468 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


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
# Warmup Iteration   1: 4.953 ±(99.9%) 0.163 ms/op
Iteration   1: 3.622 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   5.832 ms/op
                 listUser·p0.999:  7.020 ms/op
                 listUser·p0.9999: 13.484 ms/op
                 listUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8825
  mean =      3.622 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 371 
    [ 2.500,  3.750) = 4903 
    [ 3.750,  5.000) = 3335 
    [ 5.000,  6.250) = 156 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.832 ms/op
     p(99.9000) =      7.020 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.375          ops/ms
ClientSimple.existUser                       thrpt         11.896          ops/ms
ClientSimple.getUser                         thrpt         12.648          ops/ms
ClientSimple.listUser                        thrpt          9.080          ops/ms
ClientSimple.createUser                       avgt          2.044           ms/op
ClientSimple.existUser                        avgt          2.027           ms/op
ClientSimple.getUser                          avgt          1.879           ms/op
ClientSimple.listUser                         avgt          3.565           ms/op
ClientSimple.createUser                     sample  14473   2.208 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.597           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.064           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.759           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.067           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.422           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.540           ms/op
ClientSimple.existUser                      sample  17032   1.876 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.528           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.700           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.484           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.903           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.393           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.508           ms/op
ClientSimple.getUser                        sample  17660   1.817 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.670           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.683           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.831           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.026           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.456           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.468           ms/op
ClientSimple.listUser                       sample   8825   3.622 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.208           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.621           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.832           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.020           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.484           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.484           ms/op

Benchmark result is saved to 1722881124770.json
