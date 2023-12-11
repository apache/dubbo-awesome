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
# Warmup Iteration   1: 2.213 ops/ms
Iteration   1: 5.666 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.666 ops/ms


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
# Warmup Iteration   1: 5.128 ops/ms
Iteration   1: 12.194 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.194 ops/ms


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
# Warmup Iteration   1: 3.762 ops/ms
Iteration   1: 8.449 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.449 ops/ms


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
# Warmup Iteration   1: 1.961 ops/ms
Iteration   1: 3.486 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.486 ops/ms


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
# Warmup Iteration   1: 6.045 ±(99.9%) 0.104 ms/op
Iteration   1: 3.209 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.209 ms/op


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
# Warmup Iteration   1: 3.137 ±(99.9%) 0.040 ms/op
Iteration   1: 1.920 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.920 ms/op


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.059 ms/op
Iteration   1: 3.140 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.140 ms/op


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
# Warmup Iteration   1: 11.917 ±(99.9%) 0.192 ms/op
Iteration   1: 8.329 ±(99.9%) 0.082 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.329 ms/op


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
# Warmup Iteration   1: 5.148 ±(99.9%) 0.135 ms/op
Iteration   1: 2.929 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.736 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  11.305 ms/op
                 createUser·p0.9999: 11.403 ms/op
                 createUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10916
  mean =      2.929 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 2885 
    [ 2.500,  3.750) = 7053 
    [ 3.750,  5.000) = 625 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.736 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     11.305 ms/op
     p(99.9900) =     11.403 ms/op
     p(99.9990) =     11.403 ms/op
     p(99.9999) =     11.403 ms/op
    p(100.0000) =     11.403 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.075 ms/op
Iteration   1: 1.755 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   1.610 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.757 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  4.963 ms/op
                 existUser·p0.9999: 5.933 ms/op
                 existUser·p1.00:   7.676 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18215
  mean =      1.755 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 125 
    [1.000, 1.500) = 6645 
    [1.500, 2.000) = 7384 
    [2.000, 2.500) = 2335 
    [2.500, 3.000) = 1149 
    [3.000, 3.500) = 289 
    [3.500, 4.000) = 167 
    [4.000, 4.500) = 71 
    [4.500, 5.000) = 39 
    [5.000, 5.500) = 9 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      1.610 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      4.963 ms/op
     p(99.9900) =      5.933 ms/op
     p(99.9990) =      7.676 ms/op
     p(99.9999) =      7.676 ms/op
    p(100.0000) =      7.676 ms/op


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.139 ms/op
Iteration   1: 3.370 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   5.876 ms/op
                 getUser·p0.999:  6.928 ms/op
                 getUser·p0.9999: 11.387 ms/op
                 getUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9484
  mean =      3.370 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1357 
    [ 2.500,  3.750) = 5139 
    [ 3.750,  5.000) = 2534 
    [ 5.000,  6.250) = 414 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      5.876 ms/op
     p(99.9000) =      6.928 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     11.387 ms/op
     p(99.9999) =     11.387 ms/op
    p(100.0000) =     11.387 ms/op


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
# Warmup Iteration   1: 12.299 ±(99.9%) 0.425 ms/op
Iteration   1: 7.802 ±(99.9%) 0.104 ms/op
                 listUser·p0.00:   2.896 ms/op
                 listUser·p0.50:   7.610 ms/op
                 listUser·p0.90:   9.683 ms/op
                 listUser·p0.95:   10.491 ms/op
                 listUser·p0.99:   14.130 ms/op
                 listUser·p0.999:  27.390 ms/op
                 listUser·p0.9999: 28.869 ms/op
                 listUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4093
  mean =      7.802 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 97 
    [ 5.000,  7.500) = 1832 
    [ 7.500, 10.000) = 1849 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.896 ms/op
     p(50.0000) =      7.610 ms/op
     p(90.0000) =      9.683 ms/op
     p(95.0000) =     10.491 ms/op
     p(99.0000) =     14.130 ms/op
     p(99.9000) =     27.390 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.666          ops/ms
Client.existUser                       thrpt         12.194          ops/ms
Client.getUser                         thrpt          8.449          ops/ms
Client.listUser                        thrpt          3.486          ops/ms
Client.createUser                       avgt          3.209           ms/op
Client.existUser                        avgt          1.920           ms/op
Client.getUser                          avgt          3.140           ms/op
Client.listUser                         avgt          8.329           ms/op
Client.createUser                     sample  10916   2.929 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          0.846           ms/op
Client.createUser:createUser·p0.50    sample          2.736           ms/op
Client.createUser:createUser·p0.90    sample          3.641           ms/op
Client.createUser:createUser·p0.95    sample          4.202           ms/op
Client.createUser:createUser·p0.99    sample          8.946           ms/op
Client.createUser:createUser·p0.999   sample         11.305           ms/op
Client.createUser:createUser·p0.9999  sample         11.403           ms/op
Client.createUser:createUser·p1.00    sample         11.403           ms/op
Client.existUser                      sample  18215   1.755 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.693           ms/op
Client.existUser:existUser·p0.50      sample          1.610           ms/op
Client.existUser:existUser·p0.90      sample          2.470           ms/op
Client.existUser:existUser·p0.95      sample          2.757           ms/op
Client.existUser:existUser·p0.99      sample          3.711           ms/op
Client.existUser:existUser·p0.999     sample          4.963           ms/op
Client.existUser:existUser·p0.9999    sample          5.933           ms/op
Client.existUser:existUser·p1.00      sample          7.676           ms/op
Client.getUser                        sample   9484   3.370 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.995           ms/op
Client.getUser:getUser·p0.50          sample          3.289           ms/op
Client.getUser:getUser·p0.90          sample          4.342           ms/op
Client.getUser:getUser·p0.95          sample          4.923           ms/op
Client.getUser:getUser·p0.99          sample          5.876           ms/op
Client.getUser:getUser·p0.999         sample          6.928           ms/op
Client.getUser:getUser·p0.9999        sample         11.387           ms/op
Client.getUser:getUser·p1.00          sample         11.387           ms/op
Client.listUser                       sample   4093   7.802 ± 0.104   ms/op
Client.listUser:listUser·p0.00        sample          2.896           ms/op
Client.listUser:listUser·p0.50        sample          7.610           ms/op
Client.listUser:listUser·p0.90        sample          9.683           ms/op
Client.listUser:listUser·p0.95        sample         10.491           ms/op
Client.listUser:listUser·p0.99        sample         14.130           ms/op
Client.listUser:listUser·p0.999       sample         27.390           ms/op
Client.listUser:listUser·p0.9999      sample         28.869           ms/op
Client.listUser:listUser·p1.00        sample         28.869           ms/op
