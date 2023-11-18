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
# Warmup Iteration   1: 2.502 ops/ms
Iteration   1: 6.514 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.514 ops/ms


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
# Warmup Iteration   1: 6.754 ops/ms
Iteration   1: 14.065 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.065 ops/ms


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
# Warmup Iteration   1: 4.131 ops/ms
Iteration   1: 9.197 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.197 ops/ms


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
# Warmup Iteration   1: 2.318 ops/ms
Iteration   1: 4.201 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.201 ops/ms


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
# Warmup Iteration   1: 5.054 ±(99.9%) 0.099 ms/op
Iteration   1: 3.290 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.290 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.029 ms/op
Iteration   1: 1.818 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.818 ms/op


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
# Warmup Iteration   1: 4.397 ±(99.9%) 0.074 ms/op
Iteration   1: 3.034 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.034 ms/op


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
# Warmup Iteration   1: 10.488 ±(99.9%) 0.191 ms/op
Iteration   1: 7.778 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.778 ms/op


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
# Warmup Iteration   1: 5.041 ±(99.9%) 0.096 ms/op
Iteration   1: 3.157 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   9.675 ms/op
                 createUser·p0.999:  12.544 ms/op
                 createUser·p0.9999: 13.107 ms/op
                 createUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10124
  mean =      3.157 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1427 
    [ 2.500,  3.750) = 7425 
    [ 3.750,  5.000) = 1030 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      9.675 ms/op
     p(99.9000) =     12.544 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     13.107 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


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
# Warmup Iteration   1: 2.827 ±(99.9%) 0.054 ms/op
Iteration   1: 1.723 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.036 ms/op
                 existUser·p0.95:   2.392 ms/op
                 existUser·p0.99:   3.090 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 13.339 ms/op
                 existUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18550
  mean =      1.723 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 337 
    [ 1.250,  2.500) = 17554 
    [ 2.500,  3.750) = 539 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.036 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      3.090 ms/op
     p(99.9000) =     12.583 ms/op
     p(99.9900) =     13.339 ms/op
     p(99.9990) =     13.451 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.083 ms/op
Iteration   1: 2.678 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   6.133 ms/op
                 getUser·p0.999:  15.095 ms/op
                 getUser·p0.9999: 15.382 ms/op
                 getUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11933
  mean =      2.678 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 6165 
    [ 2.500,  3.750) = 5187 
    [ 3.750,  5.000) = 354 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      6.133 ms/op
     p(99.9000) =     15.095 ms/op
     p(99.9900) =     15.382 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 10.832 ±(99.9%) 0.349 ms/op
Iteration   1: 8.379 ±(99.9%) 0.141 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   8.012 ms/op
                 listUser·p0.90:   11.328 ms/op
                 listUser·p0.95:   12.714 ms/op
                 listUser·p0.99:   15.407 ms/op
                 listUser·p0.999:  28.330 ms/op
                 listUser·p0.9999: 30.441 ms/op
                 listUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3885
  mean =      8.379 ±(99.9%) 0.141 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 194 
    [ 5.000,  7.500) = 1344 
    [ 7.500, 10.000) = 1530 
    [10.000, 12.500) = 589 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      8.012 ms/op
     p(90.0000) =     11.328 ms/op
     p(95.0000) =     12.714 ms/op
     p(99.0000) =     15.407 ms/op
     p(99.9000) =     28.330 ms/op
     p(99.9900) =     30.441 ms/op
     p(99.9990) =     30.441 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.514          ops/ms
Client.existUser                       thrpt         14.065          ops/ms
Client.getUser                         thrpt          9.197          ops/ms
Client.listUser                        thrpt          4.201          ops/ms
Client.createUser                       avgt          3.290           ms/op
Client.existUser                        avgt          1.818           ms/op
Client.getUser                          avgt          3.034           ms/op
Client.listUser                         avgt          7.778           ms/op
Client.createUser                     sample  10124   3.157 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.284           ms/op
Client.createUser:createUser·p0.50    sample          2.961           ms/op
Client.createUser:createUser·p0.90    sample          3.842           ms/op
Client.createUser:createUser·p0.95    sample          4.116           ms/op
Client.createUser:createUser·p0.99    sample          9.675           ms/op
Client.createUser:createUser·p0.999   sample         12.544           ms/op
Client.createUser:createUser·p0.9999  sample         13.107           ms/op
Client.createUser:createUser·p1.00    sample         13.107           ms/op
Client.existUser                      sample  18550   1.723 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.594           ms/op
Client.existUser:existUser·p0.50      sample          1.638           ms/op
Client.existUser:existUser·p0.90      sample          2.036           ms/op
Client.existUser:existUser·p0.95      sample          2.392           ms/op
Client.existUser:existUser·p0.99      sample          3.090           ms/op
Client.existUser:existUser·p0.999     sample         12.583           ms/op
Client.existUser:existUser·p0.9999    sample         13.339           ms/op
Client.existUser:existUser·p1.00      sample         13.451           ms/op
Client.getUser                        sample  11933   2.678 ± 0.033   ms/op
Client.getUser:getUser·p0.00          sample          0.669           ms/op
Client.getUser:getUser·p0.50          sample          2.441           ms/op
Client.getUser:getUser·p0.90          sample          3.420           ms/op
Client.getUser:getUser·p0.95          sample          3.719           ms/op
Client.getUser:getUser·p0.99          sample          6.133           ms/op
Client.getUser:getUser·p0.999         sample         15.095           ms/op
Client.getUser:getUser·p0.9999        sample         15.382           ms/op
Client.getUser:getUser·p1.00          sample         15.401           ms/op
Client.listUser                       sample   3885   8.379 ± 0.141   ms/op
Client.listUser:listUser·p0.00        sample          2.363           ms/op
Client.listUser:listUser·p0.50        sample          8.012           ms/op
Client.listUser:listUser·p0.90        sample         11.328           ms/op
Client.listUser:listUser·p0.95        sample         12.714           ms/op
Client.listUser:listUser·p0.99        sample         15.407           ms/op
Client.listUser:listUser·p0.999       sample         28.330           ms/op
Client.listUser:listUser·p0.9999      sample         30.441           ms/op
Client.listUser:listUser·p1.00        sample         30.441           ms/op
