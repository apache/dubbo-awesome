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
# Warmup Iteration   1: 2.222 ops/ms
Iteration   1: 6.005 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.005 ops/ms


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
# Warmup Iteration   1: 6.064 ops/ms
Iteration   1: 13.619 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.619 ops/ms


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
# Warmup Iteration   1: 4.343 ops/ms
Iteration   1: 8.436 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.436 ops/ms


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
# Warmup Iteration   1: 1.984 ops/ms
Iteration   1: 3.296 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.296 ops/ms


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
# Warmup Iteration   1: 6.291 ±(99.9%) 0.097 ms/op
Iteration   1: 3.010 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.010 ms/op


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
# Warmup Iteration   1: 2.956 ±(99.9%) 0.028 ms/op
Iteration   1: 1.980 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.980 ms/op


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
# Warmup Iteration   1: 5.139 ±(99.9%) 0.055 ms/op
Iteration   1: 3.072 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.072 ms/op


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
# Warmup Iteration   1: 13.020 ±(99.9%) 0.304 ms/op
Iteration   1: 8.957 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.957 ms/op


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
# Warmup Iteration   1: 5.691 ±(99.9%) 0.159 ms/op
Iteration   1: 3.239 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   10.604 ms/op
                 createUser·p0.999:  15.206 ms/op
                 createUser·p0.9999: 15.974 ms/op
                 createUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9879
  mean =      3.239 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 1418 
    [ 2.500,  3.750) = 7028 
    [ 3.750,  5.000) = 1108 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =     10.604 ms/op
     p(99.9000) =     15.206 ms/op
     p(99.9900) =     15.974 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.078 ms/op
Iteration   1: 1.840 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.264 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.482 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  4.952 ms/op
                 existUser·p0.9999: 5.706 ms/op
                 existUser·p1.00:   6.742 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17482
  mean =      1.840 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 4 
    [0.500, 1.000) = 53 
    [1.000, 1.500) = 2523 
    [1.500, 2.000) = 10939 
    [2.000, 2.500) = 2267 
    [2.500, 3.000) = 1136 
    [3.000, 3.500) = 381 
    [3.500, 4.000) = 98 
    [4.000, 4.500) = 21 
    [4.500, 5.000) = 48 
    [5.000, 5.500) = 11 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.264 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =      4.952 ms/op
     p(99.9900) =      5.706 ms/op
     p(99.9990) =      6.742 ms/op
     p(99.9999) =      6.742 ms/op
    p(100.0000) =      6.742 ms/op


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.103 ms/op
Iteration   1: 3.124 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   2.798 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.739 ms/op
                 getUser·p0.99:   7.320 ms/op
                 getUser·p0.999:  21.155 ms/op
                 getUser·p0.9999: 21.496 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10409
  mean =      3.124 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1940 
    [ 2.500,  5.000) = 8040 
    [ 5.000,  7.500) = 328 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.739 ms/op
     p(99.0000) =      7.320 ms/op
     p(99.9000) =     21.155 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 12.581 ±(99.9%) 0.382 ms/op
Iteration   1: 8.790 ±(99.9%) 0.135 ms/op
                 listUser·p0.00:   1.858 ms/op
                 listUser·p0.50:   8.331 ms/op
                 listUser·p0.90:   11.764 ms/op
                 listUser·p0.95:   13.009 ms/op
                 listUser·p0.99:   19.245 ms/op
                 listUser·p0.999:  23.834 ms/op
                 listUser·p0.9999: 27.886 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3653
  mean =      8.790 ±(99.9%) 0.135 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 45 
    [ 5.000,  7.500) = 1047 
    [ 7.500, 10.000) = 1796 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      8.331 ms/op
     p(90.0000) =     11.764 ms/op
     p(95.0000) =     13.009 ms/op
     p(99.0000) =     19.245 ms/op
     p(99.9000) =     23.834 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.005          ops/ms
Client.existUser                       thrpt         13.619          ops/ms
Client.getUser                         thrpt          8.436          ops/ms
Client.listUser                        thrpt          3.296          ops/ms
Client.createUser                       avgt          3.010           ms/op
Client.existUser                        avgt          1.980           ms/op
Client.getUser                          avgt          3.072           ms/op
Client.listUser                         avgt          8.957           ms/op
Client.createUser                     sample   9879   3.239 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          0.784           ms/op
Client.createUser:createUser·p0.50    sample          3.072           ms/op
Client.createUser:createUser·p0.90    sample          3.977           ms/op
Client.createUser:createUser·p0.95    sample          4.547           ms/op
Client.createUser:createUser·p0.99    sample         10.604           ms/op
Client.createUser:createUser·p0.999   sample         15.206           ms/op
Client.createUser:createUser·p0.9999  sample         15.974           ms/op
Client.createUser:createUser·p1.00    sample         15.974           ms/op
Client.existUser                      sample  17482   1.840 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.264           ms/op
Client.existUser:existUser·p0.50      sample          1.702           ms/op
Client.existUser:existUser·p0.90      sample          2.482           ms/op
Client.existUser:existUser·p0.95      sample          2.802           ms/op
Client.existUser:existUser·p0.99      sample          3.523           ms/op
Client.existUser:existUser·p0.999     sample          4.952           ms/op
Client.existUser:existUser·p0.9999    sample          5.706           ms/op
Client.existUser:existUser·p1.00      sample          6.742           ms/op
Client.getUser                        sample  10409   3.124 ± 0.041   ms/op
Client.getUser:getUser·p0.00          sample          1.319           ms/op
Client.getUser:getUser·p0.50          sample          2.798           ms/op
Client.getUser:getUser·p0.90          sample          4.030           ms/op
Client.getUser:getUser·p0.95          sample          4.739           ms/op
Client.getUser:getUser·p0.99          sample          7.320           ms/op
Client.getUser:getUser·p0.999         sample         21.155           ms/op
Client.getUser:getUser·p0.9999        sample         21.496           ms/op
Client.getUser:getUser·p1.00          sample         21.496           ms/op
Client.listUser                       sample   3653   8.790 ± 0.135   ms/op
Client.listUser:listUser·p0.00        sample          1.858           ms/op
Client.listUser:listUser·p0.50        sample          8.331           ms/op
Client.listUser:listUser·p0.90        sample         11.764           ms/op
Client.listUser:listUser·p0.95        sample         13.009           ms/op
Client.listUser:listUser·p0.99        sample         19.245           ms/op
Client.listUser:listUser·p0.999       sample         23.834           ms/op
Client.listUser:listUser·p0.9999      sample         27.886           ms/op
Client.listUser:listUser·p1.00        sample         27.886           ms/op
