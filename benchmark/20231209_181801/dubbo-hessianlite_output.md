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
# Warmup Iteration   1: 2.408 ops/ms
Iteration   1: 5.796 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.796 ops/ms


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
# Warmup Iteration   1: 5.634 ops/ms
Iteration   1: 12.848 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.848 ops/ms


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
# Warmup Iteration   1: 4.301 ops/ms
Iteration   1: 7.909 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.909 ops/ms


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
# Warmup Iteration   1: 2.112 ops/ms
Iteration   1: 3.973 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.973 ops/ms


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
# Warmup Iteration   1: 5.041 ±(99.9%) 0.059 ms/op
Iteration   1: 3.076 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.076 ms/op


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
# Warmup Iteration   1: 3.079 ±(99.9%) 0.042 ms/op
Iteration   1: 1.916 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.916 ms/op


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
# Warmup Iteration   1: 4.669 ±(99.9%) 0.068 ms/op
Iteration   1: 2.669 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.669 ms/op


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
# Warmup Iteration   1: 11.564 ±(99.9%) 0.195 ms/op
Iteration   1: 8.254 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.254 ms/op


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
# Warmup Iteration   1: 4.938 ±(99.9%) 0.098 ms/op
Iteration   1: 2.940 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   9.929 ms/op
                 createUser·p0.999:  16.515 ms/op
                 createUser·p0.9999: 18.715 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10875
  mean =      2.940 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 4125 
    [ 2.500,  3.750) = 5791 
    [ 3.750,  5.000) = 633 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     18.715 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.106 ms/op
Iteration   1: 1.937 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.397 ms/op
                 existUser·p0.50:   1.849 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   4.082 ms/op
                 existUser·p0.999:  22.083 ms/op
                 existUser·p0.9999: 22.426 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16544
  mean =      1.937 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15300 
    [ 2.500,  5.000) = 1146 
    [ 5.000,  7.500) = 58 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.082 ms/op
     p(99.9000) =     22.083 ms/op
     p(99.9900) =     22.426 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.104 ms/op
Iteration   1: 3.364 ±(99.9%) 0.052 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.933 ms/op
                 getUser·p0.99:   7.475 ms/op
                 getUser·p0.999:  24.458 ms/op
                 getUser·p0.9999: 29.164 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9535
  mean =      3.364 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1363 
    [ 2.500,  5.000) = 7736 
    [ 5.000,  7.500) = 342 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.933 ms/op
     p(99.0000) =      7.475 ms/op
     p(99.9000) =     24.458 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 12.625 ±(99.9%) 0.552 ms/op
Iteration   1: 7.799 ±(99.9%) 0.104 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   7.504 ms/op
                 listUser·p0.90:   10.682 ms/op
                 listUser·p0.95:   11.485 ms/op
                 listUser·p0.99:   13.502 ms/op
                 listUser·p0.999:  17.404 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4095
  mean =      7.799 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 21 
    [ 3.750,  5.000) = 195 
    [ 5.000,  6.250) = 630 
    [ 6.250,  7.500) = 1191 
    [ 7.500,  8.750) = 989 
    [ 8.750, 10.000) = 520 
    [10.000, 11.250) = 298 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.474 ms/op
     p(50.0000) =      7.504 ms/op
     p(90.0000) =     10.682 ms/op
     p(95.0000) =     11.485 ms/op
     p(99.0000) =     13.502 ms/op
     p(99.9000) =     17.404 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.796          ops/ms
Client.existUser                       thrpt         12.848          ops/ms
Client.getUser                         thrpt          7.909          ops/ms
Client.listUser                        thrpt          3.973          ops/ms
Client.createUser                       avgt          3.076           ms/op
Client.existUser                        avgt          1.916           ms/op
Client.getUser                          avgt          2.669           ms/op
Client.listUser                         avgt          8.254           ms/op
Client.createUser                     sample  10875   2.940 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          0.699           ms/op
Client.createUser:createUser·p0.50    sample          2.634           ms/op
Client.createUser:createUser·p0.90    sample          3.629           ms/op
Client.createUser:createUser·p0.95    sample          4.243           ms/op
Client.createUser:createUser·p0.99    sample          9.929           ms/op
Client.createUser:createUser·p0.999   sample         16.515           ms/op
Client.createUser:createUser·p0.9999  sample         18.715           ms/op
Client.createUser:createUser·p1.00    sample         18.743           ms/op
Client.existUser                      sample  16544   1.937 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.397           ms/op
Client.existUser:existUser·p0.50      sample          1.849           ms/op
Client.existUser:existUser·p0.90      sample          2.400           ms/op
Client.existUser:existUser·p0.95      sample          2.654           ms/op
Client.existUser:existUser·p0.99      sample          4.082           ms/op
Client.existUser:existUser·p0.999     sample         22.083           ms/op
Client.existUser:existUser·p0.9999    sample         22.426           ms/op
Client.existUser:existUser·p1.00      sample         22.512           ms/op
Client.getUser                        sample   9535   3.364 ± 0.052   ms/op
Client.getUser:getUser·p0.00          sample          0.834           ms/op
Client.getUser:getUser·p0.50          sample          3.248           ms/op
Client.getUser:getUser·p0.90          sample          4.076           ms/op
Client.getUser:getUser·p0.95          sample          4.933           ms/op
Client.getUser:getUser·p0.99          sample          7.475           ms/op
Client.getUser:getUser·p0.999         sample         24.458           ms/op
Client.getUser:getUser·p0.9999        sample         29.164           ms/op
Client.getUser:getUser·p1.00          sample         29.164           ms/op
Client.listUser                       sample   4095   7.799 ± 0.104   ms/op
Client.listUser:listUser·p0.00        sample          2.474           ms/op
Client.listUser:listUser·p0.50        sample          7.504           ms/op
Client.listUser:listUser·p0.90        sample         10.682           ms/op
Client.listUser:listUser·p0.95        sample         11.485           ms/op
Client.listUser:listUser·p0.99        sample         13.502           ms/op
Client.listUser:listUser·p0.999       sample         17.404           ms/op
Client.listUser:listUser·p0.9999      sample         17.760           ms/op
Client.listUser:listUser·p1.00        sample         17.760           ms/op
