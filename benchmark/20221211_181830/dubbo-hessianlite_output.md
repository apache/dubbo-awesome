# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.060 ops/ms
Iteration   1: 3.334 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.334 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ops/ms
Iteration   1: 8.412 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.412 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.623 ops/ms
Iteration   1: 5.770 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.770 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 0.879 ops/ms
Iteration   1: 1.205 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.205 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 14.812 ±(99.9%) 0.250 ms/op
Iteration   1: 6.497 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.497 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.507 ±(99.9%) 0.062 ms/op
Iteration   1: 3.615 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.572 ±(99.9%) 0.145 ms/op
Iteration   1: 4.646 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.646 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 24.664 ±(99.9%) 0.492 ms/op
Iteration   1: 17.811 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.811 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.250 ±(99.9%) 0.311 ms/op
Iteration   1: 5.276 ±(99.9%) 0.097 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   5.046 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   8.767 ms/op
                 createUser·p0.99:   15.925 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6128
  mean =      5.276 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 46 
    [ 2.500,  3.750) = 817 
    [ 3.750,  5.000) = 2066 
    [ 5.000,  6.250) = 2704 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 131 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      8.767 ms/op
     p(99.0000) =     15.925 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 6.314 ±(99.9%) 0.146 ms/op
Iteration   1: 3.108 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  17.793 ms/op
                 existUser·p0.9999: 18.117 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10329
  mean =      3.108 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 2074 
    [ 2.500,  3.750) = 7470 
    [ 3.750,  5.000) = 453 
    [ 5.000,  6.250) = 210 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     18.117 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 9.550 ±(99.9%) 0.320 ms/op
Iteration   1: 4.768 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 9.273 ms/op
                 getUser·p1.00:   9.273 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6714
  mean =      4.768 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 0 
    [ 1.500,  2.000) = 2 
    [ 2.000,  2.500) = 9 
    [ 2.500,  3.000) = 17 
    [ 3.000,  3.500) = 51 
    [ 3.500,  4.000) = 613 
    [ 4.000,  4.500) = 1577 
    [ 4.500,  5.000) = 2554 
    [ 5.000,  5.500) = 1186 
    [ 5.500,  6.000) = 445 
    [ 6.000,  6.500) = 154 
    [ 6.500,  7.000) = 23 
    [ 7.000,  7.500) = 20 
    [ 7.500,  8.000) = 13 
    [ 8.000,  8.500) = 34 
    [ 8.500,  9.000) = 13 
    [ 9.000,  9.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.825 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =      9.273 ms/op
     p(99.9990) =      9.273 ms/op
     p(99.9999) =      9.273 ms/op
    p(100.0000) =      9.273 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 27.629 ±(99.9%) 1.157 ms/op
Iteration   1: 17.067 ±(99.9%) 0.335 ms/op
                 listUser·p0.00:   9.667 ms/op
                 listUser·p0.50:   15.122 ms/op
                 listUser·p0.90:   22.499 ms/op
                 listUser·p0.95:   27.420 ms/op
                 listUser·p0.99:   33.751 ms/op
                 listUser·p0.999:  36.671 ms/op
                 listUser·p0.9999: 37.814 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1871
  mean =     17.067 ±(99.9%) 0.335 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 854 
    [15.000, 17.500) = 308 
    [17.500, 20.000) = 393 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      9.667 ms/op
     p(50.0000) =     15.122 ms/op
     p(90.0000) =     22.499 ms/op
     p(95.0000) =     27.420 ms/op
     p(99.0000) =     33.751 ms/op
     p(99.9000) =     36.671 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.334          ops/ms
Client.existUser                       thrpt          8.412          ops/ms
Client.getUser                         thrpt          5.770          ops/ms
Client.listUser                        thrpt          1.205          ops/ms
Client.createUser                       avgt          6.497           ms/op
Client.existUser                        avgt          3.615           ms/op
Client.getUser                          avgt          4.646           ms/op
Client.listUser                         avgt         17.811           ms/op
Client.createUser                     sample   6128   5.276 ± 0.097   ms/op
Client.createUser:createUser·p0.00    sample          1.716           ms/op
Client.createUser:createUser·p0.50    sample          5.046           ms/op
Client.createUser:createUser·p0.90    sample          5.669           ms/op
Client.createUser:createUser·p0.95    sample          8.767           ms/op
Client.createUser:createUser·p0.99    sample         15.925           ms/op
Client.createUser:createUser·p0.999   sample         19.988           ms/op
Client.createUser:createUser·p0.9999  sample         19.988           ms/op
Client.createUser:createUser·p1.00    sample         19.988           ms/op
Client.existUser                      sample  10329   3.108 ± 0.037   ms/op
Client.existUser:existUser·p0.00      sample          0.906           ms/op
Client.existUser:existUser·p0.50      sample          3.142           ms/op
Client.existUser:existUser·p0.90      sample          3.604           ms/op
Client.existUser:existUser·p0.95      sample          3.973           ms/op
Client.existUser:existUser·p0.99      sample          6.259           ms/op
Client.existUser:existUser·p0.999     sample         17.793           ms/op
Client.existUser:existUser·p0.9999    sample         18.117           ms/op
Client.existUser:existUser·p1.00      sample         18.121           ms/op
Client.getUser                        sample   6714   4.768 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          1.825           ms/op
Client.getUser:getUser·p0.50          sample          4.686           ms/op
Client.getUser:getUser·p0.90          sample          5.530           ms/op
Client.getUser:getUser·p0.95          sample          5.890           ms/op
Client.getUser:getUser·p0.99          sample          7.438           ms/op
Client.getUser:getUser·p0.999         sample          8.864           ms/op
Client.getUser:getUser·p0.9999        sample          9.273           ms/op
Client.getUser:getUser·p1.00          sample          9.273           ms/op
Client.listUser                       sample   1871  17.067 ± 0.335   ms/op
Client.listUser:listUser·p0.00        sample          9.667           ms/op
Client.listUser:listUser·p0.50        sample         15.122           ms/op
Client.listUser:listUser·p0.90        sample         22.499           ms/op
Client.listUser:listUser·p0.95        sample         27.420           ms/op
Client.listUser:listUser·p0.99        sample         33.751           ms/op
Client.listUser:listUser·p0.999       sample         36.671           ms/op
Client.listUser:listUser·p0.9999      sample         37.814           ms/op
Client.listUser:listUser·p1.00        sample         37.814           ms/op
