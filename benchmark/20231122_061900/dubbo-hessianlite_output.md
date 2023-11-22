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
# Warmup Iteration   1: 2.612 ops/ms
Iteration   1: 6.977 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.977 ops/ms


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
# Warmup Iteration   1: 5.226 ops/ms
Iteration   1: 12.599 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.599 ops/ms


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
# Warmup Iteration   1: 5.071 ops/ms
Iteration   1: 9.981 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.981 ops/ms


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
# Warmup Iteration   1: 2.289 ops/ms
Iteration   1: 3.984 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.984 ops/ms


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.084 ms/op
Iteration   1: 2.679 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.679 ms/op


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
# Warmup Iteration   1: 2.796 ±(99.9%) 0.027 ms/op
Iteration   1: 1.798 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.798 ms/op


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.045 ms/op
Iteration   1: 2.887 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.887 ms/op


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
# Warmup Iteration   1: 12.312 ±(99.9%) 0.301 ms/op
Iteration   1: 7.952 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.952 ms/op


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.107 ms/op
Iteration   1: 3.047 ±(99.9%) 0.072 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   2.761 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.923 ms/op
                 createUser·p0.99:   12.022 ms/op
                 createUser·p0.999:  36.241 ms/op
                 createUser·p0.9999: 37.276 ms/op
                 createUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10522
  mean =      3.047 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3397 
    [ 2.500,  5.000) = 6851 
    [ 5.000,  7.500) = 114 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.923 ms/op
     p(99.0000) =     12.022 ms/op
     p(99.9000) =     36.241 ms/op
     p(99.9900) =     37.276 ms/op
     p(99.9990) =     37.290 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 2.959 ±(99.9%) 0.054 ms/op
Iteration   1: 1.764 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   1.688 ms/op
                 existUser·p0.90:   2.101 ms/op
                 existUser·p0.95:   2.245 ms/op
                 existUser·p0.99:   2.963 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 13.585 ms/op
                 existUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18184
  mean =      1.764 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 438 
    [ 1.250,  2.500) = 17359 
    [ 2.500,  3.750) = 289 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.245 ms/op
     p(99.0000) =      2.963 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     13.585 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.093 ms/op
Iteration   1: 2.844 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   2.712 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 18.668 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11295
  mean =      2.844 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 4481 
    [ 2.500,  3.750) = 5587 
    [ 3.750,  5.000) = 901 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.712 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     18.668 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 11.568 ±(99.9%) 0.384 ms/op
Iteration   1: 7.818 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   3.011 ms/op
                 listUser·p0.50:   7.569 ms/op
                 listUser·p0.90:   10.371 ms/op
                 listUser·p0.95:   11.452 ms/op
                 listUser·p0.99:   13.533 ms/op
                 listUser·p0.999:  15.849 ms/op
                 listUser·p0.9999: 16.269 ms/op
                 listUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4079
  mean =      7.818 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 12 
    [ 3.750,  5.000) = 155 
    [ 5.000,  6.250) = 660 
    [ 6.250,  7.500) = 1145 
    [ 7.500,  8.750) = 1033 
    [ 8.750, 10.000) = 564 
    [10.000, 11.250) = 274 
    [11.250, 12.500) = 151 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.011 ms/op
     p(50.0000) =      7.569 ms/op
     p(90.0000) =     10.371 ms/op
     p(95.0000) =     11.452 ms/op
     p(99.0000) =     13.533 ms/op
     p(99.9000) =     15.849 ms/op
     p(99.9900) =     16.269 ms/op
     p(99.9990) =     16.269 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.977          ops/ms
Client.existUser                       thrpt         12.599          ops/ms
Client.getUser                         thrpt          9.981          ops/ms
Client.listUser                        thrpt          3.984          ops/ms
Client.createUser                       avgt          2.679           ms/op
Client.existUser                        avgt          1.798           ms/op
Client.getUser                          avgt          2.887           ms/op
Client.listUser                         avgt          7.952           ms/op
Client.createUser                     sample  10522   3.047 ± 0.072   ms/op
Client.createUser:createUser·p0.00    sample          0.878           ms/op
Client.createUser:createUser·p0.50    sample          2.761           ms/op
Client.createUser:createUser·p0.90    sample          3.564           ms/op
Client.createUser:createUser·p0.95    sample          3.923           ms/op
Client.createUser:createUser·p0.99    sample         12.022           ms/op
Client.createUser:createUser·p0.999   sample         36.241           ms/op
Client.createUser:createUser·p0.9999  sample         37.276           ms/op
Client.createUser:createUser·p1.00    sample         37.290           ms/op
Client.existUser                      sample  18184   1.764 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.642           ms/op
Client.existUser:existUser·p0.50      sample          1.688           ms/op
Client.existUser:existUser·p0.90      sample          2.101           ms/op
Client.existUser:existUser·p0.95      sample          2.245           ms/op
Client.existUser:existUser·p0.99      sample          2.963           ms/op
Client.existUser:existUser·p0.999     sample         13.418           ms/op
Client.existUser:existUser·p0.9999    sample         13.585           ms/op
Client.existUser:existUser·p1.00      sample         14.041           ms/op
Client.getUser                        sample  11295   2.844 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample          0.673           ms/op
Client.getUser:getUser·p0.50          sample          2.712           ms/op
Client.getUser:getUser·p0.90          sample          3.764           ms/op
Client.getUser:getUser·p0.95          sample          4.153           ms/op
Client.getUser:getUser·p0.99          sample          6.611           ms/op
Client.getUser:getUser·p0.999         sample         16.941           ms/op
Client.getUser:getUser·p0.9999        sample         18.668           ms/op
Client.getUser:getUser·p1.00          sample         18.711           ms/op
Client.listUser                       sample   4079   7.818 ± 0.099   ms/op
Client.listUser:listUser·p0.00        sample          3.011           ms/op
Client.listUser:listUser·p0.50        sample          7.569           ms/op
Client.listUser:listUser·p0.90        sample         10.371           ms/op
Client.listUser:listUser·p0.95        sample         11.452           ms/op
Client.listUser:listUser·p0.99        sample         13.533           ms/op
Client.listUser:listUser·p0.999       sample         15.849           ms/op
Client.listUser:listUser·p0.9999      sample         16.269           ms/op
Client.listUser:listUser·p1.00        sample         16.269           ms/op
