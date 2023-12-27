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
# Warmup Iteration   1: 2.508 ops/ms
Iteration   1: 5.292 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.292 ops/ms


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
# Warmup Iteration   1: 5.891 ops/ms
Iteration   1: 12.623 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.623 ops/ms


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
# Warmup Iteration   1: 4.831 ops/ms
Iteration   1: 8.883 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.883 ops/ms


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
# Warmup Iteration   1: 2.161 ops/ms
Iteration   1: 3.803 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.803 ops/ms


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
# Warmup Iteration   1: 6.036 ±(99.9%) 0.099 ms/op
Iteration   1: 3.212 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.212 ms/op


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
# Warmup Iteration   1: 3.030 ±(99.9%) 0.034 ms/op
Iteration   1: 1.863 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.863 ms/op


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.085 ms/op
Iteration   1: 3.192 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.192 ms/op


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
# Warmup Iteration   1: 11.427 ±(99.9%) 0.199 ms/op
Iteration   1: 8.970 ±(99.9%) 0.154 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.970 ms/op


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
# Warmup Iteration   1: 5.117 ±(99.9%) 0.101 ms/op
Iteration   1: 3.210 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   8.652 ms/op
                 createUser·p0.999:  13.192 ms/op
                 createUser·p0.9999: 13.369 ms/op
                 createUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9917
  mean =      3.210 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1528 
    [ 2.500,  3.750) = 6996 
    [ 3.750,  5.000) = 1156 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      8.652 ms/op
     p(99.9000) =     13.192 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     13.369 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.085 ms/op
Iteration   1: 1.727 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.233 ms/op
                 existUser·p0.50:   1.518 ms/op
                 existUser·p0.90:   2.497 ms/op
                 existUser·p0.95:   2.731 ms/op
                 existUser·p0.99:   3.117 ms/op
                 existUser·p0.999:  15.802 ms/op
                 existUser·p0.9999: 17.850 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18502
  mean =      1.727 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1924 
    [ 1.250,  2.500) = 14743 
    [ 2.500,  3.750) = 1787 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.233 ms/op
     p(50.0000) =      1.518 ms/op
     p(90.0000) =      2.497 ms/op
     p(95.0000) =      2.731 ms/op
     p(99.0000) =      3.117 ms/op
     p(99.9000) =     15.802 ms/op
     p(99.9900) =     17.850 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.104 ms/op
Iteration   1: 3.398 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.045 ms/op
                 getUser·p0.999:  25.068 ms/op
                 getUser·p0.9999: 26.477 ms/op
                 getUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9408
  mean =      3.398 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1154 
    [ 2.500,  5.000) = 7883 
    [ 5.000,  7.500) = 337 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.045 ms/op
     p(99.9000) =     25.068 ms/op
     p(99.9900) =     26.477 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 12.447 ±(99.9%) 0.436 ms/op
Iteration   1: 8.146 ±(99.9%) 0.097 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   8.012 ms/op
                 listUser·p0.90:   10.692 ms/op
                 listUser·p0.95:   11.452 ms/op
                 listUser·p0.99:   13.500 ms/op
                 listUser·p0.999:  17.014 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3943
  mean =      8.146 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 95 
    [ 5.000,  7.500) = 1364 
    [ 7.500, 10.000) = 1902 
    [10.000, 12.500) = 509 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      8.012 ms/op
     p(90.0000) =     10.692 ms/op
     p(95.0000) =     11.452 ms/op
     p(99.0000) =     13.500 ms/op
     p(99.9000) =     17.014 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.292          ops/ms
Client.existUser                       thrpt         12.623          ops/ms
Client.getUser                         thrpt          8.883          ops/ms
Client.listUser                        thrpt          3.803          ops/ms
Client.createUser                       avgt          3.212           ms/op
Client.existUser                        avgt          1.863           ms/op
Client.getUser                          avgt          3.192           ms/op
Client.listUser                         avgt          8.970           ms/op
Client.createUser                     sample   9917   3.210 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          0.871           ms/op
Client.createUser:createUser·p0.50    sample          3.150           ms/op
Client.createUser:createUser·p0.90    sample          3.858           ms/op
Client.createUser:createUser·p0.95    sample          4.178           ms/op
Client.createUser:createUser·p0.99    sample          8.652           ms/op
Client.createUser:createUser·p0.999   sample         13.192           ms/op
Client.createUser:createUser·p0.9999  sample         13.369           ms/op
Client.createUser:createUser·p1.00    sample         13.369           ms/op
Client.existUser                      sample  18502   1.727 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.233           ms/op
Client.existUser:existUser·p0.50      sample          1.518           ms/op
Client.existUser:existUser·p0.90      sample          2.497           ms/op
Client.existUser:existUser·p0.95      sample          2.731           ms/op
Client.existUser:existUser·p0.99      sample          3.117           ms/op
Client.existUser:existUser·p0.999     sample         15.802           ms/op
Client.existUser:existUser·p0.9999    sample         17.850           ms/op
Client.existUser:existUser·p1.00      sample         17.990           ms/op
Client.getUser                        sample   9408   3.398 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample          1.303           ms/op
Client.getUser:getUser·p0.50          sample          3.236           ms/op
Client.getUser:getUser·p0.90          sample          4.358           ms/op
Client.getUser:getUser·p0.95          sample          4.801           ms/op
Client.getUser:getUser·p0.99          sample          6.045           ms/op
Client.getUser:getUser·p0.999         sample         25.068           ms/op
Client.getUser:getUser·p0.9999        sample         26.477           ms/op
Client.getUser:getUser·p1.00          sample         26.477           ms/op
Client.listUser                       sample   3943   8.146 ± 0.097   ms/op
Client.listUser:listUser·p0.00        sample          1.853           ms/op
Client.listUser:listUser·p0.50        sample          8.012           ms/op
Client.listUser:listUser·p0.90        sample         10.692           ms/op
Client.listUser:listUser·p0.95        sample         11.452           ms/op
Client.listUser:listUser·p0.99        sample         13.500           ms/op
Client.listUser:listUser·p0.999       sample         17.014           ms/op
Client.listUser:listUser·p0.9999      sample         20.382           ms/op
Client.listUser:listUser·p1.00        sample         20.382           ms/op
