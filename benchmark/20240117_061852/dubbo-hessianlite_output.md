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
# Warmup Iteration   1: 2.323 ops/ms
Iteration   1: 6.094 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.094 ops/ms


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
# Warmup Iteration   1: 5.302 ops/ms
Iteration   1: 12.619 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.619 ops/ms


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
# Warmup Iteration   1: 3.695 ops/ms
Iteration   1: 7.324 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.324 ops/ms


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
# Warmup Iteration   1: 1.837 ops/ms
Iteration   1: 2.902 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.902 ops/ms


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
# Warmup Iteration   1: 5.215 ±(99.9%) 0.079 ms/op
Iteration   1: 3.157 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.157 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.034 ms/op
Iteration   1: 1.861 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.861 ms/op


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
# Warmup Iteration   1: 4.812 ±(99.9%) 0.055 ms/op
Iteration   1: 3.416 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.416 ms/op


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
# Warmup Iteration   1: 13.506 ±(99.9%) 0.241 ms/op
Iteration   1: 8.879 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.879 ms/op


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
# Warmup Iteration   1: 5.056 ±(99.9%) 0.115 ms/op
Iteration   1: 2.925 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   2.781 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.888 ms/op
                 createUser·p0.999:  30.081 ms/op
                 createUser·p0.9999: 32.747 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10924
  mean =      2.925 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3263 
    [ 2.500,  5.000) = 7497 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.888 ms/op
     p(99.9000) =     30.081 ms/op
     p(99.9900) =     32.747 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 2.946 ±(99.9%) 0.066 ms/op
Iteration   1: 2.059 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   1.939 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.818 ms/op
                 existUser·p0.99:   5.160 ms/op
                 existUser·p0.999:  13.361 ms/op
                 existUser·p0.9999: 16.165 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15505
  mean =      2.059 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 259 
    [ 1.250,  2.500) = 13603 
    [ 2.500,  3.750) = 1296 
    [ 3.750,  5.000) = 184 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      5.160 ms/op
     p(99.9000) =     13.361 ms/op
     p(99.9900) =     16.165 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 5.616 ±(99.9%) 0.166 ms/op
Iteration   1: 3.081 ±(99.9%) 0.055 ms/op
                 getUser·p0.00:   0.531 ms/op
                 getUser·p0.50:   2.806 ms/op
                 getUser·p0.90:   3.832 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.301 ms/op
                 getUser·p0.999:  24.242 ms/op
                 getUser·p0.9999: 25.227 ms/op
                 getUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10394
  mean =      3.081 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1866 
    [ 2.500,  5.000) = 8374 
    [ 5.000,  7.500) = 82 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.832 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.301 ms/op
     p(99.9000) =     24.242 ms/op
     p(99.9900) =     25.227 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 12.958 ±(99.9%) 0.449 ms/op
Iteration   1: 8.871 ±(99.9%) 0.163 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   8.319 ms/op
                 listUser·p0.90:   11.993 ms/op
                 listUser·p0.95:   13.910 ms/op
                 listUser·p0.99:   19.634 ms/op
                 listUser·p0.999:  29.101 ms/op
                 listUser·p0.9999: 36.372 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3596
  mean =      8.871 ±(99.9%) 0.163 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 131 
    [ 5.000,  7.500) = 1055 
    [ 7.500, 10.000) = 1458 
    [10.000, 12.500) = 665 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.122 ms/op
     p(50.0000) =      8.319 ms/op
     p(90.0000) =     11.993 ms/op
     p(95.0000) =     13.910 ms/op
     p(99.0000) =     19.634 ms/op
     p(99.9000) =     29.101 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.094          ops/ms
Client.existUser                       thrpt         12.619          ops/ms
Client.getUser                         thrpt          7.324          ops/ms
Client.listUser                        thrpt          2.902          ops/ms
Client.createUser                       avgt          3.157           ms/op
Client.existUser                        avgt          1.861           ms/op
Client.getUser                          avgt          3.416           ms/op
Client.listUser                         avgt          8.879           ms/op
Client.createUser                     sample  10924   2.925 ± 0.050   ms/op
Client.createUser:createUser·p0.00    sample          1.090           ms/op
Client.createUser:createUser·p0.50    sample          2.781           ms/op
Client.createUser:createUser·p0.90    sample          3.502           ms/op
Client.createUser:createUser·p0.95    sample          3.846           ms/op
Client.createUser:createUser·p0.99    sample          5.888           ms/op
Client.createUser:createUser·p0.999   sample         30.081           ms/op
Client.createUser:createUser·p0.9999  sample         32.747           ms/op
Client.createUser:createUser·p1.00    sample         32.768           ms/op
Client.existUser                      sample  15505   2.059 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.517           ms/op
Client.existUser:existUser·p0.50      sample          1.939           ms/op
Client.existUser:existUser·p0.90      sample          2.523           ms/op
Client.existUser:existUser·p0.95      sample          2.818           ms/op
Client.existUser:existUser·p0.99      sample          5.160           ms/op
Client.existUser:existUser·p0.999     sample         13.361           ms/op
Client.existUser:existUser·p0.9999    sample         16.165           ms/op
Client.existUser:existUser·p1.00      sample         16.941           ms/op
Client.getUser                        sample  10394   3.081 ± 0.055   ms/op
Client.getUser:getUser·p0.00          sample          0.531           ms/op
Client.getUser:getUser·p0.50          sample          2.806           ms/op
Client.getUser:getUser·p0.90          sample          3.832           ms/op
Client.getUser:getUser·p0.95          sample          4.174           ms/op
Client.getUser:getUser·p0.99          sample          5.301           ms/op
Client.getUser:getUser·p0.999         sample         24.242           ms/op
Client.getUser:getUser·p0.9999        sample         25.227           ms/op
Client.getUser:getUser·p1.00          sample         25.231           ms/op
Client.listUser                       sample   3596   8.871 ± 0.163   ms/op
Client.listUser:listUser·p0.00        sample          2.122           ms/op
Client.listUser:listUser·p0.50        sample          8.319           ms/op
Client.listUser:listUser·p0.90        sample         11.993           ms/op
Client.listUser:listUser·p0.95        sample         13.910           ms/op
Client.listUser:listUser·p0.99        sample         19.634           ms/op
Client.listUser:listUser·p0.999       sample         29.101           ms/op
Client.listUser:listUser·p0.9999      sample         36.372           ms/op
Client.listUser:listUser·p1.00        sample         36.372           ms/op
