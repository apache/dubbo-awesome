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
# Warmup Iteration   1: 2.153 ops/ms
Iteration   1: 6.020 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.020 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.974 ops/ms
Iteration   1: 11.891 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.891 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.854 ops/ms
Iteration   1: 7.071 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.071 ops/ms


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
# Warmup Iteration   1: 1.989 ops/ms
Iteration   1: 3.713 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.713 ops/ms


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
# Warmup Iteration   1: 5.228 ±(99.9%) 0.070 ms/op
Iteration   1: 3.046 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.046 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.338 ±(99.9%) 0.031 ms/op
Iteration   1: 1.834 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.834 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.851 ±(99.9%) 0.058 ms/op
Iteration   1: 2.875 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.875 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.375 ±(99.9%) 0.267 ms/op
Iteration   1: 8.467 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.467 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.608 ±(99.9%) 0.105 ms/op
Iteration   1: 2.966 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   2.798 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  13.963 ms/op
                 createUser·p0.9999: 14.041 ms/op
                 createUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10779
  mean =      2.966 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 2536 
    [ 2.500,  3.750) = 7344 
    [ 3.750,  5.000) = 601 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     13.963 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 2.918 ±(99.9%) 0.057 ms/op
Iteration   1: 1.909 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.378 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   3.899 ms/op
                 existUser·p0.999:  10.823 ms/op
                 existUser·p0.9999: 11.707 ms/op
                 existUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16802
  mean =      1.909 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 333 
    [ 1.250,  2.500) = 15180 
    [ 2.500,  3.750) = 1098 
    [ 3.750,  5.000) = 154 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =     10.823 ms/op
     p(99.9900) =     11.707 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.171 ms/op
Iteration   1: 3.004 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   2.773 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   7.694 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 13.793 ms/op
                 getUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10664
  mean =      3.004 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 2744 
    [ 2.500,  3.750) = 6633 
    [ 3.750,  5.000) = 913 
    [ 5.000,  6.250) = 135 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.694 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.793 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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
# Warmup Iteration   1: 11.247 ±(99.9%) 0.337 ms/op
Iteration   1: 8.566 ±(99.9%) 0.110 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   8.290 ms/op
                 listUser·p0.90:   11.174 ms/op
                 listUser·p0.95:   12.272 ms/op
                 listUser·p0.99:   15.360 ms/op
                 listUser·p0.999:  18.637 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3749
  mean =      8.566 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 28 
    [ 5.000,  7.500) = 1211 
    [ 7.500, 10.000) = 1713 
    [10.000, 12.500) = 634 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.597 ms/op
     p(50.0000) =      8.290 ms/op
     p(90.0000) =     11.174 ms/op
     p(95.0000) =     12.272 ms/op
     p(99.0000) =     15.360 ms/op
     p(99.9000) =     18.637 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.020          ops/ms
Client.existUser                       thrpt         11.891          ops/ms
Client.getUser                         thrpt          7.071          ops/ms
Client.listUser                        thrpt          3.713          ops/ms
Client.createUser                       avgt          3.046           ms/op
Client.existUser                        avgt          1.834           ms/op
Client.getUser                          avgt          2.875           ms/op
Client.listUser                         avgt          8.467           ms/op
Client.createUser                     sample  10779   2.966 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          0.919           ms/op
Client.createUser:createUser·p0.50    sample          2.798           ms/op
Client.createUser:createUser·p0.90    sample          3.617           ms/op
Client.createUser:createUser·p0.95    sample          4.137           ms/op
Client.createUser:createUser·p0.99    sample          7.274           ms/op
Client.createUser:createUser·p0.999   sample         13.963           ms/op
Client.createUser:createUser·p0.9999  sample         14.041           ms/op
Client.createUser:createUser·p1.00    sample         14.041           ms/op
Client.existUser                      sample  16802   1.909 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.378           ms/op
Client.existUser:existUser·p0.50      sample          1.778           ms/op
Client.existUser:existUser·p0.90      sample          2.425           ms/op
Client.existUser:existUser·p0.95      sample          2.654           ms/op
Client.existUser:existUser·p0.99      sample          3.899           ms/op
Client.existUser:existUser·p0.999     sample         10.823           ms/op
Client.existUser:existUser·p0.9999    sample         11.707           ms/op
Client.existUser:existUser·p1.00      sample         13.189           ms/op
Client.getUser                        sample  10664   3.004 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          0.743           ms/op
Client.getUser:getUser·p0.50          sample          2.773           ms/op
Client.getUser:getUser·p0.90          sample          3.842           ms/op
Client.getUser:getUser·p0.95          sample          4.391           ms/op
Client.getUser:getUser·p0.99          sample          7.694           ms/op
Client.getUser:getUser·p0.999         sample         13.058           ms/op
Client.getUser:getUser·p0.9999        sample         13.793           ms/op
Client.getUser:getUser·p1.00          sample         13.828           ms/op
Client.listUser                       sample   3749   8.566 ± 0.110   ms/op
Client.listUser:listUser·p0.00        sample          2.597           ms/op
Client.listUser:listUser·p0.50        sample          8.290           ms/op
Client.listUser:listUser·p0.90        sample         11.174           ms/op
Client.listUser:listUser·p0.95        sample         12.272           ms/op
Client.listUser:listUser·p0.99        sample         15.360           ms/op
Client.listUser:listUser·p0.999       sample         18.637           ms/op
Client.listUser:listUser·p0.9999      sample         20.152           ms/op
Client.listUser:listUser·p1.00        sample         20.152           ms/op
