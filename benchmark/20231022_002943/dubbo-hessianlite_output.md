# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.369 ops/ms
Iteration   1: 4.380 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.380 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.289 ops/ms
Iteration   1: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.615 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.665 ops/ms
Iteration   1: 6.072 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.072 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.306 ops/ms
Iteration   1: 1.933 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.933 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.159 ±(99.9%) 0.111 ms/op
Iteration   1: 3.404 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.404 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.032 ±(99.9%) 0.084 ms/op
Iteration   1: 2.429 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.429 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.248 ±(99.9%) 0.142 ms/op
Iteration   1: 3.561 ±(99.9%) 0.125 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.561 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 23.527 ±(99.9%) 0.506 ms/op
Iteration   1: 14.969 ±(99.9%) 0.255 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  14.969 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.020 ±(99.9%) 0.402 ms/op
Iteration   1: 3.965 ±(99.9%) 0.093 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   6.144 ms/op
                 createUser·p0.95:   9.306 ms/op
                 createUser·p0.99:   17.317 ms/op
                 createUser·p0.999:  24.835 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8087
  mean =      3.965 ±(99.9%) 0.093 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 698 
    [ 2.500,  5.000) = 6068 
    [ 5.000,  7.500) = 839 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      9.306 ms/op
     p(99.0000) =     17.317 ms/op
     p(99.9000) =     24.835 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.152 ms/op
Iteration   1: 1.691 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   1.331 ms/op
                 existUser·p0.90:   1.931 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   9.617 ms/op
                 existUser·p0.999:  13.779 ms/op
                 existUser·p0.9999: 14.339 ms/op
                 existUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19019
  mean =      1.691 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3759 
    [ 1.250,  2.500) = 14064 
    [ 2.500,  3.750) = 274 
    [ 3.750,  5.000) = 246 
    [ 5.000,  6.250) = 190 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 146 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.331 ms/op
     p(90.0000) =      1.931 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     14.339 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 8.036 ±(99.9%) 0.222 ms/op
Iteration   1: 3.075 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.773 ms/op
                 getUser·p0.90:   3.749 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   11.767 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 18.896 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10376
  mean =      3.075 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 2459 
    [ 2.500,  3.750) = 6871 
    [ 3.750,  5.000) = 545 
    [ 5.000,  6.250) = 188 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.749 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =     11.767 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     18.896 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 21.596 ±(99.9%) 0.932 ms/op
Iteration   1: 13.647 ±(99.9%) 0.252 ms/op
                 listUser·p0.00:   4.956 ms/op
                 listUser·p0.50:   13.337 ms/op
                 listUser·p0.90:   18.481 ms/op
                 listUser·p0.95:   20.644 ms/op
                 listUser·p0.99:   23.374 ms/op
                 listUser·p0.999:  32.066 ms/op
                 listUser·p0.9999: 33.554 ms/op
                 listUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2366
  mean =     13.647 ±(99.9%) 0.252 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 255 
    [10.000, 12.500) = 630 
    [12.500, 15.000) = 661 
    [15.000, 17.500) = 406 
    [17.500, 20.000) = 184 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      4.956 ms/op
     p(50.0000) =     13.337 ms/op
     p(90.0000) =     18.481 ms/op
     p(95.0000) =     20.644 ms/op
     p(99.0000) =     23.374 ms/op
     p(99.9000) =     32.066 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.380          ops/ms
Client.existUser                       thrpt         10.615          ops/ms
Client.getUser                         thrpt          6.072          ops/ms
Client.listUser                        thrpt          1.933          ops/ms
Client.createUser                       avgt          3.404           ms/op
Client.existUser                        avgt          2.429           ms/op
Client.getUser                          avgt          3.561           ms/op
Client.listUser                         avgt         14.969           ms/op
Client.createUser                     sample   8087   3.965 ± 0.093   ms/op
Client.createUser:createUser·p0.00    sample          1.538           ms/op
Client.createUser:createUser·p0.50    sample          3.092           ms/op
Client.createUser:createUser·p0.90    sample          6.144           ms/op
Client.createUser:createUser·p0.95    sample          9.306           ms/op
Client.createUser:createUser·p0.99    sample         17.317           ms/op
Client.createUser:createUser·p0.999   sample         24.835           ms/op
Client.createUser:createUser·p0.9999  sample         29.295           ms/op
Client.createUser:createUser·p1.00    sample         29.295           ms/op
Client.existUser                      sample  19019   1.691 ± 0.033   ms/op
Client.existUser:existUser·p0.00      sample          0.555           ms/op
Client.existUser:existUser·p0.50      sample          1.331           ms/op
Client.existUser:existUser·p0.90      sample          1.931           ms/op
Client.existUser:existUser·p0.95      sample          3.482           ms/op
Client.existUser:existUser·p0.99      sample          9.617           ms/op
Client.existUser:existUser·p0.999     sample         13.779           ms/op
Client.existUser:existUser·p0.9999    sample         14.339           ms/op
Client.existUser:existUser·p1.00      sample         14.369           ms/op
Client.getUser                        sample  10376   3.075 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample          0.967           ms/op
Client.getUser:getUser·p0.50          sample          2.773           ms/op
Client.getUser:getUser·p0.90          sample          3.749           ms/op
Client.getUser:getUser·p0.95          sample          4.923           ms/op
Client.getUser:getUser·p0.99          sample         11.767           ms/op
Client.getUser:getUser·p0.999         sample         18.055           ms/op
Client.getUser:getUser·p0.9999        sample         18.896           ms/op
Client.getUser:getUser·p1.00          sample         18.907           ms/op
Client.listUser                       sample   2366  13.647 ± 0.252   ms/op
Client.listUser:listUser·p0.00        sample          4.956           ms/op
Client.listUser:listUser·p0.50        sample         13.337           ms/op
Client.listUser:listUser·p0.90        sample         18.481           ms/op
Client.listUser:listUser·p0.95        sample         20.644           ms/op
Client.listUser:listUser·p0.99        sample         23.374           ms/op
Client.listUser:listUser·p0.999       sample         32.066           ms/op
Client.listUser:listUser·p0.9999      sample         33.554           ms/op
Client.listUser:listUser·p1.00        sample         33.554           ms/op
