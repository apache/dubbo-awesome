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
# Warmup Iteration   1: 2.275 ops/ms
Iteration   1: 5.815 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.815 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.616 ops/ms
Iteration   1: 13.483 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.483 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ops/ms
Iteration   1: 8.472 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.472 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.176 ops/ms
Iteration   1: 3.967 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.967 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.705 ±(99.9%) 0.093 ms/op
Iteration   1: 3.251 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.251 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.574 ±(99.9%) 0.040 ms/op
Iteration   1: 1.900 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.900 ms/op


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
# Warmup Iteration   1: 4.716 ±(99.9%) 0.065 ms/op
Iteration   1: 3.059 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.059 ms/op


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
# Warmup Iteration   1: 12.870 ±(99.9%) 0.432 ms/op
Iteration   1: 9.031 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.031 ms/op


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.100 ms/op
Iteration   1: 2.921 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   2.781 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   7.332 ms/op
                 createUser·p0.999:  10.076 ms/op
                 createUser·p0.9999: 10.107 ms/op
                 createUser·p1.00:   10.109 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11181
  mean =      2.921 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 12 
    [ 1.000,  2.000) = 951 
    [ 2.000,  3.000) = 5725 
    [ 3.000,  4.000) = 3889 
    [ 4.000,  5.000) = 325 
    [ 5.000,  6.000) = 77 
    [ 6.000,  7.000) = 75 
    [ 7.000,  8.000) = 20 
    [ 8.000,  9.000) = 43 
    [ 9.000, 10.000) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     10.076 ms/op
     p(99.9900) =     10.107 ms/op
     p(99.9990) =     10.109 ms/op
     p(99.9999) =     10.109 ms/op
    p(100.0000) =     10.109 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.071 ms/op
Iteration   1: 1.808 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.245 ms/op
                 existUser·p0.95:   2.388 ms/op
                 existUser·p0.99:   3.011 ms/op
                 existUser·p0.999:  18.088 ms/op
                 existUser·p0.9999: 18.193 ms/op
                 existUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17995
  mean =      1.808 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1127 
    [ 1.250,  2.500) = 16302 
    [ 2.500,  3.750) = 494 
    [ 3.750,  5.000) = 4 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.388 ms/op
     p(99.0000) =      3.011 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     18.193 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.117 ms/op
Iteration   1: 3.023 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.685 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.812 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  6.841 ms/op
                 getUser·p0.9999: 8.437 ms/op
                 getUser·p1.00:   8.520 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10586
  mean =      3.023 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 115 
    [2.000, 2.500) = 1350 
    [2.500, 3.000) = 3908 
    [3.000, 3.500) = 3831 
    [3.500, 4.000) = 1000 
    [4.000, 4.500) = 151 
    [4.500, 5.000) = 61 
    [5.000, 5.500) = 74 
    [5.500, 6.000) = 34 
    [6.000, 6.500) = 18 
    [6.500, 7.000) = 24 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.812 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =      6.841 ms/op
     p(99.9900) =      8.437 ms/op
     p(99.9990) =      8.520 ms/op
     p(99.9999) =      8.520 ms/op
    p(100.0000) =      8.520 ms/op


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
# Warmup Iteration   1: 12.091 ±(99.9%) 0.435 ms/op
Iteration   1: 8.192 ±(99.9%) 0.124 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   7.799 ms/op
                 listUser·p0.90:   10.822 ms/op
                 listUser·p0.95:   11.862 ms/op
                 listUser·p0.99:   17.324 ms/op
                 listUser·p0.999:  29.197 ms/op
                 listUser·p0.9999: 32.571 ms/op
                 listUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4014
  mean =      8.192 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 114 
    [ 5.000,  7.500) = 1618 
    [ 7.500, 10.000) = 1616 
    [10.000, 12.500) = 519 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.773 ms/op
     p(50.0000) =      7.799 ms/op
     p(90.0000) =     10.822 ms/op
     p(95.0000) =     11.862 ms/op
     p(99.0000) =     17.324 ms/op
     p(99.9000) =     29.197 ms/op
     p(99.9900) =     32.571 ms/op
     p(99.9990) =     32.571 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.815          ops/ms
Client.existUser                       thrpt         13.483          ops/ms
Client.getUser                         thrpt          8.472          ops/ms
Client.listUser                        thrpt          3.967          ops/ms
Client.createUser                       avgt          3.251           ms/op
Client.existUser                        avgt          1.900           ms/op
Client.getUser                          avgt          3.059           ms/op
Client.listUser                         avgt          9.031           ms/op
Client.createUser                     sample  11181   2.921 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          0.860           ms/op
Client.createUser:createUser·p0.50    sample          2.781           ms/op
Client.createUser:createUser·p0.90    sample          3.699           ms/op
Client.createUser:createUser·p0.95    sample          4.063           ms/op
Client.createUser:createUser·p0.99    sample          7.332           ms/op
Client.createUser:createUser·p0.999   sample         10.076           ms/op
Client.createUser:createUser·p0.9999  sample         10.107           ms/op
Client.createUser:createUser·p1.00    sample         10.109           ms/op
Client.existUser                      sample  17995   1.808 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.558           ms/op
Client.existUser:existUser·p0.50      sample          1.749           ms/op
Client.existUser:existUser·p0.90      sample          2.245           ms/op
Client.existUser:existUser·p0.95      sample          2.388           ms/op
Client.existUser:existUser·p0.99      sample          3.011           ms/op
Client.existUser:existUser·p0.999     sample         18.088           ms/op
Client.existUser:existUser·p0.9999    sample         18.193           ms/op
Client.existUser:existUser·p1.00      sample         18.219           ms/op
Client.getUser                        sample  10586   3.023 ± 0.018   ms/op
Client.getUser:getUser·p0.00          sample          0.685           ms/op
Client.getUser:getUser·p0.50          sample          2.990           ms/op
Client.getUser:getUser·p0.90          sample          3.572           ms/op
Client.getUser:getUser·p0.95          sample          3.812           ms/op
Client.getUser:getUser·p0.99          sample          5.390           ms/op
Client.getUser:getUser·p0.999         sample          6.841           ms/op
Client.getUser:getUser·p0.9999        sample          8.437           ms/op
Client.getUser:getUser·p1.00          sample          8.520           ms/op
Client.listUser                       sample   4014   8.192 ± 0.124   ms/op
Client.listUser:listUser·p0.00        sample          2.773           ms/op
Client.listUser:listUser·p0.50        sample          7.799           ms/op
Client.listUser:listUser·p0.90        sample         10.822           ms/op
Client.listUser:listUser·p0.95        sample         11.862           ms/op
Client.listUser:listUser·p0.99        sample         17.324           ms/op
Client.listUser:listUser·p0.999       sample         29.197           ms/op
Client.listUser:listUser·p0.9999      sample         32.571           ms/op
Client.listUser:listUser·p1.00        sample         32.571           ms/op
