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
# Warmup Iteration   1: 2.212 ops/ms
Iteration   1: 5.564 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.564 ops/ms


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
# Warmup Iteration   1: 5.840 ops/ms
Iteration   1: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.288 ops/ms


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
# Warmup Iteration   1: 4.383 ops/ms
Iteration   1: 8.528 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.528 ops/ms


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
# Warmup Iteration   1: 2.006 ops/ms
Iteration   1: 4.031 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.031 ops/ms


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
# Warmup Iteration   1: 5.671 ±(99.9%) 0.086 ms/op
Iteration   1: 2.914 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.914 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.036 ms/op
Iteration   1: 2.081 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.081 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.060 ms/op
Iteration   1: 3.090 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.090 ms/op


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
# Warmup Iteration   1: 11.391 ±(99.9%) 0.215 ms/op
Iteration   1: 7.832 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.832 ms/op


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
# Warmup Iteration   1: 5.285 ±(99.9%) 0.118 ms/op
Iteration   1: 3.042 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   2.892 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.357 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 10.813 ms/op
                 createUser·p1.00:   10.813 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10503
  mean =      3.042 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 110 
    [ 2.000,  3.000) = 6137 
    [ 3.000,  4.000) = 3575 
    [ 4.000,  5.000) = 470 
    [ 5.000,  6.000) = 164 
    [ 6.000,  7.000) = 8 
    [ 7.000,  8.000) = 7 
    [ 8.000,  9.000) = 17 
    [ 9.000, 10.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.357 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     10.813 ms/op
     p(99.9990) =     10.813 ms/op
     p(99.9999) =     10.813 ms/op
    p(100.0000) =     10.813 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.083 ms/op
Iteration   1: 1.859 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   1.733 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.552 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  32.637 ms/op
                 existUser·p0.9999: 32.906 ms/op
                 existUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17224
  mean =      1.859 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16222 
    [ 2.500,  5.000) = 921 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.552 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =     32.637 ms/op
     p(99.9900) =     32.906 ms/op
     p(99.9990) =     33.096 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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
# Warmup Iteration   1: 4.919 ±(99.9%) 0.133 ms/op
Iteration   1: 2.862 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   2.757 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.157 ms/op
                 getUser·p0.999:  7.768 ms/op
                 getUser·p0.9999: 9.990 ms/op
                 getUser·p1.00:   10.158 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11348
  mean =      2.862 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 22 
    [ 1.000,  2.000) = 822 
    [ 2.000,  3.000) = 6334 
    [ 3.000,  4.000) = 3643 
    [ 4.000,  5.000) = 411 
    [ 5.000,  6.000) = 41 
    [ 6.000,  7.000) = 27 
    [ 7.000,  8.000) = 44 
    [ 8.000,  9.000) = 3 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.757 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.157 ms/op
     p(99.9000) =      7.768 ms/op
     p(99.9900) =      9.990 ms/op
     p(99.9990) =     10.158 ms/op
     p(99.9999) =     10.158 ms/op
    p(100.0000) =     10.158 ms/op


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
# Warmup Iteration   1: 12.427 ±(99.9%) 0.436 ms/op
Iteration   1: 7.710 ±(99.9%) 0.098 ms/op
                 listUser·p0.00:   2.953 ms/op
                 listUser·p0.50:   7.438 ms/op
                 listUser·p0.90:   9.798 ms/op
                 listUser·p0.95:   10.846 ms/op
                 listUser·p0.99:   14.137 ms/op
                 listUser·p0.999:  21.703 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4225
  mean =      7.710 ±(99.9%) 0.098 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 148 
    [ 5.000,  7.500) = 2037 
    [ 7.500, 10.000) = 1663 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.953 ms/op
     p(50.0000) =      7.438 ms/op
     p(90.0000) =      9.798 ms/op
     p(95.0000) =     10.846 ms/op
     p(99.0000) =     14.137 ms/op
     p(99.9000) =     21.703 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.564          ops/ms
Client.existUser                       thrpt         10.288          ops/ms
Client.getUser                         thrpt          8.528          ops/ms
Client.listUser                        thrpt          4.031          ops/ms
Client.createUser                       avgt          2.914           ms/op
Client.existUser                        avgt          2.081           ms/op
Client.getUser                          avgt          3.090           ms/op
Client.listUser                         avgt          7.832           ms/op
Client.createUser                     sample  10503   3.042 ± 0.022   ms/op
Client.createUser:createUser·p0.00    sample          1.305           ms/op
Client.createUser:createUser·p0.50    sample          2.892           ms/op
Client.createUser:createUser·p0.90    sample          3.690           ms/op
Client.createUser:createUser·p0.95    sample          4.252           ms/op
Client.createUser:createUser·p0.99    sample          5.357           ms/op
Client.createUser:createUser·p0.999   sample          9.077           ms/op
Client.createUser:createUser·p0.9999  sample         10.813           ms/op
Client.createUser:createUser·p1.00    sample         10.813           ms/op
Client.existUser                      sample  17224   1.859 ± 0.035   ms/op
Client.existUser:existUser·p0.00      sample          0.534           ms/op
Client.existUser:existUser·p0.50      sample          1.733           ms/op
Client.existUser:existUser·p0.90      sample          2.351           ms/op
Client.existUser:existUser·p0.95      sample          2.552           ms/op
Client.existUser:existUser·p0.99      sample          3.842           ms/op
Client.existUser:existUser·p0.999     sample         32.637           ms/op
Client.existUser:existUser·p0.9999    sample         32.906           ms/op
Client.existUser:existUser·p1.00      sample         33.096           ms/op
Client.getUser                        sample  11348   2.862 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.599           ms/op
Client.getUser:getUser·p0.50          sample          2.757           ms/op
Client.getUser:getUser·p0.90          sample          3.695           ms/op
Client.getUser:getUser·p0.95          sample          3.981           ms/op
Client.getUser:getUser·p0.99          sample          5.157           ms/op
Client.getUser:getUser·p0.999         sample          7.768           ms/op
Client.getUser:getUser·p0.9999        sample          9.990           ms/op
Client.getUser:getUser·p1.00          sample         10.158           ms/op
Client.listUser                       sample   4225   7.710 ± 0.098   ms/op
Client.listUser:listUser·p0.00        sample          2.953           ms/op
Client.listUser:listUser·p0.50        sample          7.438           ms/op
Client.listUser:listUser·p0.90        sample          9.798           ms/op
Client.listUser:listUser·p0.95        sample         10.846           ms/op
Client.listUser:listUser·p0.99        sample         14.137           ms/op
Client.listUser:listUser·p0.999       sample         21.703           ms/op
Client.listUser:listUser·p0.9999      sample         22.675           ms/op
Client.listUser:listUser·p1.00        sample         22.675           ms/op
