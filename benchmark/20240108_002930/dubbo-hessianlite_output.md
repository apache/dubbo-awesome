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
# Warmup Iteration   1: 2.493 ops/ms
Iteration   1: 6.103 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.103 ops/ms


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
# Warmup Iteration   1: 6.507 ops/ms
Iteration   1: 12.764 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.764 ops/ms


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
# Warmup Iteration   1: 4.355 ops/ms
Iteration   1: 9.278 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.278 ops/ms


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
# Warmup Iteration   1: 2.243 ops/ms
Iteration   1: 4.002 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.002 ops/ms


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
# Warmup Iteration   1: 5.146 ±(99.9%) 0.092 ms/op
Iteration   1: 3.147 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.147 ms/op


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
# Warmup Iteration   1: 3.454 ±(99.9%) 0.033 ms/op
Iteration   1: 2.185 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.185 ms/op


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
# Warmup Iteration   1: 4.771 ±(99.9%) 0.066 ms/op
Iteration   1: 2.869 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.869 ms/op


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
# Warmup Iteration   1: 11.930 ±(99.9%) 0.212 ms/op
Iteration   1: 6.997 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  6.997 ms/op


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.120 ms/op
Iteration   1: 2.985 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.753 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  19.969 ms/op
                 createUser·p0.9999: 21.323 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10698
  mean =      2.985 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3130 
    [ 2.500,  5.000) = 7296 
    [ 5.000,  7.500) = 205 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     19.969 ms/op
     p(99.9900) =     21.323 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.097 ms/op
Iteration   1: 1.828 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   3.440 ms/op
                 existUser·p0.999:  4.985 ms/op
                 existUser·p0.9999: 8.161 ms/op
                 existUser·p1.00:   8.167 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17502
  mean =      1.828 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 6 
    [1.000, 1.500) = 3310 
    [1.500, 2.000) = 9425 
    [2.000, 2.500) = 3628 
    [2.500, 3.000) = 877 
    [3.000, 3.500) = 100 
    [3.500, 4.000) = 66 
    [4.000, 4.500) = 51 
    [4.500, 5.000) = 24 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      3.440 ms/op
     p(99.9000) =      4.985 ms/op
     p(99.9900) =      8.161 ms/op
     p(99.9990) =      8.167 ms/op
     p(99.9999) =      8.167 ms/op
    p(100.0000) =      8.167 ms/op


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.121 ms/op
Iteration   1: 3.019 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  29.184 ms/op
                 getUser·p0.9999: 29.424 ms/op
                 getUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10596
  mean =      3.019 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2608 
    [ 2.500,  5.000) = 7869 
    [ 5.000,  7.500) = 87 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     29.184 ms/op
     p(99.9900) =     29.424 ms/op
     p(99.9990) =     29.426 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 10.656 ±(99.9%) 0.322 ms/op
Iteration   1: 8.062 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   7.807 ms/op
                 listUser·p0.90:   10.371 ms/op
                 listUser·p0.95:   11.289 ms/op
                 listUser·p0.99:   18.067 ms/op
                 listUser·p0.999:  23.427 ms/op
                 listUser·p0.9999: 25.788 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4031
  mean =      8.062 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 179 
    [ 5.000,  7.500) = 1525 
    [ 7.500, 10.000) = 1788 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.261 ms/op
     p(50.0000) =      7.807 ms/op
     p(90.0000) =     10.371 ms/op
     p(95.0000) =     11.289 ms/op
     p(99.0000) =     18.067 ms/op
     p(99.9000) =     23.427 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.103          ops/ms
Client.existUser                       thrpt         12.764          ops/ms
Client.getUser                         thrpt          9.278          ops/ms
Client.listUser                        thrpt          4.002          ops/ms
Client.createUser                       avgt          3.147           ms/op
Client.existUser                        avgt          2.185           ms/op
Client.getUser                          avgt          2.869           ms/op
Client.listUser                         avgt          6.997           ms/op
Client.createUser                     sample  10698   2.985 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          0.794           ms/op
Client.createUser:createUser·p0.50    sample          2.753           ms/op
Client.createUser:createUser·p0.90    sample          3.793           ms/op
Client.createUser:createUser·p0.95    sample          4.178           ms/op
Client.createUser:createUser·p0.99    sample          6.603           ms/op
Client.createUser:createUser·p0.999   sample         19.969           ms/op
Client.createUser:createUser·p0.9999  sample         21.323           ms/op
Client.createUser:createUser·p1.00    sample         21.332           ms/op
Client.existUser                      sample  17502   1.828 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.870           ms/op
Client.existUser:existUser·p0.50      sample          1.716           ms/op
Client.existUser:existUser·p0.90      sample          2.380           ms/op
Client.existUser:existUser·p0.95      sample          2.560           ms/op
Client.existUser:existUser·p0.99      sample          3.440           ms/op
Client.existUser:existUser·p0.999     sample          4.985           ms/op
Client.existUser:existUser·p0.9999    sample          8.161           ms/op
Client.existUser:existUser·p1.00      sample          8.167           ms/op
Client.getUser                        sample  10596   3.019 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample          0.816           ms/op
Client.getUser:getUser·p0.50          sample          2.974           ms/op
Client.getUser:getUser·p0.90          sample          3.781           ms/op
Client.getUser:getUser·p0.95          sample          3.994           ms/op
Client.getUser:getUser·p0.99          sample          5.186           ms/op
Client.getUser:getUser·p0.999         sample         29.184           ms/op
Client.getUser:getUser·p0.9999        sample         29.424           ms/op
Client.getUser:getUser·p1.00          sample         29.426           ms/op
Client.listUser                       sample   4031   8.062 ± 0.119   ms/op
Client.listUser:listUser·p0.00        sample          2.261           ms/op
Client.listUser:listUser·p0.50        sample          7.807           ms/op
Client.listUser:listUser·p0.90        sample         10.371           ms/op
Client.listUser:listUser·p0.95        sample         11.289           ms/op
Client.listUser:listUser·p0.99        sample         18.067           ms/op
Client.listUser:listUser·p0.999       sample         23.427           ms/op
Client.listUser:listUser·p0.9999      sample         25.788           ms/op
Client.listUser:listUser·p1.00        sample         25.788           ms/op
