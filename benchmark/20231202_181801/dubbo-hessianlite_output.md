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
# Warmup Iteration   1: 2.400 ops/ms
Iteration   1: 5.649 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.649 ops/ms


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
# Warmup Iteration   1: 5.817 ops/ms
Iteration   1: 12.097 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.097 ops/ms


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
# Warmup Iteration   1: 3.868 ops/ms
Iteration   1: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.146 ops/ms


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
# Warmup Iteration   1: 2.126 ops/ms
Iteration   1: 3.202 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.202 ops/ms


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
# Warmup Iteration   1: 5.517 ±(99.9%) 0.070 ms/op
Iteration   1: 3.290 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.290 ms/op


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.032 ms/op
Iteration   1: 2.062 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.062 ms/op


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
# Warmup Iteration   1: 5.098 ±(99.9%) 0.059 ms/op
Iteration   1: 3.010 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.010 ms/op


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
# Warmup Iteration   1: 12.373 ±(99.9%) 0.187 ms/op
Iteration   1: 8.064 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.064 ms/op


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.102 ms/op
Iteration   1: 2.938 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.802 ms/op
                 createUser·p0.90:   3.786 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  9.710 ms/op
                 createUser·p0.9999: 13.831 ms/op
                 createUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10867
  mean =      2.938 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 2688 
    [ 2.500,  3.750) = 6961 
    [ 3.750,  5.000) = 1051 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.802 ms/op
     p(90.0000) =      3.786 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =      9.710 ms/op
     p(99.9900) =     13.831 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.068 ms/op
Iteration   1: 1.883 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.436 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.524 ms/op
                 existUser·p0.95:   2.757 ms/op
                 existUser·p0.99:   3.187 ms/op
                 existUser·p0.999:  4.900 ms/op
                 existUser·p0.9999: 5.926 ms/op
                 existUser·p1.00:   6.709 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16978
  mean =      1.883 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 183 
    [1.000, 1.500) = 2892 
    [1.500, 2.000) = 8267 
    [2.000, 2.500) = 3831 
    [2.500, 3.000) = 1476 
    [3.000, 3.500) = 206 
    [3.500, 4.000) = 41 
    [4.000, 4.500) = 1 
    [4.500, 5.000) = 68 
    [5.000, 5.500) = 10 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.524 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.187 ms/op
     p(99.9000) =      4.900 ms/op
     p(99.9900) =      5.926 ms/op
     p(99.9990) =      6.709 ms/op
     p(99.9999) =      6.709 ms/op
    p(100.0000) =      6.709 ms/op


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
# Warmup Iteration   1: 4.532 ±(99.9%) 0.109 ms/op
Iteration   1: 3.283 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.501 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.616 ms/op
                 getUser·p0.999:  7.030 ms/op
                 getUser·p0.9999: 10.519 ms/op
                 getUser·p1.00:   10.519 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9843
  mean =      3.283 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 1244 
    [ 2.500,  3.750) = 6660 
    [ 3.750,  5.000) = 1731 
    [ 5.000,  6.250) = 139 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.616 ms/op
     p(99.9000) =      7.030 ms/op
     p(99.9900) =     10.519 ms/op
     p(99.9990) =     10.519 ms/op
     p(99.9999) =     10.519 ms/op
    p(100.0000) =     10.519 ms/op


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
# Warmup Iteration   1: 12.890 ±(99.9%) 0.472 ms/op
Iteration   1: 8.300 ±(99.9%) 0.125 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   7.946 ms/op
                 listUser·p0.90:   10.600 ms/op
                 listUser·p0.95:   11.862 ms/op
                 listUser·p0.99:   19.606 ms/op
                 listUser·p0.999:  24.375 ms/op
                 listUser·p0.9999: 28.803 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3832
  mean =      8.300 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 97 
    [ 5.000,  7.500) = 1369 
    [ 7.500, 10.000) = 1784 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.109 ms/op
     p(50.0000) =      7.946 ms/op
     p(90.0000) =     10.600 ms/op
     p(95.0000) =     11.862 ms/op
     p(99.0000) =     19.606 ms/op
     p(99.9000) =     24.375 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.649          ops/ms
Client.existUser                       thrpt         12.097          ops/ms
Client.getUser                         thrpt          8.146          ops/ms
Client.listUser                        thrpt          3.202          ops/ms
Client.createUser                       avgt          3.290           ms/op
Client.existUser                        avgt          2.062           ms/op
Client.getUser                          avgt          3.010           ms/op
Client.listUser                         avgt          8.064           ms/op
Client.createUser                     sample  10867   2.938 ± 0.024   ms/op
Client.createUser:createUser·p0.00    sample          0.873           ms/op
Client.createUser:createUser·p0.50    sample          2.802           ms/op
Client.createUser:createUser·p0.90    sample          3.786           ms/op
Client.createUser:createUser·p0.95    sample          4.067           ms/op
Client.createUser:createUser·p0.99    sample          5.243           ms/op
Client.createUser:createUser·p0.999   sample          9.710           ms/op
Client.createUser:createUser·p0.9999  sample         13.831           ms/op
Client.createUser:createUser·p1.00    sample         14.025           ms/op
Client.existUser                      sample  16978   1.883 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.436           ms/op
Client.existUser:existUser·p0.50      sample          1.786           ms/op
Client.existUser:existUser·p0.90      sample          2.524           ms/op
Client.existUser:existUser·p0.95      sample          2.757           ms/op
Client.existUser:existUser·p0.99      sample          3.187           ms/op
Client.existUser:existUser·p0.999     sample          4.900           ms/op
Client.existUser:existUser·p0.9999    sample          5.926           ms/op
Client.existUser:existUser·p1.00      sample          6.709           ms/op
Client.getUser                        sample   9843   3.283 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.501           ms/op
Client.getUser:getUser·p0.50          sample          3.289           ms/op
Client.getUser:getUser·p0.90          sample          4.063           ms/op
Client.getUser:getUser·p0.95          sample          4.325           ms/op
Client.getUser:getUser·p0.99          sample          5.616           ms/op
Client.getUser:getUser·p0.999         sample          7.030           ms/op
Client.getUser:getUser·p0.9999        sample         10.519           ms/op
Client.getUser:getUser·p1.00          sample         10.519           ms/op
Client.listUser                       sample   3832   8.300 ± 0.125   ms/op
Client.listUser:listUser·p0.00        sample          2.109           ms/op
Client.listUser:listUser·p0.50        sample          7.946           ms/op
Client.listUser:listUser·p0.90        sample         10.600           ms/op
Client.listUser:listUser·p0.95        sample         11.862           ms/op
Client.listUser:listUser·p0.99        sample         19.606           ms/op
Client.listUser:listUser·p0.999       sample         24.375           ms/op
Client.listUser:listUser·p0.9999      sample         28.803           ms/op
Client.listUser:listUser·p1.00        sample         28.803           ms/op
