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
# Warmup Iteration   1: 2.452 ops/ms
Iteration   1: 6.164 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.164 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.568 ops/ms
Iteration   1: 11.948 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.948 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.713 ops/ms
Iteration   1: 7.846 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.846 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.115 ops/ms
Iteration   1: 3.448 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.448 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.347 ±(99.9%) 0.064 ms/op
Iteration   1: 3.558 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.558 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.282 ±(99.9%) 0.037 ms/op
Iteration   1: 2.008 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.008 ms/op


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
# Warmup Iteration   1: 5.512 ±(99.9%) 0.082 ms/op
Iteration   1: 2.878 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.878 ms/op


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
# Warmup Iteration   1: 12.001 ±(99.9%) 0.280 ms/op
Iteration   1: 8.730 ±(99.9%) 0.163 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.730 ms/op


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
# Warmup Iteration   1: 5.063 ±(99.9%) 0.148 ms/op
Iteration   1: 3.097 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.176 ms/op
                 createUser·p0.999:  16.996 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10311
  mean =      3.097 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1866 
    [ 2.500,  3.750) = 7295 
    [ 3.750,  5.000) = 1014 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.176 ms/op
     p(99.9000) =     16.996 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.059 ±(99.9%) 0.062 ms/op
Iteration   1: 1.763 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   1.683 ms/op
                 existUser·p0.90:   2.068 ms/op
                 existUser·p0.95:   2.290 ms/op
                 existUser·p0.99:   3.088 ms/op
                 existUser·p0.999:  7.660 ms/op
                 existUser·p0.9999: 7.817 ms/op
                 existUser·p1.00:   7.823 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18120
  mean =      1.763 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 2 
    [0.500, 1.000) = 16 
    [1.000, 1.500) = 1952 
    [1.500, 2.000) = 13915 
    [2.000, 2.500) = 1750 
    [2.500, 3.000) = 260 
    [3.000, 3.500) = 122 
    [3.500, 4.000) = 12 
    [4.000, 4.500) = 12 
    [4.500, 5.000) = 12 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 30 
    [7.000, 7.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.068 ms/op
     p(95.0000) =      2.290 ms/op
     p(99.0000) =      3.088 ms/op
     p(99.9000) =      7.660 ms/op
     p(99.9900) =      7.817 ms/op
     p(99.9990) =      7.823 ms/op
     p(99.9999) =      7.823 ms/op
    p(100.0000) =      7.823 ms/op


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.104 ms/op
Iteration   1: 2.957 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.933 ms/op
                 getUser·p0.99:   4.844 ms/op
                 getUser·p0.999:  6.849 ms/op
                 getUser·p0.9999: 6.978 ms/op
                 getUser·p1.00:   6.980 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10817
  mean =      2.957 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 68 
    [1.500, 2.000) = 343 
    [2.000, 2.500) = 1902 
    [2.500, 3.000) = 3490 
    [3.000, 3.500) = 3500 
    [3.500, 4.000) = 1067 
    [4.000, 4.500) = 244 
    [4.500, 5.000) = 103 
    [5.000, 5.500) = 44 
    [5.500, 6.000) = 13 
    [6.000, 6.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.933 ms/op
     p(99.0000) =      4.844 ms/op
     p(99.9000) =      6.849 ms/op
     p(99.9900) =      6.978 ms/op
     p(99.9990) =      6.980 ms/op
     p(99.9999) =      6.980 ms/op
    p(100.0000) =      6.980 ms/op


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
# Warmup Iteration   1: 12.794 ±(99.9%) 0.530 ms/op
Iteration   1: 8.014 ±(99.9%) 0.110 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   7.758 ms/op
                 listUser·p0.90:   10.420 ms/op
                 listUser·p0.95:   11.416 ms/op
                 listUser·p0.99:   16.151 ms/op
                 listUser·p0.999:  20.693 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4023
  mean =      8.014 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 139 
    [ 5.000,  7.500) = 1621 
    [ 7.500, 10.000) = 1737 
    [10.000, 12.500) = 419 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      7.758 ms/op
     p(90.0000) =     10.420 ms/op
     p(95.0000) =     11.416 ms/op
     p(99.0000) =     16.151 ms/op
     p(99.9000) =     20.693 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.164          ops/ms
Client.existUser                       thrpt         11.948          ops/ms
Client.getUser                         thrpt          7.846          ops/ms
Client.listUser                        thrpt          3.448          ops/ms
Client.createUser                       avgt          3.558           ms/op
Client.existUser                        avgt          2.008           ms/op
Client.getUser                          avgt          2.878           ms/op
Client.listUser                         avgt          8.730           ms/op
Client.createUser                     sample  10311   3.097 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.157           ms/op
Client.createUser:createUser·p0.50    sample          2.941           ms/op
Client.createUser:createUser·p0.90    sample          3.801           ms/op
Client.createUser:createUser·p0.95    sample          4.104           ms/op
Client.createUser:createUser·p0.99    sample          5.176           ms/op
Client.createUser:createUser·p0.999   sample         16.996           ms/op
Client.createUser:createUser·p0.9999  sample         17.236           ms/op
Client.createUser:createUser·p1.00    sample         17.236           ms/op
Client.existUser                      sample  18120   1.763 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.461           ms/op
Client.existUser:existUser·p0.50      sample          1.683           ms/op
Client.existUser:existUser·p0.90      sample          2.068           ms/op
Client.existUser:existUser·p0.95      sample          2.290           ms/op
Client.existUser:existUser·p0.99      sample          3.088           ms/op
Client.existUser:existUser·p0.999     sample          7.660           ms/op
Client.existUser:existUser·p0.9999    sample          7.817           ms/op
Client.existUser:existUser·p1.00      sample          7.823           ms/op
Client.getUser                        sample  10817   2.957 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.784           ms/op
Client.getUser:getUser·p0.50          sample          2.945           ms/op
Client.getUser:getUser·p0.90          sample          3.629           ms/op
Client.getUser:getUser·p0.95          sample          3.933           ms/op
Client.getUser:getUser·p0.99          sample          4.844           ms/op
Client.getUser:getUser·p0.999         sample          6.849           ms/op
Client.getUser:getUser·p0.9999        sample          6.978           ms/op
Client.getUser:getUser·p1.00          sample          6.980           ms/op
Client.listUser                       sample   4023   8.014 ± 0.110   ms/op
Client.listUser:listUser·p0.00        sample          1.876           ms/op
Client.listUser:listUser·p0.50        sample          7.758           ms/op
Client.listUser:listUser·p0.90        sample         10.420           ms/op
Client.listUser:listUser·p0.95        sample         11.416           ms/op
Client.listUser:listUser·p0.99        sample         16.151           ms/op
Client.listUser:listUser·p0.999       sample         20.693           ms/op
Client.listUser:listUser·p0.9999      sample         23.069           ms/op
Client.listUser:listUser·p1.00        sample         23.069           ms/op
