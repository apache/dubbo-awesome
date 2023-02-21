# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.016 ops/ms
Iteration   1: 2.591 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.591 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.362 ops/ms
Iteration   1: 6.950 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.950 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.603 ops/ms
Iteration   1: 5.830 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.830 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.867 ops/ms
Iteration   1: 1.563 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.563 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 14.830 ±(99.9%) 0.260 ms/op
Iteration   1: 6.960 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.960 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.590 ±(99.9%) 0.065 ms/op
Iteration   1: 2.918 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.195 ±(99.9%) 0.115 ms/op
Iteration   1: 5.319 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 24.847 ±(99.9%) 0.339 ms/op
Iteration   1: 17.896 ±(99.9%) 0.147 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.896 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.183 ±(99.9%) 0.351 ms/op
Iteration   1: 5.969 ±(99.9%) 0.392 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   8.995 ms/op
                 createUser·p0.95:   11.158 ms/op
                 createUser·p0.99:   19.825 ms/op
                 createUser·p0.999:  146.770 ms/op
                 createUser·p0.9999: 156.500 ms/op
                 createUser·p1.00:   156.500 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5730
  mean =      5.969 ±(99.9%) 0.392 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 5530 
    [ 12.500,  25.000) = 154 
    [ 25.000,  37.500) = 5 
    [ 37.500,  50.000) = 5 
    [ 50.000,  62.500) = 6 
    [ 62.500,  75.000) = 3 
    [ 75.000,  87.500) = 4 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 5 
    [112.500, 125.000) = 4 
    [125.000, 137.500) = 5 
    [137.500, 150.000) = 6 
    [150.000, 162.500) = 3 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      8.995 ms/op
     p(95.0000) =     11.158 ms/op
     p(99.0000) =     19.825 ms/op
     p(99.9000) =    146.770 ms/op
     p(99.9900) =    156.500 ms/op
     p(99.9990) =    156.500 ms/op
     p(99.9999) =    156.500 ms/op
    p(100.0000) =    156.500 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.490 ±(99.9%) 0.177 ms/op
Iteration   1: 3.996 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   4.010 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   8.208 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 12.239 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8008
  mean =      3.996 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 248 
    [ 2.500,  3.750) = 1316 
    [ 3.750,  5.000) = 6185 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     12.239 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.403 ±(99.9%) 0.241 ms/op
Iteration   1: 4.365 ±(99.9%) 0.048 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   10.743 ms/op
                 getUser·p0.999:  16.040 ms/op
                 getUser·p0.9999: 16.105 ms/op
                 getUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7327
  mean =      4.365 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 36 
    [ 2.500,  3.750) = 898 
    [ 3.750,  5.000) = 5801 
    [ 5.000,  6.250) = 419 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =     10.743 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     16.105 ms/op
     p(99.9990) =     16.105 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.432 ±(99.9%) 0.830 ms/op
Iteration   1: 16.507 ±(99.9%) 0.203 ms/op
                 listUser·p0.00:   9.929 ms/op
                 listUser·p0.50:   15.466 ms/op
                 listUser·p0.90:   18.153 ms/op
                 listUser·p0.95:   24.959 ms/op
                 listUser·p0.99:   28.180 ms/op
                 listUser·p0.999:  28.475 ms/op
                 listUser·p0.9999: 28.475 ms/op
                 listUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1945
  mean =     16.507 ±(99.9%) 0.203 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 1492 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      9.929 ms/op
     p(50.0000) =     15.466 ms/op
     p(90.0000) =     18.153 ms/op
     p(95.0000) =     24.959 ms/op
     p(99.0000) =     28.180 ms/op
     p(99.9000) =     28.475 ms/op
     p(99.9900) =     28.475 ms/op
     p(99.9990) =     28.475 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt    Score   Error   Units
Client.createUser                      thrpt          2.591          ops/ms
Client.existUser                       thrpt          6.950          ops/ms
Client.getUser                         thrpt          5.830          ops/ms
Client.listUser                        thrpt          1.563          ops/ms
Client.createUser                       avgt          6.960           ms/op
Client.existUser                        avgt          2.918           ms/op
Client.getUser                          avgt          5.319           ms/op
Client.listUser                         avgt         17.896           ms/op
Client.createUser                     sample  5730    5.969 ± 0.392   ms/op
Client.createUser:createUser·p0.00    sample          1.274           ms/op
Client.createUser:createUser·p0.50    sample          4.678           ms/op
Client.createUser:createUser·p0.90    sample          8.995           ms/op
Client.createUser:createUser·p0.95    sample         11.158           ms/op
Client.createUser:createUser·p0.99    sample         19.825           ms/op
Client.createUser:createUser·p0.999   sample        146.770           ms/op
Client.createUser:createUser·p0.9999  sample        156.500           ms/op
Client.createUser:createUser·p1.00    sample        156.500           ms/op
Client.existUser                      sample  8008    3.996 ± 0.036   ms/op
Client.existUser:existUser·p0.00      sample          0.634           ms/op
Client.existUser:existUser·p0.50      sample          4.010           ms/op
Client.existUser:existUser·p0.90      sample          4.432           ms/op
Client.existUser:existUser·p0.95      sample          4.604           ms/op
Client.existUser:existUser·p0.99      sample          8.208           ms/op
Client.existUser:existUser·p0.999     sample         11.567           ms/op
Client.existUser:existUser·p0.9999    sample         12.239           ms/op
Client.existUser:existUser·p1.00      sample         12.239           ms/op
Client.getUser                        sample  7327    4.365 ± 0.048   ms/op
Client.getUser:getUser·p0.00          sample          1.640           ms/op
Client.getUser:getUser·p0.50          sample          4.211           ms/op
Client.getUser:getUser·p0.90          sample          4.817           ms/op
Client.getUser:getUser·p0.95          sample          5.423           ms/op
Client.getUser:getUser·p0.99          sample         10.743           ms/op
Client.getUser:getUser·p0.999         sample         16.040           ms/op
Client.getUser:getUser·p0.9999        sample         16.105           ms/op
Client.getUser:getUser·p1.00          sample         16.105           ms/op
Client.listUser                       sample  1945   16.507 ± 0.203   ms/op
Client.listUser:listUser·p0.00        sample          9.929           ms/op
Client.listUser:listUser·p0.50        sample         15.466           ms/op
Client.listUser:listUser·p0.90        sample         18.153           ms/op
Client.listUser:listUser·p0.95        sample         24.959           ms/op
Client.listUser:listUser·p0.99        sample         28.180           ms/op
Client.listUser:listUser·p0.999       sample         28.475           ms/op
Client.listUser:listUser·p0.9999      sample         28.475           ms/op
Client.listUser:listUser·p1.00        sample         28.475           ms/op
