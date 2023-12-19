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
# Warmup Iteration   1: 2.171 ops/ms
Iteration   1: 5.881 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.881 ops/ms


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
# Warmup Iteration   1: 5.166 ops/ms
Iteration   1: 13.205 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.205 ops/ms


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
# Warmup Iteration   1: 4.093 ops/ms
Iteration   1: 7.310 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.310 ops/ms


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
# Warmup Iteration   1: 2.319 ops/ms
Iteration   1: 3.401 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.401 ops/ms


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
# Warmup Iteration   1: 5.191 ±(99.9%) 0.081 ms/op
Iteration   1: 2.991 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.991 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.036 ms/op
Iteration   1: 2.154 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.154 ms/op


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.064 ms/op
Iteration   1: 3.088 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.088 ms/op


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
# Warmup Iteration   1: 12.606 ±(99.9%) 0.275 ms/op
Iteration   1: 8.131 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.131 ms/op


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
# Warmup Iteration   1: 5.075 ±(99.9%) 0.109 ms/op
Iteration   1: 2.945 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   2.707 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  16.077 ms/op
                 createUser·p0.9999: 16.490 ms/op
                 createUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10861
  mean =      2.945 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2575 
    [ 2.500,  3.750) = 7334 
    [ 3.750,  5.000) = 753 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.707 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     16.077 ms/op
     p(99.9900) =     16.490 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.083 ms/op
Iteration   1: 1.793 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   1.714 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   2.916 ms/op
                 existUser·p0.999:  5.326 ms/op
                 existUser·p0.9999: 6.408 ms/op
                 existUser·p1.00:   6.627 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17858
  mean =      1.793 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 42 
    [1.000, 1.500) = 3141 
    [1.500, 2.000) = 10737 
    [2.000, 2.500) = 3111 
    [2.500, 3.000) = 689 
    [3.000, 3.500) = 37 
    [3.500, 4.000) = 28 
    [4.000, 4.500) = 14 
    [4.500, 5.000) = 13 
    [5.000, 5.500) = 40 
    [5.500, 6.000) = 2 
    [6.000, 6.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      2.916 ms/op
     p(99.9000) =      5.326 ms/op
     p(99.9900) =      6.408 ms/op
     p(99.9990) =      6.627 ms/op
     p(99.9999) =      6.627 ms/op
    p(100.0000) =      6.627 ms/op


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.146 ms/op
Iteration   1: 3.212 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  11.273 ms/op
                 getUser·p0.9999: 12.665 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9980
  mean =      3.212 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 1517 
    [ 2.500,  3.750) = 6752 
    [ 3.750,  5.000) = 1459 
    [ 5.000,  6.250) = 151 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     11.273 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


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
# Warmup Iteration   1: 12.231 ±(99.9%) 0.455 ms/op
Iteration   1: 7.717 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   7.430 ms/op
                 listUser·p0.90:   9.929 ms/op
                 listUser·p0.95:   11.026 ms/op
                 listUser·p0.99:   15.430 ms/op
                 listUser·p0.999:  25.670 ms/op
                 listUser·p0.9999: 26.935 ms/op
                 listUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4219
  mean =      7.717 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 170 
    [ 5.000,  7.500) = 2021 
    [ 7.500, 10.000) = 1618 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.372 ms/op
     p(50.0000) =      7.430 ms/op
     p(90.0000) =      9.929 ms/op
     p(95.0000) =     11.026 ms/op
     p(99.0000) =     15.430 ms/op
     p(99.9000) =     25.670 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.881          ops/ms
Client.existUser                       thrpt         13.205          ops/ms
Client.getUser                         thrpt          7.310          ops/ms
Client.listUser                        thrpt          3.401          ops/ms
Client.createUser                       avgt          2.991           ms/op
Client.existUser                        avgt          2.154           ms/op
Client.getUser                          avgt          3.088           ms/op
Client.listUser                         avgt          8.131           ms/op
Client.createUser                     sample  10861   2.945 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          0.670           ms/op
Client.createUser:createUser·p0.50    sample          2.707           ms/op
Client.createUser:createUser·p0.90    sample          3.645           ms/op
Client.createUser:createUser·p0.95    sample          4.133           ms/op
Client.createUser:createUser·p0.99    sample          7.184           ms/op
Client.createUser:createUser·p0.999   sample         16.077           ms/op
Client.createUser:createUser·p0.9999  sample         16.490           ms/op
Client.createUser:createUser·p1.00    sample         16.515           ms/op
Client.existUser                      sample  17858   1.793 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.676           ms/op
Client.existUser:existUser·p0.50      sample          1.714           ms/op
Client.existUser:existUser·p0.90      sample          2.298           ms/op
Client.existUser:existUser·p0.95      sample          2.482           ms/op
Client.existUser:existUser·p0.99      sample          2.916           ms/op
Client.existUser:existUser·p0.999     sample          5.326           ms/op
Client.existUser:existUser·p0.9999    sample          6.408           ms/op
Client.existUser:existUser·p1.00      sample          6.627           ms/op
Client.getUser                        sample   9980   3.212 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.710           ms/op
Client.getUser:getUser·p0.50          sample          3.121           ms/op
Client.getUser:getUser·p0.90          sample          4.071           ms/op
Client.getUser:getUser·p0.95          sample          4.497           ms/op
Client.getUser:getUser·p0.99          sample          6.111           ms/op
Client.getUser:getUser·p0.999         sample         11.273           ms/op
Client.getUser:getUser·p0.9999        sample         12.665           ms/op
Client.getUser:getUser·p1.00          sample         12.665           ms/op
Client.listUser                       sample   4219   7.717 ± 0.112   ms/op
Client.listUser:listUser·p0.00        sample          2.372           ms/op
Client.listUser:listUser·p0.50        sample          7.430           ms/op
Client.listUser:listUser·p0.90        sample          9.929           ms/op
Client.listUser:listUser·p0.95        sample         11.026           ms/op
Client.listUser:listUser·p0.99        sample         15.430           ms/op
Client.listUser:listUser·p0.999       sample         25.670           ms/op
Client.listUser:listUser·p0.9999      sample         26.935           ms/op
Client.listUser:listUser·p1.00        sample         26.935           ms/op
