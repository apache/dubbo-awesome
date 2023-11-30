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
# Warmup Iteration   1: 2.309 ops/ms
Iteration   1: 5.577 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.577 ops/ms


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
# Warmup Iteration   1: 6.619 ops/ms
Iteration   1: 13.551 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.551 ops/ms


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
# Warmup Iteration   1: 4.453 ops/ms
Iteration   1: 7.480 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.480 ops/ms


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
# Warmup Iteration   1: 2.376 ops/ms
Iteration   1: 3.808 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.808 ops/ms


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
# Warmup Iteration   1: 5.431 ±(99.9%) 0.064 ms/op
Iteration   1: 2.958 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.958 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.032 ms/op
Iteration   1: 1.777 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.777 ms/op


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
# Warmup Iteration   1: 4.877 ±(99.9%) 0.065 ms/op
Iteration   1: 3.235 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.235 ms/op


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
# Warmup Iteration   1: 11.401 ±(99.9%) 0.166 ms/op
Iteration   1: 7.492 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.492 ms/op


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
# Warmup Iteration   1: 4.990 ±(99.9%) 0.109 ms/op
Iteration   1: 3.056 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  15.663 ms/op
                 createUser·p0.9999: 15.892 ms/op
                 createUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10453
  mean =      3.056 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 2879 
    [ 2.500,  3.750) = 5970 
    [ 3.750,  5.000) = 1520 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     15.892 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.083 ±(99.9%) 0.072 ms/op
Iteration   1: 1.736 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.421 ms/op
                 existUser·p0.99:   3.754 ms/op
                 existUser·p0.999:  13.943 ms/op
                 existUser·p0.9999: 14.576 ms/op
                 existUser·p1.00:   14.631 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18414
  mean =      1.736 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 722 
    [ 1.250,  2.500) = 16932 
    [ 2.500,  3.750) = 576 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      3.754 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     14.576 ms/op
     p(99.9990) =     14.631 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.096 ms/op
Iteration   1: 3.133 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  21.402 ms/op
                 getUser·p0.9999: 22.734 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10217
  mean =      3.133 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1987 
    [ 2.500,  5.000) = 7918 
    [ 5.000,  7.500) = 278 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     21.402 ms/op
     p(99.9900) =     22.734 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 11.203 ±(99.9%) 0.486 ms/op
Iteration   1: 7.432 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   7.119 ms/op
                 listUser·p0.90:   9.568 ms/op
                 listUser·p0.95:   10.732 ms/op
                 listUser·p0.99:   15.122 ms/op
                 listUser·p0.999:  30.130 ms/op
                 listUser·p0.9999: 38.273 ms/op
                 listUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4374
  mean =      7.432 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 312 
    [ 5.000,  7.500) = 2266 
    [ 7.500, 10.000) = 1455 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.802 ms/op
     p(50.0000) =      7.119 ms/op
     p(90.0000) =      9.568 ms/op
     p(95.0000) =     10.732 ms/op
     p(99.0000) =     15.122 ms/op
     p(99.9000) =     30.130 ms/op
     p(99.9900) =     38.273 ms/op
     p(99.9990) =     38.273 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.577          ops/ms
Client.existUser                       thrpt         13.551          ops/ms
Client.getUser                         thrpt          7.480          ops/ms
Client.listUser                        thrpt          3.808          ops/ms
Client.createUser                       avgt          2.958           ms/op
Client.existUser                        avgt          1.777           ms/op
Client.getUser                          avgt          3.235           ms/op
Client.listUser                         avgt          7.492           ms/op
Client.createUser                     sample  10453   3.056 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.079           ms/op
Client.createUser:createUser·p0.50    sample          2.970           ms/op
Client.createUser:createUser·p0.90    sample          4.039           ms/op
Client.createUser:createUser·p0.95    sample          4.301           ms/op
Client.createUser:createUser·p0.99    sample          4.817           ms/op
Client.createUser:createUser·p0.999   sample         15.663           ms/op
Client.createUser:createUser·p0.9999  sample         15.892           ms/op
Client.createUser:createUser·p1.00    sample         15.892           ms/op
Client.existUser                      sample  18414   1.736 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.634           ms/op
Client.existUser:existUser·p0.50      sample          1.597           ms/op
Client.existUser:existUser·p0.90      sample          2.183           ms/op
Client.existUser:existUser·p0.95      sample          2.421           ms/op
Client.existUser:existUser·p0.99      sample          3.754           ms/op
Client.existUser:existUser·p0.999     sample         13.943           ms/op
Client.existUser:existUser·p0.9999    sample         14.576           ms/op
Client.existUser:existUser·p1.00      sample         14.631           ms/op
Client.getUser                        sample  10217   3.133 ± 0.040   ms/op
Client.getUser:getUser·p0.00          sample          0.782           ms/op
Client.getUser:getUser·p0.50          sample          3.047           ms/op
Client.getUser:getUser·p0.90          sample          3.772           ms/op
Client.getUser:getUser·p0.95          sample          4.260           ms/op
Client.getUser:getUser·p0.99          sample          6.005           ms/op
Client.getUser:getUser·p0.999         sample         21.402           ms/op
Client.getUser:getUser·p0.9999        sample         22.734           ms/op
Client.getUser:getUser·p1.00          sample         22.741           ms/op
Client.listUser                       sample   4374   7.432 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          1.802           ms/op
Client.listUser:listUser·p0.50        sample          7.119           ms/op
Client.listUser:listUser·p0.90        sample          9.568           ms/op
Client.listUser:listUser·p0.95        sample         10.732           ms/op
Client.listUser:listUser·p0.99        sample         15.122           ms/op
Client.listUser:listUser·p0.999       sample         30.130           ms/op
Client.listUser:listUser·p0.9999      sample         38.273           ms/op
Client.listUser:listUser·p1.00        sample         38.273           ms/op
