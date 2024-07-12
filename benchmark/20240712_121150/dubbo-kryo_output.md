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
# Warmup Iteration   1: 1.571 ops/ms
Iteration   1: 8.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.017 ops/ms


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
# Warmup Iteration   1: 5.166 ops/ms
Iteration   1: 11.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.150 ops/ms


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
# Warmup Iteration   1: 4.327 ops/ms
Iteration   1: 11.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.246 ops/ms


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
# Warmup Iteration   1: 4.500 ops/ms
Iteration   1: 8.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.347 ops/ms


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.064 ms/op
Iteration   1: 2.450 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.450 ms/op


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
# Warmup Iteration   1: 2.996 ±(99.9%) 0.041 ms/op
Iteration   1: 1.824 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.824 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.062 ms/op
Iteration   1: 2.369 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.369 ms/op


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
# Warmup Iteration   1: 4.184 ±(99.9%) 0.077 ms/op
Iteration   1: 3.636 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.636 ms/op


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
# Warmup Iteration   1: 3.440 ±(99.9%) 0.086 ms/op
Iteration   1: 1.947 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   1.860 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   2.703 ms/op
                 createUser·p0.99:   3.689 ms/op
                 createUser·p0.999:  17.760 ms/op
                 createUser·p0.9999: 21.507 ms/op
                 createUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16568
  mean =      1.947 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15171 
    [ 2.500,  5.000) = 1322 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.689 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     21.507 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 2.842 ±(99.9%) 0.061 ms/op
Iteration   1: 1.751 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.477 ms/op
                 existUser·p0.50:   1.622 ms/op
                 existUser·p0.90:   2.023 ms/op
                 existUser·p0.95:   2.204 ms/op
                 existUser·p0.99:   5.189 ms/op
                 existUser·p0.999:  23.600 ms/op
                 existUser·p0.9999: 24.361 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18256
  mean =      1.751 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17790 
    [ 2.500,  5.000) = 268 
    [ 5.000,  7.500) = 112 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.622 ms/op
     p(90.0000) =      2.023 ms/op
     p(95.0000) =      2.204 ms/op
     p(99.0000) =      5.189 ms/op
     p(99.9000) =     23.600 ms/op
     p(99.9900) =     24.361 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 3.392 ±(99.9%) 0.094 ms/op
Iteration   1: 2.185 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.803 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  13.697 ms/op
                 getUser·p0.9999: 13.844 ms/op
                 getUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14892
  mean =      2.185 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 12306 
    [ 2.500,  3.750) = 2408 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.803 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     13.844 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 4.731 ±(99.9%) 0.131 ms/op
Iteration   1: 3.462 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.346 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.772 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  20.439 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9249
  mean =      3.462 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 414 
    [ 2.500,  5.000) = 8497 
    [ 5.000,  7.500) = 294 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.772 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     20.439 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.017          ops/ms
ClientSimple.existUser                       thrpt         11.150          ops/ms
ClientSimple.getUser                         thrpt         11.246          ops/ms
ClientSimple.listUser                        thrpt          8.347          ops/ms
ClientSimple.createUser                       avgt          2.450           ms/op
ClientSimple.existUser                        avgt          1.824           ms/op
ClientSimple.getUser                          avgt          2.369           ms/op
ClientSimple.listUser                         avgt          3.636           ms/op
ClientSimple.createUser                     sample  16568   1.947 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.770           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.860           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.689           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.760           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.507           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.529           ms/op
ClientSimple.existUser                      sample  18256   1.751 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.477           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.622           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.023           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.204           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.189           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.600           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.361           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.740           ms/op
ClientSimple.getUser                        sample  14892   2.185 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.803           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.748           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.697           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.844           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.844           ms/op
ClientSimple.listUser                       sample   9249   3.462 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.967           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.346           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.772           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.480           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.439           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.004           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.004           ms/op

Benchmark result is saved to 1720786052778.json
