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
# Warmup Iteration   1: 2.579 ops/ms
Iteration   1: 5.705 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.705 ops/ms


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
# Warmup Iteration   1: 5.823 ops/ms
Iteration   1: 12.432 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.432 ops/ms


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
Iteration   1: 9.270 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.270 ops/ms


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
# Warmup Iteration   1: 2.281 ops/ms
Iteration   1: 3.590 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.590 ops/ms


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
# Warmup Iteration   1: 5.806 ±(99.9%) 0.102 ms/op
Iteration   1: 2.880 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.880 ms/op


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
# Warmup Iteration   1: 2.904 ±(99.9%) 0.034 ms/op
Iteration   1: 1.905 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.905 ms/op


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.043 ms/op
Iteration   1: 2.765 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.765 ms/op


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
# Warmup Iteration   1: 11.904 ±(99.9%) 0.152 ms/op
Iteration   1: 8.994 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.994 ms/op


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
# Warmup Iteration   1: 4.924 ±(99.9%) 0.104 ms/op
Iteration   1: 3.184 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   2.888 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   9.923 ms/op
                 createUser·p0.999:  18.315 ms/op
                 createUser·p0.9999: 18.842 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10034
  mean =      3.184 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 3725 
    [ 2.500,  3.750) = 4195 
    [ 3.750,  5.000) = 1813 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      9.923 ms/op
     p(99.9000) =     18.315 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.060 ms/op
Iteration   1: 2.163 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   2.154 ms/op
                 existUser·p0.90:   2.647 ms/op
                 existUser·p0.95:   2.793 ms/op
                 existUser·p0.99:   3.311 ms/op
                 existUser·p0.999:  7.609 ms/op
                 existUser·p0.9999: 8.548 ms/op
                 existUser·p1.00:   8.716 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14776
  mean =      2.163 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 45 
    [1.000, 1.500) = 767 
    [1.500, 2.000) = 4543 
    [2.000, 2.500) = 6592 
    [2.500, 3.000) = 2464 
    [3.000, 3.500) = 239 
    [3.500, 4.000) = 50 
    [4.000, 4.500) = 7 
    [4.500, 5.000) = 32 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 10 
    [7.500, 8.000) = 9 
    [8.000, 8.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      2.647 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.311 ms/op
     p(99.9000) =      7.609 ms/op
     p(99.9900) =      8.548 ms/op
     p(99.9990) =      8.716 ms/op
     p(99.9999) =      8.716 ms/op
    p(100.0000) =      8.716 ms/op


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
# Warmup Iteration   1: 4.720 ±(99.9%) 0.112 ms/op
Iteration   1: 3.072 ±(99.9%) 0.043 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.768 ms/op
                 getUser·p0.999:  23.953 ms/op
                 getUser·p0.9999: 24.627 ms/op
                 getUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10393
  mean =      3.072 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2078 
    [ 2.500,  5.000) = 8159 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.768 ms/op
     p(99.9000) =     23.953 ms/op
     p(99.9900) =     24.627 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 12.812 ±(99.9%) 0.433 ms/op
Iteration   1: 8.387 ±(99.9%) 0.129 ms/op
                 listUser·p0.00:   1.712 ms/op
                 listUser·p0.50:   7.954 ms/op
                 listUser·p0.90:   11.485 ms/op
                 listUser·p0.95:   12.796 ms/op
                 listUser·p0.99:   15.878 ms/op
                 listUser·p0.999:  21.750 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3829
  mean =      8.387 ±(99.9%) 0.129 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 130 
    [ 5.000,  7.500) = 1404 
    [ 7.500, 10.000) = 1517 
    [10.000, 12.500) = 548 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      7.954 ms/op
     p(90.0000) =     11.485 ms/op
     p(95.0000) =     12.796 ms/op
     p(99.0000) =     15.878 ms/op
     p(99.9000) =     21.750 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.705          ops/ms
Client.existUser                       thrpt         12.432          ops/ms
Client.getUser                         thrpt          9.270          ops/ms
Client.listUser                        thrpt          3.590          ops/ms
Client.createUser                       avgt          2.880           ms/op
Client.existUser                        avgt          1.905           ms/op
Client.getUser                          avgt          2.765           ms/op
Client.listUser                         avgt          8.994           ms/op
Client.createUser                     sample  10034   3.184 ± 0.051   ms/op
Client.createUser:createUser·p0.00    sample          1.161           ms/op
Client.createUser:createUser·p0.50    sample          2.888           ms/op
Client.createUser:createUser·p0.90    sample          4.465           ms/op
Client.createUser:createUser·p0.95    sample          4.768           ms/op
Client.createUser:createUser·p0.99    sample          9.923           ms/op
Client.createUser:createUser·p0.999   sample         18.315           ms/op
Client.createUser:createUser·p0.9999  sample         18.842           ms/op
Client.createUser:createUser·p1.00    sample         18.842           ms/op
Client.existUser                      sample  14776   2.163 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.528           ms/op
Client.existUser:existUser·p0.50      sample          2.154           ms/op
Client.existUser:existUser·p0.90      sample          2.647           ms/op
Client.existUser:existUser·p0.95      sample          2.793           ms/op
Client.existUser:existUser·p0.99      sample          3.311           ms/op
Client.existUser:existUser·p0.999     sample          7.609           ms/op
Client.existUser:existUser·p0.9999    sample          8.548           ms/op
Client.existUser:existUser·p1.00      sample          8.716           ms/op
Client.getUser                        sample  10393   3.072 ± 0.043   ms/op
Client.getUser:getUser·p0.00          sample          0.912           ms/op
Client.getUser:getUser·p0.50          sample          2.986           ms/op
Client.getUser:getUser·p0.90          sample          3.723           ms/op
Client.getUser:getUser·p0.95          sample          3.985           ms/op
Client.getUser:getUser·p0.99          sample          5.768           ms/op
Client.getUser:getUser·p0.999         sample         23.953           ms/op
Client.getUser:getUser·p0.9999        sample         24.627           ms/op
Client.getUser:getUser·p1.00          sample         24.642           ms/op
Client.listUser                       sample   3829   8.387 ± 0.129   ms/op
Client.listUser:listUser·p0.00        sample          1.712           ms/op
Client.listUser:listUser·p0.50        sample          7.954           ms/op
Client.listUser:listUser·p0.90        sample         11.485           ms/op
Client.listUser:listUser·p0.95        sample         12.796           ms/op
Client.listUser:listUser·p0.99        sample         15.878           ms/op
Client.listUser:listUser·p0.999       sample         21.750           ms/op
Client.listUser:listUser·p0.9999      sample         22.774           ms/op
Client.listUser:listUser·p1.00        sample         22.774           ms/op
