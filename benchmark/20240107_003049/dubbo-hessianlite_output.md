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
# Warmup Iteration   1: 2.393 ops/ms
Iteration   1: 5.591 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.591 ops/ms


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
# Warmup Iteration   1: 5.376 ops/ms
Iteration   1: 13.054 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.054 ops/ms


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
# Warmup Iteration   1: 4.004 ops/ms
Iteration   1: 7.055 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.055 ops/ms


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
# Warmup Iteration   1: 2.422 ops/ms
Iteration   1: 4.181 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.181 ops/ms


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.067 ms/op
Iteration   1: 3.177 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.177 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.030 ms/op
Iteration   1: 1.842 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.842 ms/op


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.064 ms/op
Iteration   1: 3.019 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.019 ms/op


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
# Warmup Iteration   1: 13.444 ±(99.9%) 0.350 ms/op
Iteration   1: 7.622 ±(99.9%) 0.121 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.622 ms/op


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.094 ms/op
Iteration   1: 2.862 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.707 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   6.224 ms/op
                 createUser·p0.999:  11.518 ms/op
                 createUser·p0.9999: 11.534 ms/op
                 createUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11220
  mean =      2.862 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 3212 
    [ 2.500,  3.750) = 7313 
    [ 3.750,  5.000) = 413 
    [ 5.000,  6.250) = 142 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.707 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      6.224 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     11.534 ms/op
     p(99.9990) =     11.534 ms/op
     p(99.9999) =     11.534 ms/op
    p(100.0000) =     11.534 ms/op


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
# Warmup Iteration   1: 3.188 ±(99.9%) 0.118 ms/op
Iteration   1: 1.922 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.210 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.505 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  18.448 ms/op
                 existUser·p0.9999: 18.645 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16629
  mean =      1.922 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 758 
    [ 1.250,  2.500) = 15032 
    [ 2.500,  3.750) = 688 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.210 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.505 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     18.645 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.107 ms/op
Iteration   1: 3.111 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.945 ms/op
                 getUser·p0.999:  6.455 ms/op
                 getUser·p0.9999: 9.222 ms/op
                 getUser·p1.00:   9.257 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10329
  mean =      3.111 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 11 
    [ 1.500,  2.000) = 326 
    [ 2.000,  2.500) = 1595 
    [ 2.500,  3.000) = 2926 
    [ 3.000,  3.500) = 3018 
    [ 3.500,  4.000) = 1591 
    [ 4.000,  4.500) = 440 
    [ 4.500,  5.000) = 176 
    [ 5.000,  5.500) = 93 
    [ 5.500,  6.000) = 56 
    [ 6.000,  6.500) = 88 
    [ 6.500,  7.000) = 2 
    [ 7.000,  7.500) = 5 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 1 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.945 ms/op
     p(99.9000) =      6.455 ms/op
     p(99.9900) =      9.222 ms/op
     p(99.9990) =      9.257 ms/op
     p(99.9999) =      9.257 ms/op
    p(100.0000) =      9.257 ms/op


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
# Warmup Iteration   1: 12.147 ±(99.9%) 0.454 ms/op
Iteration   1: 8.496 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   2.859 ms/op
                 listUser·p0.50:   8.135 ms/op
                 listUser·p0.90:   11.600 ms/op
                 listUser·p0.95:   12.665 ms/op
                 listUser·p0.99:   15.778 ms/op
                 listUser·p0.999:  20.877 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3763
  mean =      8.496 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 122 
    [ 5.000,  7.500) = 1253 
    [ 7.500, 10.000) = 1588 
    [10.000, 12.500) = 566 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.859 ms/op
     p(50.0000) =      8.135 ms/op
     p(90.0000) =     11.600 ms/op
     p(95.0000) =     12.665 ms/op
     p(99.0000) =     15.778 ms/op
     p(99.9000) =     20.877 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.591          ops/ms
Client.existUser                       thrpt         13.054          ops/ms
Client.getUser                         thrpt          7.055          ops/ms
Client.listUser                        thrpt          4.181          ops/ms
Client.createUser                       avgt          3.177           ms/op
Client.existUser                        avgt          1.842           ms/op
Client.getUser                          avgt          3.019           ms/op
Client.listUser                         avgt          7.622           ms/op
Client.createUser                     sample  11220   2.862 ± 0.026   ms/op
Client.createUser:createUser·p0.00    sample          0.813           ms/op
Client.createUser:createUser·p0.50    sample          2.707           ms/op
Client.createUser:createUser·p0.90    sample          3.510           ms/op
Client.createUser:createUser·p0.95    sample          3.854           ms/op
Client.createUser:createUser·p0.99    sample          6.224           ms/op
Client.createUser:createUser·p0.999   sample         11.518           ms/op
Client.createUser:createUser·p0.9999  sample         11.534           ms/op
Client.createUser:createUser·p1.00    sample         11.534           ms/op
Client.existUser                      sample  16629   1.922 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.210           ms/op
Client.existUser:existUser·p0.50      sample          1.860           ms/op
Client.existUser:existUser·p0.90      sample          2.351           ms/op
Client.existUser:existUser·p0.95      sample          2.505           ms/op
Client.existUser:existUser·p0.99      sample          3.572           ms/op
Client.existUser:existUser·p0.999     sample         18.448           ms/op
Client.existUser:existUser·p0.9999    sample         18.645           ms/op
Client.existUser:existUser·p1.00      sample         18.645           ms/op
Client.getUser                        sample  10329   3.111 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.384           ms/op
Client.getUser:getUser·p0.50          sample          3.060           ms/op
Client.getUser:getUser·p0.90          sample          3.887           ms/op
Client.getUser:getUser·p0.95          sample          4.350           ms/op
Client.getUser:getUser·p0.99          sample          5.945           ms/op
Client.getUser:getUser·p0.999         sample          6.455           ms/op
Client.getUser:getUser·p0.9999        sample          9.222           ms/op
Client.getUser:getUser·p1.00          sample          9.257           ms/op
Client.listUser                       sample   3763   8.496 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          2.859           ms/op
Client.listUser:listUser·p0.50        sample          8.135           ms/op
Client.listUser:listUser·p0.90        sample         11.600           ms/op
Client.listUser:listUser·p0.95        sample         12.665           ms/op
Client.listUser:listUser·p0.99        sample         15.778           ms/op
Client.listUser:listUser·p0.999       sample         20.877           ms/op
Client.listUser:listUser·p0.9999      sample         23.134           ms/op
Client.listUser:listUser·p1.00        sample         23.134           ms/op
