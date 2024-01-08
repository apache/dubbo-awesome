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
# Warmup Iteration   1: 2.619 ops/ms
Iteration   1: 6.263 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.263 ops/ms


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
# Warmup Iteration   1: 6.123 ops/ms
Iteration   1: 15.735 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  15.735 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.291 ops/ms
Iteration   1: 8.527 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.527 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.062 ops/ms
Iteration   1: 3.660 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.660 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.426 ±(99.9%) 0.067 ms/op
Iteration   1: 3.151 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.151 ms/op


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
# Warmup Iteration   1: 2.935 ±(99.9%) 0.028 ms/op
Iteration   1: 1.820 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.820 ms/op


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
# Warmup Iteration   1: 4.675 ±(99.9%) 0.065 ms/op
Iteration   1: 2.973 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.973 ms/op


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
# Warmup Iteration   1: 12.330 ±(99.9%) 0.285 ms/op
Iteration   1: 9.283 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.283 ms/op


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.129 ms/op
Iteration   1: 2.978 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   2.798 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   6.871 ms/op
                 createUser·p0.999:  10.535 ms/op
                 createUser·p0.9999: 13.663 ms/op
                 createUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10729
  mean =      2.978 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2284 
    [ 2.500,  3.750) = 7202 
    [ 3.750,  5.000) = 1046 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.871 ms/op
     p(99.9000) =     10.535 ms/op
     p(99.9900) =     13.663 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.299 ±(99.9%) 0.112 ms/op
Iteration   1: 1.775 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.425 ms/op
                 existUser·p0.99:   2.675 ms/op
                 existUser·p0.999:  4.127 ms/op
                 existUser·p0.9999: 4.996 ms/op
                 existUser·p1.00:   5.095 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18120
  mean =      1.775 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 104 
    [1.000, 1.500) = 4909 
    [1.500, 2.000) = 7896 
    [2.000, 2.500) = 4612 
    [2.500, 3.000) = 524 
    [3.000, 3.500) = 37 
    [3.500, 4.000) = 17 
    [4.000, 4.500) = 12 
    [4.500, 5.000) = 8 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.425 ms/op
     p(99.0000) =      2.675 ms/op
     p(99.9000) =      4.127 ms/op
     p(99.9900) =      4.996 ms/op
     p(99.9990) =      5.095 ms/op
     p(99.9999) =      5.095 ms/op
    p(100.0000) =      5.095 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.365 ±(99.9%) 0.092 ms/op
Iteration   1: 2.942 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   2.908 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  6.390 ms/op
                 getUser·p0.9999: 7.947 ms/op
                 getUser·p1.00:   7.979 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10855
  mean =      2.942 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 12 
    [1.000, 1.500) = 65 
    [1.500, 2.000) = 448 
    [2.000, 2.500) = 2334 
    [2.500, 3.000) = 3201 
    [3.000, 3.500) = 2767 
    [3.500, 4.000) = 1558 
    [4.000, 4.500) = 234 
    [4.500, 5.000) = 130 
    [5.000, 5.500) = 82 
    [5.500, 6.000) = 2 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =      6.390 ms/op
     p(99.9900) =      7.947 ms/op
     p(99.9990) =      7.979 ms/op
     p(99.9999) =      7.979 ms/op
    p(100.0000) =      7.979 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.155 ±(99.9%) 0.432 ms/op
Iteration   1: 8.458 ±(99.9%) 0.161 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   7.954 ms/op
                 listUser·p0.90:   11.518 ms/op
                 listUser·p0.95:   12.689 ms/op
                 listUser·p0.99:   24.052 ms/op
                 listUser·p0.999:  28.046 ms/op
                 listUser·p0.9999: 29.688 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3809
  mean =      8.458 ±(99.9%) 0.161 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 182 
    [ 5.000,  7.500) = 1318 
    [ 7.500, 10.000) = 1574 
    [10.000, 12.500) = 511 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.788 ms/op
     p(50.0000) =      7.954 ms/op
     p(90.0000) =     11.518 ms/op
     p(95.0000) =     12.689 ms/op
     p(99.0000) =     24.052 ms/op
     p(99.9000) =     28.046 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     29.688 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.263          ops/ms
Client.existUser                       thrpt         15.735          ops/ms
Client.getUser                         thrpt          8.527          ops/ms
Client.listUser                        thrpt          3.660          ops/ms
Client.createUser                       avgt          3.151           ms/op
Client.existUser                        avgt          1.820           ms/op
Client.getUser                          avgt          2.973           ms/op
Client.listUser                         avgt          9.283           ms/op
Client.createUser                     sample  10729   2.978 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.266           ms/op
Client.createUser:createUser·p0.50    sample          2.798           ms/op
Client.createUser:createUser·p0.90    sample          3.858           ms/op
Client.createUser:createUser·p0.95    sample          4.166           ms/op
Client.createUser:createUser·p0.99    sample          6.871           ms/op
Client.createUser:createUser·p0.999   sample         10.535           ms/op
Client.createUser:createUser·p0.9999  sample         13.663           ms/op
Client.createUser:createUser·p1.00    sample         13.664           ms/op
Client.existUser                      sample  18120   1.775 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.510           ms/op
Client.existUser:existUser·p0.50      sample          1.745           ms/op
Client.existUser:existUser·p0.90      sample          2.277           ms/op
Client.existUser:existUser·p0.95      sample          2.425           ms/op
Client.existUser:existUser·p0.99      sample          2.675           ms/op
Client.existUser:existUser·p0.999     sample          4.127           ms/op
Client.existUser:existUser·p0.9999    sample          4.996           ms/op
Client.existUser:existUser·p1.00      sample          5.095           ms/op
Client.getUser                        sample  10855   2.942 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.644           ms/op
Client.getUser:getUser·p0.50          sample          2.908           ms/op
Client.getUser:getUser·p0.90          sample          3.699           ms/op
Client.getUser:getUser·p0.95          sample          3.928           ms/op
Client.getUser:getUser·p0.99          sample          4.997           ms/op
Client.getUser:getUser·p0.999         sample          6.390           ms/op
Client.getUser:getUser·p0.9999        sample          7.947           ms/op
Client.getUser:getUser·p1.00          sample          7.979           ms/op
Client.listUser                       sample   3809   8.458 ± 0.161   ms/op
Client.listUser:listUser·p0.00        sample          1.788           ms/op
Client.listUser:listUser·p0.50        sample          7.954           ms/op
Client.listUser:listUser·p0.90        sample         11.518           ms/op
Client.listUser:listUser·p0.95        sample         12.689           ms/op
Client.listUser:listUser·p0.99        sample         24.052           ms/op
Client.listUser:listUser·p0.999       sample         28.046           ms/op
Client.listUser:listUser·p0.9999      sample         29.688           ms/op
Client.listUser:listUser·p1.00        sample         29.688           ms/op
