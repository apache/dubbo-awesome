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
# Warmup Iteration   1: 1.647 ops/ms
Iteration   1: 6.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.419 ops/ms


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
# Warmup Iteration   1: 5.763 ops/ms
Iteration   1: 13.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.017 ops/ms


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
# Warmup Iteration   1: 4.859 ops/ms
Iteration   1: 11.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.948 ops/ms


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
# Warmup Iteration   1: 4.418 ops/ms
Iteration   1: 8.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.519 ops/ms


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.064 ms/op
Iteration   1: 2.482 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.482 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.049 ms/op
Iteration   1: 1.758 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.758 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.064 ms/op
Iteration   1: 2.085 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.085 ms/op


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
# Warmup Iteration   1: 5.208 ±(99.9%) 0.113 ms/op
Iteration   1: 3.660 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.660 ms/op


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.123 ms/op
Iteration   1: 2.281 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.388 ms/op
                 createUser·p0.50:   2.089 ms/op
                 createUser·p0.90:   2.933 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   7.072 ms/op
                 createUser·p0.999:  23.322 ms/op
                 createUser·p0.9999: 26.083 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14067
  mean =      2.281 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10392 
    [ 2.500,  5.000) = 3332 
    [ 5.000,  7.500) = 232 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      7.072 ms/op
     p(99.9000) =     23.322 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 3.083 ±(99.9%) 0.072 ms/op
Iteration   1: 2.004 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   1.843 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.896 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  14.062 ms/op
                 existUser·p0.9999: 14.785 ms/op
                 existUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15948
  mean =      2.004 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 13953 
    [ 2.500,  3.750) = 1704 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =     14.062 ms/op
     p(99.9900) =     14.785 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.108 ms/op
Iteration   1: 2.044 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.523 ms/op
                 getUser·p0.50:   1.889 ms/op
                 getUser·p0.90:   2.724 ms/op
                 getUser·p0.95:   2.949 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  13.767 ms/op
                 getUser·p0.9999: 17.128 ms/op
                 getUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15712
  mean =      2.044 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 376 
    [ 1.250,  2.500) = 12624 
    [ 2.500,  3.750) = 2527 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.889 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =     13.767 ms/op
     p(99.9900) =     17.128 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.168 ms/op
Iteration   1: 3.950 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.090 ms/op
                 listUser·p0.99:   7.030 ms/op
                 listUser·p0.999:  21.299 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8092
  mean =      3.950 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 166 
    [ 2.500,  5.000) = 7480 
    [ 5.000,  7.500) = 376 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.090 ms/op
     p(99.0000) =      7.030 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.419          ops/ms
ClientSimple.existUser                       thrpt         13.017          ops/ms
ClientSimple.getUser                         thrpt         11.948          ops/ms
ClientSimple.listUser                        thrpt          8.519          ops/ms
ClientSimple.createUser                       avgt          2.482           ms/op
ClientSimple.existUser                        avgt          1.758           ms/op
ClientSimple.getUser                          avgt          2.085           ms/op
ClientSimple.listUser                         avgt          3.660           ms/op
ClientSimple.createUser                     sample  14067   2.281 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.388           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.089           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.330           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.072           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.322           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.083           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.296           ms/op
ClientSimple.existUser                      sample  15948   2.004 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.621           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.843           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.896           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.141           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.062           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.785           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.795           ms/op
ClientSimple.getUser                        sample  15712   2.044 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.523           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.889           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.055           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.767           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.128           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.334           ms/op
ClientSimple.listUser                       sample   8092   3.950 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.122           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.961           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.090           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.030           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.299           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.364           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.364           ms/op

Benchmark result is saved to 1715407502509.json
