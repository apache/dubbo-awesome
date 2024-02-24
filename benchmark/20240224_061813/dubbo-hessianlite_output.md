# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.411 ops/ms
Iteration   1: 6.183 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.183 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.653 ops/ms
Iteration   1: 13.757 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.757 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.514 ops/ms
Iteration   1: 9.062 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.062 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.038 ops/ms
Iteration   1: 3.341 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.341 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.929 ±(99.9%) 0.076 ms/op
Iteration   1: 3.067 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.067 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.033 ±(99.9%) 0.031 ms/op
Iteration   1: 1.790 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.790 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ±(99.9%) 0.065 ms/op
Iteration   1: 3.384 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.384 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.396 ±(99.9%) 0.154 ms/op
Iteration   1: 9.018 ±(99.9%) 0.127 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.018 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.165 ±(99.9%) 0.100 ms/op
Iteration   1: 3.070 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   2.847 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  10.486 ms/op
                 createUser·p0.9999: 11.599 ms/op
                 createUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10401
  mean =      3.070 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 999 
    [ 2.500,  3.750) = 8221 
    [ 3.750,  5.000) = 935 
    [ 5.000,  6.250) = 144 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     10.486 ms/op
     p(99.9900) =     11.599 ms/op
     p(99.9990) =     11.600 ms/op
     p(99.9999) =     11.600 ms/op
    p(100.0000) =     11.600 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.498 ±(99.9%) 0.089 ms/op
Iteration   1: 1.886 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  19.726 ms/op
                 existUser·p0.9999: 19.917 ms/op
                 existUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17229
  mean =      1.886 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 411 
    [ 1.250,  2.500) = 16042 
    [ 2.500,  3.750) = 595 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     19.917 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.781 ±(99.9%) 0.115 ms/op
Iteration   1: 3.391 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.397 ms/op
                 getUser·p0.999:  20.827 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9422
  mean =      3.391 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 671 
    [ 2.500,  5.000) = 8608 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.397 ms/op
     p(99.9000) =     20.827 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.506 ±(99.9%) 0.695 ms/op
Iteration   1: 8.124 ±(99.9%) 0.161 ms/op
                 listUser·p0.00:   2.798 ms/op
                 listUser·p0.50:   7.627 ms/op
                 listUser·p0.90:   10.211 ms/op
                 listUser·p0.95:   11.551 ms/op
                 listUser·p0.99:   21.037 ms/op
                 listUser·p0.999:  37.163 ms/op
                 listUser·p0.9999: 37.487 ms/op
                 listUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3937
  mean =      8.124 ±(99.9%) 0.161 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 104 
    [ 5.000,  7.500) = 1719 
    [ 7.500, 10.000) = 1660 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.798 ms/op
     p(50.0000) =      7.627 ms/op
     p(90.0000) =     10.211 ms/op
     p(95.0000) =     11.551 ms/op
     p(99.0000) =     21.037 ms/op
     p(99.9000) =     37.163 ms/op
     p(99.9900) =     37.487 ms/op
     p(99.9990) =     37.487 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.183          ops/ms
Client.existUser                       thrpt         13.757          ops/ms
Client.getUser                         thrpt          9.062          ops/ms
Client.listUser                        thrpt          3.341          ops/ms
Client.createUser                       avgt          3.067           ms/op
Client.existUser                        avgt          1.790           ms/op
Client.getUser                          avgt          3.384           ms/op
Client.listUser                         avgt          9.018           ms/op
Client.createUser                     sample  10401   3.070 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.206           ms/op
Client.createUser:createUser·p0.50    sample          2.847           ms/op
Client.createUser:createUser·p0.90    sample          3.805           ms/op
Client.createUser:createUser·p0.95    sample          4.194           ms/op
Client.createUser:createUser·p0.99    sample          5.808           ms/op
Client.createUser:createUser·p0.999   sample         10.486           ms/op
Client.createUser:createUser·p0.9999  sample         11.599           ms/op
Client.createUser:createUser·p1.00    sample         11.600           ms/op
Client.existUser                      sample  17229   1.886 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.867           ms/op
Client.existUser:existUser·p0.50      sample          1.772           ms/op
Client.existUser:existUser·p0.90      sample          2.273           ms/op
Client.existUser:existUser·p0.95      sample          2.470           ms/op
Client.existUser:existUser·p0.99      sample          3.940           ms/op
Client.existUser:existUser·p0.999     sample         19.726           ms/op
Client.existUser:existUser·p0.9999    sample         19.917           ms/op
Client.existUser:existUser·p1.00      sample         19.988           ms/op
Client.getUser                        sample   9422   3.391 ± 0.040   ms/op
Client.getUser:getUser·p0.00          sample          1.010           ms/op
Client.getUser:getUser·p0.50          sample          3.297           ms/op
Client.getUser:getUser·p0.90          sample          4.157           ms/op
Client.getUser:getUser·p0.95          sample          4.514           ms/op
Client.getUser:getUser·p0.99          sample          5.397           ms/op
Client.getUser:getUser·p0.999         sample         20.827           ms/op
Client.getUser:getUser·p0.9999        sample         22.217           ms/op
Client.getUser:getUser·p1.00          sample         22.217           ms/op
Client.listUser                       sample   3937   8.124 ± 0.161   ms/op
Client.listUser:listUser·p0.00        sample          2.798           ms/op
Client.listUser:listUser·p0.50        sample          7.627           ms/op
Client.listUser:listUser·p0.90        sample         10.211           ms/op
Client.listUser:listUser·p0.95        sample         11.551           ms/op
Client.listUser:listUser·p0.99        sample         21.037           ms/op
Client.listUser:listUser·p0.999       sample         37.163           ms/op
Client.listUser:listUser·p0.9999      sample         37.487           ms/op
Client.listUser:listUser·p1.00        sample         37.487           ms/op
