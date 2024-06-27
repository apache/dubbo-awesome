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
# Warmup Iteration   1: 1.308 ops/ms
Iteration   1: 5.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.769 ops/ms


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
# Warmup Iteration   1: 5.421 ops/ms
Iteration   1: 11.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.158 ops/ms


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
# Warmup Iteration   1: 4.574 ops/ms
Iteration   1: 9.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.160 ops/ms


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
# Warmup Iteration   1: 3.679 ops/ms
Iteration   1: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.608 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.868 ±(99.9%) 0.099 ms/op
Iteration   1: 2.251 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.251 ms/op


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
# Warmup Iteration   1: 3.786 ±(99.9%) 0.062 ms/op
Iteration   1: 2.576 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.576 ms/op


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
# Warmup Iteration   1: 3.511 ±(99.9%) 0.068 ms/op
Iteration   1: 2.276 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.276 ms/op


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
# Warmup Iteration   1: 4.530 ±(99.9%) 0.086 ms/op
Iteration   1: 3.509 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.509 ms/op


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.145 ms/op
Iteration   1: 2.183 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   1.954 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   2.888 ms/op
                 createUser·p0.99:   7.081 ms/op
                 createUser·p0.999:  21.082 ms/op
                 createUser·p0.9999: 22.660 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14633
  mean =      2.183 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13133 
    [ 2.500,  5.000) = 1263 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      7.081 ms/op
     p(99.9000) =     21.082 ms/op
     p(99.9900) =     22.660 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.097 ms/op
Iteration   1: 1.960 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.358 ms/op
                 existUser·p0.50:   1.905 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.806 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  15.122 ms/op
                 existUser·p0.9999: 15.229 ms/op
                 existUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16298
  mean =      1.960 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 684 
    [ 1.250,  2.500) = 13786 
    [ 2.500,  3.750) = 1649 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     15.229 ms/op
     p(99.9990) =     15.270 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 3.695 ±(99.9%) 0.105 ms/op
Iteration   1: 2.265 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.806 ms/op
                 getUser·p0.95:   3.069 ms/op
                 getUser·p0.99:   4.460 ms/op
                 getUser·p0.999:  14.179 ms/op
                 getUser·p0.9999: 16.126 ms/op
                 getUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14156
  mean =      2.265 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 11168 
    [ 2.500,  3.750) = 2719 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.069 ms/op
     p(99.0000) =      4.460 ms/op
     p(99.9000) =     14.179 ms/op
     p(99.9900) =     16.126 ms/op
     p(99.9990) =     16.187 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 5.153 ±(99.9%) 0.165 ms/op
Iteration   1: 3.468 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.277 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   6.651 ms/op
                 listUser·p0.999:  7.891 ms/op
                 listUser·p0.9999: 11.223 ms/op
                 listUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9350
  mean =      3.468 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 568 
    [ 2.500,  3.750) = 5651 
    [ 3.750,  5.000) = 2627 
    [ 5.000,  6.250) = 345 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      6.651 ms/op
     p(99.9000) =      7.891 ms/op
     p(99.9900) =     11.223 ms/op
     p(99.9990) =     11.223 ms/op
     p(99.9999) =     11.223 ms/op
    p(100.0000) =     11.223 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.769          ops/ms
ClientSimple.existUser                       thrpt         11.158          ops/ms
ClientSimple.getUser                         thrpt          9.160          ops/ms
ClientSimple.listUser                        thrpt          8.608          ops/ms
ClientSimple.createUser                       avgt          2.251           ms/op
ClientSimple.existUser                        avgt          2.576           ms/op
ClientSimple.getUser                          avgt          2.276           ms/op
ClientSimple.listUser                         avgt          3.509           ms/op
ClientSimple.createUser                     sample  14633   2.183 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.838           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.954           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.081           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.082           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.660           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.675           ms/op
ClientSimple.existUser                      sample  16298   1.960 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.358           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.905           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.806           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.076           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.122           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.229           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.270           ms/op
ClientSimple.getUser                        sample  14156   2.265 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.625           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.069           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.460           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.179           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.126           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.187           ms/op
ClientSimple.listUser                       sample   9350   3.468 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.071           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.277           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.054           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.651           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.891           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.223           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.223           ms/op

Benchmark result is saved to 1719511524851.json
