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
# Warmup Iteration   1: 2.689 ops/ms
Iteration   1: 6.440 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.440 ops/ms


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
# Warmup Iteration   1: 6.208 ops/ms
Iteration   1: 12.547 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.547 ops/ms


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
# Warmup Iteration   1: 4.531 ops/ms
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
# Warmup Iteration   1: 2.326 ops/ms
Iteration   1: 4.032 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.032 ops/ms


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
# Warmup Iteration   1: 5.632 ±(99.9%) 0.064 ms/op
Iteration   1: 3.090 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.090 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.033 ms/op
Iteration   1: 1.838 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.838 ms/op


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
# Warmup Iteration   1: 4.952 ±(99.9%) 0.066 ms/op
Iteration   1: 2.567 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.567 ms/op


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
# Warmup Iteration   1: 11.246 ±(99.9%) 0.147 ms/op
Iteration   1: 7.663 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.663 ms/op


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.120 ms/op
Iteration   1: 2.779 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   3.176 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   11.780 ms/op
                 createUser·p0.999:  30.523 ms/op
                 createUser·p0.9999: 32.014 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11496
  mean =      2.779 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5663 
    [ 2.500,  5.000) = 5571 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.176 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =     11.780 ms/op
     p(99.9000) =     30.523 ms/op
     p(99.9900) =     32.014 ms/op
     p(99.9990) =     32.014 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 3.001 ±(99.9%) 0.064 ms/op
Iteration   1: 2.038 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   1.968 ms/op
                 existUser·p0.90:   2.818 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.509 ms/op
                 existUser·p0.999:  17.924 ms/op
                 existUser·p0.9999: 19.511 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15718
  mean =      2.038 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 745 
    [ 1.250,  2.500) = 12838 
    [ 2.500,  3.750) = 2061 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.509 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     19.511 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.122 ms/op
Iteration   1: 3.064 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.683 ms/op
                 getUser·p0.999:  24.920 ms/op
                 getUser·p0.9999: 25.580 ms/op
                 getUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10513
  mean =      3.064 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2548 
    [ 2.500,  5.000) = 7800 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.683 ms/op
     p(99.9000) =     24.920 ms/op
     p(99.9900) =     25.580 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 11.542 ±(99.9%) 0.366 ms/op
Iteration   1: 7.553 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   7.004 ms/op
                 listUser·p0.90:   10.240 ms/op
                 listUser·p0.95:   11.174 ms/op
                 listUser·p0.99:   20.709 ms/op
                 listUser·p0.999:  23.749 ms/op
                 listUser·p0.9999: 23.986 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4232
  mean =      7.553 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 268 
    [ 5.000,  7.500) = 2261 
    [ 7.500, 10.000) = 1214 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.830 ms/op
     p(50.0000) =      7.004 ms/op
     p(90.0000) =     10.240 ms/op
     p(95.0000) =     11.174 ms/op
     p(99.0000) =     20.709 ms/op
     p(99.9000) =     23.749 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.440          ops/ms
Client.existUser                       thrpt         12.547          ops/ms
Client.getUser                         thrpt          7.909          ops/ms
Client.listUser                        thrpt          4.032          ops/ms
Client.createUser                       avgt          3.090           ms/op
Client.existUser                        avgt          1.838           ms/op
Client.getUser                          avgt          2.567           ms/op
Client.listUser                         avgt          7.663           ms/op
Client.createUser                     sample  11496   2.779 ± 0.056   ms/op
Client.createUser:createUser·p0.00    sample          0.948           ms/op
Client.createUser:createUser·p0.50    sample          2.507           ms/op
Client.createUser:createUser·p0.90    sample          3.176           ms/op
Client.createUser:createUser·p0.95    sample          3.985           ms/op
Client.createUser:createUser·p0.99    sample         11.780           ms/op
Client.createUser:createUser·p0.999   sample         30.523           ms/op
Client.createUser:createUser·p0.9999  sample         32.014           ms/op
Client.createUser:createUser·p1.00    sample         32.014           ms/op
Client.existUser                      sample  15718   2.038 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.569           ms/op
Client.existUser:existUser·p0.50      sample          1.968           ms/op
Client.existUser:existUser·p0.90      sample          2.818           ms/op
Client.existUser:existUser·p0.95      sample          3.088           ms/op
Client.existUser:existUser·p0.99      sample          3.509           ms/op
Client.existUser:existUser·p0.999     sample         17.924           ms/op
Client.existUser:existUser·p0.9999    sample         19.511           ms/op
Client.existUser:existUser·p1.00      sample         19.530           ms/op
Client.getUser                        sample  10513   3.064 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample          0.645           ms/op
Client.getUser:getUser·p0.50          sample          2.966           ms/op
Client.getUser:getUser·p0.90          sample          3.867           ms/op
Client.getUser:getUser·p0.95          sample          4.219           ms/op
Client.getUser:getUser·p0.99          sample          5.683           ms/op
Client.getUser:getUser·p0.999         sample         24.920           ms/op
Client.getUser:getUser·p0.9999        sample         25.580           ms/op
Client.getUser:getUser·p1.00          sample         25.592           ms/op
Client.listUser                       sample   4232   7.553 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          2.830           ms/op
Client.listUser:listUser·p0.50        sample          7.004           ms/op
Client.listUser:listUser·p0.90        sample         10.240           ms/op
Client.listUser:listUser·p0.95        sample         11.174           ms/op
Client.listUser:listUser·p0.99        sample         20.709           ms/op
Client.listUser:listUser·p0.999       sample         23.749           ms/op
Client.listUser:listUser·p0.9999      sample         23.986           ms/op
Client.listUser:listUser·p1.00        sample         23.986           ms/op
