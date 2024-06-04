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
# Warmup Iteration   1: 1.669 ops/ms
Iteration   1: 7.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.279 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.292 ops/ms
Iteration   1: 13.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.297 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.279 ops/ms
Iteration   1: 15.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.378 ops/ms


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
# Warmup Iteration   1: 5.350 ops/ms
Iteration   1: 8.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.428 ops/ms


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
# Warmup Iteration   1: 3.861 ±(99.9%) 0.082 ms/op
Iteration   1: 2.164 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.164 ms/op


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
# Warmup Iteration   1: 3.665 ±(99.9%) 0.071 ms/op
Iteration   1: 2.017 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.017 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.066 ms/op
Iteration   1: 2.000 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.000 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.372 ±(99.9%) 0.097 ms/op
Iteration   1: 3.343 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.343 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ±(99.9%) 0.103 ms/op
Iteration   1: 2.287 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.134 ms/op
                 createUser·p0.90:   2.814 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   7.110 ms/op
                 createUser·p0.999:  17.334 ms/op
                 createUser·p0.9999: 17.583 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14001
  mean =      2.287 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 425 
    [ 1.250,  2.500) = 10807 
    [ 2.500,  3.750) = 2360 
    [ 3.750,  5.000) = 168 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      7.110 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     17.583 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 2.894 ±(99.9%) 0.066 ms/op
Iteration   1: 1.831 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.451 ms/op
                 existUser·p0.50:   1.726 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.497 ms/op
                 existUser·p0.99:   3.876 ms/op
                 existUser·p0.999:  12.655 ms/op
                 existUser·p0.9999: 13.687 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17587
  mean =      1.831 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1241 
    [ 1.250,  2.500) = 15477 
    [ 2.500,  3.750) = 679 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.497 ms/op
     p(99.0000) =      3.876 ms/op
     p(99.9000) =     12.655 ms/op
     p(99.9900) =     13.687 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.085 ms/op
Iteration   1: 2.160 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.501 ms/op
                 getUser·p0.50:   2.101 ms/op
                 getUser·p0.90:   2.875 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 13.161 ms/op
                 getUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14881
  mean =      2.160 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 11240 
    [ 2.500,  3.750) = 3437 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     13.161 ms/op
     p(99.9990) =     13.369 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


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
# Warmup Iteration   1: 5.075 ±(99.9%) 0.361 ms/op
Iteration   1: 3.486 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.449 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  22.807 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9194
  mean =      3.486 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1216 
    [ 2.500,  5.000) = 7759 
    [ 5.000,  7.500) = 148 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.279          ops/ms
ClientSimple.existUser                       thrpt         13.297          ops/ms
ClientSimple.getUser                         thrpt         15.378          ops/ms
ClientSimple.listUser                        thrpt          8.428          ops/ms
ClientSimple.createUser                       avgt          2.164           ms/op
ClientSimple.existUser                        avgt          2.017           ms/op
ClientSimple.getUser                          avgt          2.000           ms/op
ClientSimple.listUser                         avgt          3.343           ms/op
ClientSimple.createUser                     sample  14001   2.287 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.569           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.134           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.240           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.110           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.334           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.583           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.596           ms/op
ClientSimple.existUser                      sample  17587   1.831 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.451           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.726           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.497           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.876           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.655           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.687           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.812           ms/op
ClientSimple.getUser                        sample  14881   2.160 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.501           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.101           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.146           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.752           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.977           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.161           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.369           ms/op
ClientSimple.listUser                       sample   9194   3.486 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.033           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.449           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.170           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.062           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.807           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.970           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.970           ms/op

Benchmark result is saved to 1717502795014.json
