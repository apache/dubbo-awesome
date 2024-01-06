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
# Warmup Iteration   1: 2.268 ops/ms
Iteration   1: 7.307 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.307 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.448 ops/ms
Iteration   1: 13.386 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.386 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 5.016 ops/ms
Iteration   1: 9.727 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.727 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.230 ops/ms
Iteration   1: 3.759 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.759 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.483 ±(99.9%) 0.080 ms/op
Iteration   1: 3.194 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.194 ms/op


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
# Warmup Iteration   1: 3.180 ±(99.9%) 0.030 ms/op
Iteration   1: 2.012 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.012 ms/op


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.052 ms/op
Iteration   1: 3.605 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.605 ms/op


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
# Warmup Iteration   1: 12.059 ±(99.9%) 0.323 ms/op
Iteration   1: 8.004 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.004 ms/op


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.123 ms/op
Iteration   1: 2.788 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  18.776 ms/op
                 createUser·p0.9999: 20.690 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11462
  mean =      2.788 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4900 
    [ 2.500,  5.000) = 6348 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     20.690 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 2.909 ±(99.9%) 0.069 ms/op
Iteration   1: 1.883 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.080 ms/op
                 existUser·p0.999:  17.203 ms/op
                 existUser·p0.9999: 18.205 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17102
  mean =      1.883 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 569 
    [ 1.250,  2.500) = 15537 
    [ 2.500,  3.750) = 877 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.080 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     18.205 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 4.427 ±(99.9%) 0.094 ms/op
Iteration   1: 2.771 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   2.691 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.592 ms/op
                 getUser·p0.999:  8.478 ms/op
                 getUser·p0.9999: 8.831 ms/op
                 getUser·p1.00:   8.831 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11548
  mean =      2.771 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 68 
    [1.500, 2.000) = 703 
    [2.000, 2.500) = 3455 
    [2.500, 3.000) = 3726 
    [3.000, 3.500) = 2400 
    [3.500, 4.000) = 900 
    [4.000, 4.500) = 163 
    [4.500, 5.000) = 53 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 29 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 7 
    [8.000, 8.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.691 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.592 ms/op
     p(99.9000) =      8.478 ms/op
     p(99.9900) =      8.831 ms/op
     p(99.9990) =      8.831 ms/op
     p(99.9999) =      8.831 ms/op
    p(100.0000) =      8.831 ms/op


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
# Warmup Iteration   1: 11.750 ±(99.9%) 0.366 ms/op
Iteration   1: 7.439 ±(99.9%) 0.111 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   7.070 ms/op
                 listUser·p0.90:   9.699 ms/op
                 listUser·p0.95:   10.830 ms/op
                 listUser·p0.99:   18.437 ms/op
                 listUser·p0.999:  24.005 ms/op
                 listUser·p0.9999: 26.444 ms/op
                 listUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4416
  mean =      7.439 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 218 
    [ 5.000,  7.500) = 2467 
    [ 7.500, 10.000) = 1365 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.601 ms/op
     p(50.0000) =      7.070 ms/op
     p(90.0000) =      9.699 ms/op
     p(95.0000) =     10.830 ms/op
     p(99.0000) =     18.437 ms/op
     p(99.9000) =     24.005 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          7.307          ops/ms
Client.existUser                       thrpt         13.386          ops/ms
Client.getUser                         thrpt          9.727          ops/ms
Client.listUser                        thrpt          3.759          ops/ms
Client.createUser                       avgt          3.194           ms/op
Client.existUser                        avgt          2.012           ms/op
Client.getUser                          avgt          3.605           ms/op
Client.listUser                         avgt          8.004           ms/op
Client.createUser                     sample  11462   2.788 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          0.802           ms/op
Client.createUser:createUser·p0.50    sample          2.572           ms/op
Client.createUser:createUser·p0.90    sample          3.506           ms/op
Client.createUser:createUser·p0.95    sample          4.166           ms/op
Client.createUser:createUser·p0.99    sample          7.594           ms/op
Client.createUser:createUser·p0.999   sample         18.776           ms/op
Client.createUser:createUser·p0.9999  sample         20.690           ms/op
Client.createUser:createUser·p1.00    sample         20.709           ms/op
Client.existUser                      sample  17102   1.883 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.590           ms/op
Client.existUser:existUser·p0.50      sample          1.806           ms/op
Client.existUser:existUser·p0.90      sample          2.388           ms/op
Client.existUser:existUser·p0.95      sample          2.523           ms/op
Client.existUser:existUser·p0.99      sample          3.080           ms/op
Client.existUser:existUser·p0.999     sample         17.203           ms/op
Client.existUser:existUser·p0.9999    sample         18.205           ms/op
Client.existUser:existUser·p1.00      sample         18.252           ms/op
Client.getUser                        sample  11548   2.771 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.855           ms/op
Client.getUser:getUser·p0.50          sample          2.691           ms/op
Client.getUser:getUser·p0.90          sample          3.514           ms/op
Client.getUser:getUser·p0.95          sample          3.740           ms/op
Client.getUser:getUser·p0.99          sample          4.592           ms/op
Client.getUser:getUser·p0.999         sample          8.478           ms/op
Client.getUser:getUser·p0.9999        sample          8.831           ms/op
Client.getUser:getUser·p1.00          sample          8.831           ms/op
Client.listUser                       sample   4416   7.439 ± 0.111   ms/op
Client.listUser:listUser·p0.00        sample          2.601           ms/op
Client.listUser:listUser·p0.50        sample          7.070           ms/op
Client.listUser:listUser·p0.90        sample          9.699           ms/op
Client.listUser:listUser·p0.95        sample         10.830           ms/op
Client.listUser:listUser·p0.99        sample         18.437           ms/op
Client.listUser:listUser·p0.999       sample         24.005           ms/op
Client.listUser:listUser·p0.9999      sample         26.444           ms/op
Client.listUser:listUser·p1.00        sample         26.444           ms/op
