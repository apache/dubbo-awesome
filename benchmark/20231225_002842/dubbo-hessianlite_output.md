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
# Warmup Iteration   1: 2.389 ops/ms
Iteration   1: 6.161 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.161 ops/ms


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
# Warmup Iteration   1: 5.974 ops/ms
Iteration   1: 13.143 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.143 ops/ms


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
# Warmup Iteration   1: 4.085 ops/ms
Iteration   1: 8.367 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.367 ops/ms


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
# Warmup Iteration   1: 2.179 ops/ms
Iteration   1: 3.070 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.070 ops/ms


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
# Warmup Iteration   1: 5.409 ±(99.9%) 0.053 ms/op
Iteration   1: 3.245 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.245 ms/op


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
# Warmup Iteration   1: 3.414 ±(99.9%) 0.039 ms/op
Iteration   1: 2.120 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.120 ms/op


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
# Warmup Iteration   1: 4.789 ±(99.9%) 0.065 ms/op
Iteration   1: 3.222 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.222 ms/op


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
# Warmup Iteration   1: 13.142 ±(99.9%) 0.267 ms/op
Iteration   1: 8.602 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.602 ms/op


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
# Warmup Iteration   1: 4.964 ±(99.9%) 0.103 ms/op
Iteration   1: 3.066 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   9.629 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 21.680 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10475
  mean =      3.066 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3229 
    [ 2.500,  5.000) = 7044 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      9.629 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     21.680 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 3.038 ±(99.9%) 0.075 ms/op
Iteration   1: 1.680 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   1.595 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.372 ms/op
                 existUser·p0.99:   3.088 ms/op
                 existUser·p0.999:  10.974 ms/op
                 existUser·p0.9999: 11.504 ms/op
                 existUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19112
  mean =      1.680 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2144 
    [ 1.250,  2.500) = 16352 
    [ 2.500,  3.750) = 489 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.595 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      3.088 ms/op
     p(99.9000) =     10.974 ms/op
     p(99.9900) =     11.504 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ±(99.9%) 0.104 ms/op
Iteration   1: 3.204 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.565 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  7.563 ms/op
                 getUser·p0.9999: 11.698 ms/op
                 getUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9974
  mean =      3.204 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1357 
    [ 2.500,  3.750) = 6720 
    [ 3.750,  5.000) = 1659 
    [ 5.000,  6.250) = 190 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.565 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      7.563 ms/op
     p(99.9900) =     11.698 ms/op
     p(99.9990) =     11.698 ms/op
     p(99.9999) =     11.698 ms/op
    p(100.0000) =     11.698 ms/op


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
# Warmup Iteration   1: 11.872 ±(99.9%) 0.384 ms/op
Iteration   1: 8.361 ±(99.9%) 0.153 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   7.840 ms/op
                 listUser·p0.90:   11.303 ms/op
                 listUser·p0.95:   13.430 ms/op
                 listUser·p0.99:   21.429 ms/op
                 listUser·p0.999:  29.790 ms/op
                 listUser·p0.9999: 32.801 ms/op
                 listUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3820
  mean =      8.361 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 148 
    [ 5.000,  7.500) = 1500 
    [ 7.500, 10.000) = 1515 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.931 ms/op
     p(50.0000) =      7.840 ms/op
     p(90.0000) =     11.303 ms/op
     p(95.0000) =     13.430 ms/op
     p(99.0000) =     21.429 ms/op
     p(99.9000) =     29.790 ms/op
     p(99.9900) =     32.801 ms/op
     p(99.9990) =     32.801 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.161          ops/ms
Client.existUser                       thrpt         13.143          ops/ms
Client.getUser                         thrpt          8.367          ops/ms
Client.listUser                        thrpt          3.070          ops/ms
Client.createUser                       avgt          3.245           ms/op
Client.existUser                        avgt          2.120           ms/op
Client.getUser                          avgt          3.222           ms/op
Client.listUser                         avgt          8.602           ms/op
Client.createUser                     sample  10475   3.066 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          0.908           ms/op
Client.createUser:createUser·p0.50    sample          2.900           ms/op
Client.createUser:createUser·p0.90    sample          3.846           ms/op
Client.createUser:createUser·p0.95    sample          4.133           ms/op
Client.createUser:createUser·p0.99    sample          9.629           ms/op
Client.createUser:createUser·p0.999   sample         19.431           ms/op
Client.createUser:createUser·p0.9999  sample         21.680           ms/op
Client.createUser:createUser·p1.00    sample         21.725           ms/op
Client.existUser                      sample  19112   1.680 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.526           ms/op
Client.existUser:existUser·p0.50      sample          1.595           ms/op
Client.existUser:existUser·p0.90      sample          2.191           ms/op
Client.existUser:existUser·p0.95      sample          2.372           ms/op
Client.existUser:existUser·p0.99      sample          3.088           ms/op
Client.existUser:existUser·p0.999     sample         10.974           ms/op
Client.existUser:existUser·p0.9999    sample         11.504           ms/op
Client.existUser:existUser·p1.00      sample         11.534           ms/op
Client.getUser                        sample   9974   3.204 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.691           ms/op
Client.getUser:getUser·p0.50          sample          3.092           ms/op
Client.getUser:getUser·p0.90          sample          4.063           ms/op
Client.getUser:getUser·p0.95          sample          4.565           ms/op
Client.getUser:getUser·p0.99          sample          5.628           ms/op
Client.getUser:getUser·p0.999         sample          7.563           ms/op
Client.getUser:getUser·p0.9999        sample         11.698           ms/op
Client.getUser:getUser·p1.00          sample         11.698           ms/op
Client.listUser                       sample   3820   8.361 ± 0.153   ms/op
Client.listUser:listUser·p0.00        sample          1.931           ms/op
Client.listUser:listUser·p0.50        sample          7.840           ms/op
Client.listUser:listUser·p0.90        sample         11.303           ms/op
Client.listUser:listUser·p0.95        sample         13.430           ms/op
Client.listUser:listUser·p0.99        sample         21.429           ms/op
Client.listUser:listUser·p0.999       sample         29.790           ms/op
Client.listUser:listUser·p0.9999      sample         32.801           ms/op
Client.listUser:listUser·p1.00        sample         32.801           ms/op
