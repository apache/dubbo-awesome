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
# Warmup Iteration   1: 2.575 ops/ms
Iteration   1: 5.999 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.999 ops/ms


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
# Warmup Iteration   1: 5.975 ops/ms
Iteration   1: 10.269 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.269 ops/ms


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
# Warmup Iteration   1: 4.098 ops/ms
Iteration   1: 8.967 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.967 ops/ms


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
# Warmup Iteration   1: 2.021 ops/ms
Iteration   1: 3.328 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.328 ops/ms


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
# Warmup Iteration   1: 5.782 ±(99.9%) 0.074 ms/op
Iteration   1: 3.001 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.001 ms/op


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
# Warmup Iteration   1: 3.218 ±(99.9%) 0.031 ms/op
Iteration   1: 1.815 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.815 ms/op


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
# Warmup Iteration   1: 5.058 ±(99.9%) 0.064 ms/op
Iteration   1: 3.164 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.164 ms/op


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
# Warmup Iteration   1: 13.944 ±(99.9%) 0.242 ms/op
Iteration   1: 9.715 ±(99.9%) 0.110 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.715 ms/op


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
# Warmup Iteration   1: 5.063 ±(99.9%) 0.119 ms/op
Iteration   1: 3.102 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   2.785 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   11.539 ms/op
                 createUser·p0.999:  16.105 ms/op
                 createUser·p0.9999: 16.236 ms/op
                 createUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10370
  mean =      3.102 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1730 
    [ 2.500,  3.750) = 7424 
    [ 3.750,  5.000) = 923 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =     11.539 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     16.236 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 2.793 ±(99.9%) 0.053 ms/op
Iteration   1: 1.646 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   1.552 ms/op
                 existUser·p0.90:   2.025 ms/op
                 existUser·p0.95:   2.167 ms/op
                 existUser·p0.99:   2.802 ms/op
                 existUser·p0.999:  17.280 ms/op
                 existUser·p0.9999: 18.591 ms/op
                 existUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19416
  mean =      1.646 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1771 
    [ 1.250,  2.500) = 17344 
    [ 2.500,  3.750) = 227 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      1.552 ms/op
     p(90.0000) =      2.025 ms/op
     p(95.0000) =      2.167 ms/op
     p(99.0000) =      2.802 ms/op
     p(99.9000) =     17.280 ms/op
     p(99.9900) =     18.591 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 5.458 ±(99.9%) 0.430 ms/op
Iteration   1: 3.304 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.021 ms/op
                 getUser·p0.95:   4.283 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  10.724 ms/op
                 getUser·p0.9999: 11.158 ms/op
                 getUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9683
  mean =      3.304 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 298 
    [ 2.000,  3.000) = 2962 
    [ 3.000,  4.000) = 5387 
    [ 4.000,  5.000) = 762 
    [ 5.000,  6.000) = 165 
    [ 6.000,  7.000) = 56 
    [ 7.000,  8.000) = 19 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 6 
    [10.000, 11.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.021 ms/op
     p(95.0000) =      4.283 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     10.724 ms/op
     p(99.9900) =     11.158 ms/op
     p(99.9990) =     11.158 ms/op
     p(99.9999) =     11.158 ms/op
    p(100.0000) =     11.158 ms/op


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
# Warmup Iteration   1: 13.390 ±(99.9%) 0.447 ms/op
Iteration   1: 8.042 ±(99.9%) 0.096 ms/op
                 listUser·p0.00:   2.990 ms/op
                 listUser·p0.50:   7.840 ms/op
                 listUser·p0.90:   10.306 ms/op
                 listUser·p0.95:   11.211 ms/op
                 listUser·p0.99:   13.500 ms/op
                 listUser·p0.999:  24.025 ms/op
                 listUser·p0.9999: 27.001 ms/op
                 listUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3994
  mean =      8.042 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 92 
    [ 5.000,  7.500) = 1553 
    [ 7.500, 10.000) = 1858 
    [10.000, 12.500) = 422 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.990 ms/op
     p(50.0000) =      7.840 ms/op
     p(90.0000) =     10.306 ms/op
     p(95.0000) =     11.211 ms/op
     p(99.0000) =     13.500 ms/op
     p(99.9000) =     24.025 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.999          ops/ms
Client.existUser                       thrpt         10.269          ops/ms
Client.getUser                         thrpt          8.967          ops/ms
Client.listUser                        thrpt          3.328          ops/ms
Client.createUser                       avgt          3.001           ms/op
Client.existUser                        avgt          1.815           ms/op
Client.getUser                          avgt          3.164           ms/op
Client.listUser                         avgt          9.715           ms/op
Client.createUser                     sample  10370   3.102 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.100           ms/op
Client.createUser:createUser·p0.50    sample          2.785           ms/op
Client.createUser:createUser·p0.90    sample          3.887           ms/op
Client.createUser:createUser·p0.95    sample          4.391           ms/op
Client.createUser:createUser·p0.99    sample         11.539           ms/op
Client.createUser:createUser·p0.999   sample         16.105           ms/op
Client.createUser:createUser·p0.9999  sample         16.236           ms/op
Client.createUser:createUser·p1.00    sample         16.237           ms/op
Client.existUser                      sample  19416   1.646 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.682           ms/op
Client.existUser:existUser·p0.50      sample          1.552           ms/op
Client.existUser:existUser·p0.90      sample          2.025           ms/op
Client.existUser:existUser·p0.95      sample          2.167           ms/op
Client.existUser:existUser·p0.99      sample          2.802           ms/op
Client.existUser:existUser·p0.999     sample         17.280           ms/op
Client.existUser:existUser·p0.9999    sample         18.591           ms/op
Client.existUser:existUser·p1.00      sample         19.300           ms/op
Client.getUser                        sample   9683   3.304 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          1.178           ms/op
Client.getUser:getUser·p0.50          sample          3.301           ms/op
Client.getUser:getUser·p0.90          sample          4.021           ms/op
Client.getUser:getUser·p0.95          sample          4.283           ms/op
Client.getUser:getUser·p0.99          sample          6.136           ms/op
Client.getUser:getUser·p0.999         sample         10.724           ms/op
Client.getUser:getUser·p0.9999        sample         11.158           ms/op
Client.getUser:getUser·p1.00          sample         11.158           ms/op
Client.listUser                       sample   3994   8.042 ± 0.096   ms/op
Client.listUser:listUser·p0.00        sample          2.990           ms/op
Client.listUser:listUser·p0.50        sample          7.840           ms/op
Client.listUser:listUser·p0.90        sample         10.306           ms/op
Client.listUser:listUser·p0.95        sample         11.211           ms/op
Client.listUser:listUser·p0.99        sample         13.500           ms/op
Client.listUser:listUser·p0.999       sample         24.025           ms/op
Client.listUser:listUser·p0.9999      sample         27.001           ms/op
Client.listUser:listUser·p1.00        sample         27.001           ms/op
