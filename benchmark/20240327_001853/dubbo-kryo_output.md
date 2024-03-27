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
# Warmup Iteration   1: 1.667 ops/ms
Iteration   1: 7.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.027 ops/ms


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
# Warmup Iteration   1: 6.050 ops/ms
Iteration   1: 13.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.101 ops/ms


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
# Warmup Iteration   1: 6.210 ops/ms
Iteration   1: 13.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.238 ops/ms


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
# Warmup Iteration   1: 4.965 ops/ms
Iteration   1: 8.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.096 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.063 ±(99.9%) 0.073 ms/op
Iteration   1: 2.152 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.152 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.068 ms/op
Iteration   1: 1.687 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.687 ms/op


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
# Warmup Iteration   1: 3.372 ±(99.9%) 0.066 ms/op
Iteration   1: 1.959 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.959 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.435 ±(99.9%) 0.102 ms/op
Iteration   1: 3.780 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.780 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.650 ±(99.9%) 0.090 ms/op
Iteration   1: 1.934 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   1.774 ms/op
                 createUser·p0.90:   2.253 ms/op
                 createUser·p0.95:   2.527 ms/op
                 createUser·p0.99:   5.239 ms/op
                 createUser·p0.999:  32.375 ms/op
                 createUser·p0.9999: 34.517 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16549
  mean =      1.934 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15704 
    [ 2.500,  5.000) = 663 
    [ 5.000,  7.500) = 131 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.253 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      5.239 ms/op
     p(99.9000) =     32.375 ms/op
     p(99.9900) =     34.517 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 2.998 ±(99.9%) 0.067 ms/op
Iteration   1: 1.758 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.463 ms/op
                 existUser·p0.50:   1.559 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.497 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  20.447 ms/op
                 existUser·p0.9999: 21.081 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18187
  mean =      1.758 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17295 
    [ 2.500,  5.000) = 805 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      1.559 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.497 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     21.081 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 3.093 ±(99.9%) 0.069 ms/op
Iteration   1: 1.937 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.544 ms/op
                 getUser·p0.99:   3.258 ms/op
                 getUser·p0.999:  23.944 ms/op
                 getUser·p0.9999: 25.114 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16455
  mean =      1.937 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15467 
    [ 2.500,  5.000) = 922 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      3.258 ms/op
     p(99.9000) =     23.944 ms/op
     p(99.9900) =     25.114 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 4.314 ±(99.9%) 0.149 ms/op
Iteration   1: 2.870 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.671 ms/op
                 listUser·p0.90:   3.690 ms/op
                 listUser·p0.95:   3.992 ms/op
                 listUser·p0.99:   5.460 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 9.828 ms/op
                 listUser·p1.00:   9.830 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 11187
  mean =      2.870 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 125 
    [ 2.000,  3.000) = 7993 
    [ 3.000,  4.000) = 2519 
    [ 4.000,  5.000) = 426 
    [ 5.000,  6.000) = 21 
    [ 6.000,  7.000) = 46 
    [ 7.000,  8.000) = 16 
    [ 8.000,  9.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.992 ms/op
     p(99.0000) =      5.460 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =      9.828 ms/op
     p(99.9990) =      9.830 ms/op
     p(99.9999) =      9.830 ms/op
    p(100.0000) =      9.830 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.027          ops/ms
ClientSimple.existUser                       thrpt         13.101          ops/ms
ClientSimple.getUser                         thrpt         13.238          ops/ms
ClientSimple.listUser                        thrpt          8.096          ops/ms
ClientSimple.createUser                       avgt          2.152           ms/op
ClientSimple.existUser                        avgt          1.687           ms/op
ClientSimple.getUser                          avgt          1.959           ms/op
ClientSimple.listUser                         avgt          3.780           ms/op
ClientSimple.createUser                     sample  16549   1.934 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.623           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.774           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.253           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.239           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.375           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.517           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.603           ms/op
ClientSimple.existUser                      sample  18187   1.758 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.463           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.559           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.497           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.465           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.447           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.081           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.430           ms/op
ClientSimple.getUser                        sample  16455   1.937 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.555           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.544           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.258           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.944           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.114           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.199           ms/op
ClientSimple.listUser                       sample  11187   2.870 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.834           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.671           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.992           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.460           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.257           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.828           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.830           ms/op

Benchmark result is saved to 1711498457490.json
