# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.316 ops/ms
Iteration   1: 6.600 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.600 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.715 ops/ms
Iteration   1: 13.557 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.557 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.445 ops/ms
Iteration   1: 7.874 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.874 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.297 ops/ms
Iteration   1: 3.714 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.714 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.325 ±(99.9%) 0.070 ms/op
Iteration   1: 3.252 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.252 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.164 ±(99.9%) 0.029 ms/op
Iteration   1: 2.041 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.041 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.503 ±(99.9%) 0.063 ms/op
Iteration   1: 3.071 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.071 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.950 ±(99.9%) 0.183 ms/op
Iteration   1: 7.937 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.937 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.959 ±(99.9%) 0.235 ms/op
Iteration   1: 2.737 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.910 ms/op
                 createUser·p0.999:  16.357 ms/op
                 createUser·p0.9999: 19.098 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11668
  mean =      2.737 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 5921 
    [ 2.500,  3.750) = 5218 
    [ 3.750,  5.000) = 412 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.910 ms/op
     p(99.9000) =     16.357 ms/op
     p(99.9900) =     19.098 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.939 ±(99.9%) 0.057 ms/op
Iteration   1: 1.916 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.445 ms/op
                 existUser·p0.50:   1.868 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   3.281 ms/op
                 existUser·p0.999:  16.531 ms/op
                 existUser·p0.9999: 16.619 ms/op
                 existUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16678
  mean =      1.916 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 660 
    [ 1.250,  2.500) = 15312 
    [ 2.500,  3.750) = 606 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      3.281 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     16.619 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.103 ms/op
Iteration   1: 2.842 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.642 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.037 ms/op
                 getUser·p0.99:   5.918 ms/op
                 getUser·p0.999:  16.122 ms/op
                 getUser·p0.9999: 16.291 ms/op
                 getUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11387
  mean =      2.842 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 5033 
    [ 2.500,  3.750) = 5303 
    [ 3.750,  5.000) = 806 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.037 ms/op
     p(99.0000) =      5.918 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     16.291 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.171 ±(99.9%) 0.294 ms/op
Iteration   1: 8.067 ±(99.9%) 0.135 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   7.643 ms/op
                 listUser·p0.90:   10.967 ms/op
                 listUser·p0.95:   11.928 ms/op
                 listUser·p0.99:   16.195 ms/op
                 listUser·p0.999:  28.877 ms/op
                 listUser·p0.9999: 58.655 ms/op
                 listUser·p1.00:   58.655 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3975
  mean =      8.067 ±(99.9%) 0.135 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 211 
    [ 5.000, 10.000) = 3019 
    [10.000, 15.000) = 689 
    [15.000, 20.000) = 45 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.847 ms/op
     p(50.0000) =      7.643 ms/op
     p(90.0000) =     10.967 ms/op
     p(95.0000) =     11.928 ms/op
     p(99.0000) =     16.195 ms/op
     p(99.9000) =     28.877 ms/op
     p(99.9900) =     58.655 ms/op
     p(99.9990) =     58.655 ms/op
     p(99.9999) =     58.655 ms/op
    p(100.0000) =     58.655 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.600          ops/ms
Client.existUser                       thrpt         13.557          ops/ms
Client.getUser                         thrpt          7.874          ops/ms
Client.listUser                        thrpt          3.714          ops/ms
Client.createUser                       avgt          3.252           ms/op
Client.existUser                        avgt          2.041           ms/op
Client.getUser                          avgt          3.071           ms/op
Client.listUser                         avgt          7.937           ms/op
Client.createUser                     sample  11668   2.737 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          1.077           ms/op
Client.createUser:createUser·p0.50    sample          2.494           ms/op
Client.createUser:createUser·p0.90    sample          3.330           ms/op
Client.createUser:createUser·p0.95    sample          3.707           ms/op
Client.createUser:createUser·p0.99    sample          4.910           ms/op
Client.createUser:createUser·p0.999   sample         16.357           ms/op
Client.createUser:createUser·p0.9999  sample         19.098           ms/op
Client.createUser:createUser·p1.00    sample         19.104           ms/op
Client.existUser                      sample  16678   1.916 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.445           ms/op
Client.existUser:existUser·p0.50      sample          1.868           ms/op
Client.existUser:existUser·p0.90      sample          2.294           ms/op
Client.existUser:existUser·p0.95      sample          2.462           ms/op
Client.existUser:existUser·p0.99      sample          3.281           ms/op
Client.existUser:existUser·p0.999     sample         16.531           ms/op
Client.existUser:existUser·p0.9999    sample         16.619           ms/op
Client.existUser:existUser·p1.00      sample         16.630           ms/op
Client.getUser                        sample  11387   2.842 ± 0.033   ms/op
Client.getUser:getUser·p0.00          sample          0.847           ms/op
Client.getUser:getUser·p0.50          sample          2.642           ms/op
Client.getUser:getUser·p0.90          sample          3.723           ms/op
Client.getUser:getUser·p0.95          sample          4.037           ms/op
Client.getUser:getUser·p0.99          sample          5.918           ms/op
Client.getUser:getUser·p0.999         sample         16.122           ms/op
Client.getUser:getUser·p0.9999        sample         16.291           ms/op
Client.getUser:getUser·p1.00          sample         16.302           ms/op
Client.listUser                       sample   3975   8.067 ± 0.135   ms/op
Client.listUser:listUser·p0.00        sample          1.847           ms/op
Client.listUser:listUser·p0.50        sample          7.643           ms/op
Client.listUser:listUser·p0.90        sample         10.967           ms/op
Client.listUser:listUser·p0.95        sample         11.928           ms/op
Client.listUser:listUser·p0.99        sample         16.195           ms/op
Client.listUser:listUser·p0.999       sample         28.877           ms/op
Client.listUser:listUser·p0.9999      sample         58.655           ms/op
Client.listUser:listUser·p1.00        sample         58.655           ms/op
