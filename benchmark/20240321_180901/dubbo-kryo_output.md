# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.896 ops/ms
Iteration   1: 7.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.697 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.612 ops/ms
Iteration   1: 13.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.923 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.674 ops/ms
Iteration   1: 13.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.846 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ops/ms
Iteration   1: 8.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.090 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ±(99.9%) 0.074 ms/op
Iteration   1: 2.219 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.219 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.057 ms/op
Iteration   1: 1.757 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.291 ±(99.9%) 0.055 ms/op
Iteration   1: 1.965 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.965 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.861 ±(99.9%) 0.095 ms/op
Iteration   1: 2.879 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.879 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.428 ±(99.9%) 0.087 ms/op
Iteration   1: 2.266 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   2.847 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  21.718 ms/op
                 createUser·p0.9999: 23.139 ms/op
                 createUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14220
  mean =      2.266 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11302 
    [ 2.500,  5.000) = 2644 
    [ 5.000,  7.500) = 82 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     21.718 ms/op
     p(99.9900) =     23.139 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.800 ±(99.9%) 0.058 ms/op
Iteration   1: 1.955 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.691 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  27.775 ms/op
                 existUser·p0.9999: 28.040 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16362
  mean =      1.955 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15122 
    [ 2.500,  5.000) = 1164 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =     27.775 ms/op
     p(99.9900) =     28.040 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.170 ±(99.9%) 0.079 ms/op
Iteration   1: 2.109 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.620 ms/op
                 getUser·p0.50:   2.025 ms/op
                 getUser·p0.90:   2.699 ms/op
                 getUser·p0.95:   2.896 ms/op
                 getUser·p0.99:   4.004 ms/op
                 getUser·p0.999:  11.024 ms/op
                 getUser·p0.9999: 11.370 ms/op
                 getUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15156
  mean =      2.109 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 12535 
    [ 2.500,  3.750) = 2314 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      4.004 ms/op
     p(99.9000) =     11.024 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     11.370 ms/op
     p(99.9999) =     11.370 ms/op
    p(100.0000) =     11.370 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.699 ±(99.9%) 0.127 ms/op
Iteration   1: 3.490 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.633 ms/op
                 listUser·p0.50:   3.224 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   5.578 ms/op
                 listUser·p0.999:  18.608 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9135
  mean =      3.490 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 354 
    [ 2.500,  3.750) = 5883 
    [ 3.750,  5.000) = 2677 
    [ 5.000,  6.250) = 118 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.578 ms/op
     p(99.9000) =     18.608 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.697          ops/ms
ClientSimple.existUser                       thrpt         13.923          ops/ms
ClientSimple.getUser                         thrpt         13.846          ops/ms
ClientSimple.listUser                        thrpt          8.090          ops/ms
ClientSimple.createUser                       avgt          2.219           ms/op
ClientSimple.existUser                        avgt          1.757           ms/op
ClientSimple.getUser                          avgt          1.965           ms/op
ClientSimple.listUser                         avgt          2.879           ms/op
ClientSimple.createUser                     sample  14220   2.266 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.555           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.273           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.718           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.139           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.167           ms/op
ClientSimple.existUser                      sample  16362   1.955 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.617           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.691           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.748           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.775           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.040           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.082           ms/op
ClientSimple.getUser                        sample  15156   2.109 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.620           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.025           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.004           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.024           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.370           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.370           ms/op
ClientSimple.listUser                       sample   9135   3.490 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.633           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.224           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.578           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.608           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.678           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.678           ms/op

Benchmark result is saved to 1711044301782.json
