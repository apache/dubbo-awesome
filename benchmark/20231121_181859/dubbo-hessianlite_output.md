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
# Warmup Iteration   1: 2.574 ops/ms
Iteration   1: 6.245 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.245 ops/ms


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
# Warmup Iteration   1: 6.786 ops/ms
Iteration   1: 12.916 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.916 ops/ms


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
# Warmup Iteration   1: 4.441 ops/ms
Iteration   1: 8.942 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.942 ops/ms


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
# Warmup Iteration   1: 2.134 ops/ms
Iteration   1: 4.530 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.530 ops/ms


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.080 ms/op
Iteration   1: 3.208 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.208 ms/op


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
# Warmup Iteration   1: 3.008 ±(99.9%) 0.035 ms/op
Iteration   1: 2.021 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.021 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.590 ±(99.9%) 0.040 ms/op
Iteration   1: 2.887 ±(99.9%) 0.010 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.357 ±(99.9%) 0.235 ms/op
Iteration   1: 8.066 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.066 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.812 ±(99.9%) 0.081 ms/op
Iteration   1: 3.064 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   2.798 ms/op
                 createUser·p0.90:   3.799 ms/op
                 createUser·p0.95:   4.520 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  12.095 ms/op
                 createUser·p0.9999: 17.668 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10403
  mean =      3.064 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1783 
    [ 2.500,  3.750) = 7425 
    [ 3.750,  5.000) = 860 
    [ 5.000,  6.250) = 196 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.799 ms/op
     p(95.0000) =      4.520 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.095 ms/op
     p(99.9900) =     17.668 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.479 ±(99.9%) 0.066 ms/op
Iteration   1: 1.710 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   1.589 ms/op
                 existUser·p0.90:   2.101 ms/op
                 existUser·p0.95:   2.331 ms/op
                 existUser·p0.99:   2.847 ms/op
                 existUser·p0.999:  24.946 ms/op
                 existUser·p0.9999: 25.945 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18715
  mean =      1.710 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18170 
    [ 2.500,  5.000) = 446 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      1.589 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.331 ms/op
     p(99.0000) =      2.847 ms/op
     p(99.9000) =     24.946 ms/op
     p(99.9900) =     25.945 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.099 ms/op
Iteration   1: 2.845 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  8.310 ms/op
                 getUser·p0.9999: 9.983 ms/op
                 getUser·p1.00:   10.158 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11569
  mean =      2.845 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 9 
    [ 1.000,  2.000) = 548 
    [ 2.000,  3.000) = 7515 
    [ 3.000,  4.000) = 2780 
    [ 4.000,  5.000) = 482 
    [ 5.000,  6.000) = 166 
    [ 6.000,  7.000) = 26 
    [ 7.000,  8.000) = 11 
    [ 8.000,  9.000) = 28 
    [ 9.000, 10.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      8.310 ms/op
     p(99.9900) =      9.983 ms/op
     p(99.9990) =     10.158 ms/op
     p(99.9999) =     10.158 ms/op
    p(100.0000) =     10.158 ms/op


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
# Warmup Iteration   1: 11.434 ±(99.9%) 0.583 ms/op
Iteration   1: 7.317 ±(99.9%) 0.094 ms/op
                 listUser·p0.00:   3.076 ms/op
                 listUser·p0.50:   7.029 ms/op
                 listUser·p0.90:   9.568 ms/op
                 listUser·p0.95:   10.486 ms/op
                 listUser·p0.99:   14.533 ms/op
                 listUser·p0.999:  18.109 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4362
  mean =      7.317 ±(99.9%) 0.094 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 293 
    [ 5.000,  7.500) = 2379 
    [ 7.500, 10.000) = 1381 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.076 ms/op
     p(50.0000) =      7.029 ms/op
     p(90.0000) =      9.568 ms/op
     p(95.0000) =     10.486 ms/op
     p(99.0000) =     14.533 ms/op
     p(99.9000) =     18.109 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.245          ops/ms
Client.existUser                       thrpt         12.916          ops/ms
Client.getUser                         thrpt          8.942          ops/ms
Client.listUser                        thrpt          4.530          ops/ms
Client.createUser                       avgt          3.208           ms/op
Client.existUser                        avgt          2.021           ms/op
Client.getUser                          avgt          2.887           ms/op
Client.listUser                         avgt          8.066           ms/op
Client.createUser                     sample  10403   3.064 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.225           ms/op
Client.createUser:createUser·p0.50    sample          2.798           ms/op
Client.createUser:createUser·p0.90    sample          3.799           ms/op
Client.createUser:createUser·p0.95    sample          4.520           ms/op
Client.createUser:createUser·p0.99    sample          6.578           ms/op
Client.createUser:createUser·p0.999   sample         12.095           ms/op
Client.createUser:createUser·p0.9999  sample         17.668           ms/op
Client.createUser:createUser·p1.00    sample         17.760           ms/op
Client.existUser                      sample  18715   1.710 ± 0.028   ms/op
Client.existUser:existUser·p0.00      sample          0.521           ms/op
Client.existUser:existUser·p0.50      sample          1.589           ms/op
Client.existUser:existUser·p0.90      sample          2.101           ms/op
Client.existUser:existUser·p0.95      sample          2.331           ms/op
Client.existUser:existUser·p0.99      sample          2.847           ms/op
Client.existUser:existUser·p0.999     sample         24.946           ms/op
Client.existUser:existUser·p0.9999    sample         25.945           ms/op
Client.existUser:existUser·p1.00      sample         26.116           ms/op
Client.getUser                        sample  11569   2.845 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.617           ms/op
Client.getUser:getUser·p0.50          sample          2.617           ms/op
Client.getUser:getUser·p0.90          sample          3.764           ms/op
Client.getUser:getUser·p0.95          sample          4.096           ms/op
Client.getUser:getUser·p0.99          sample          5.415           ms/op
Client.getUser:getUser·p0.999         sample          8.310           ms/op
Client.getUser:getUser·p0.9999        sample          9.983           ms/op
Client.getUser:getUser·p1.00          sample         10.158           ms/op
Client.listUser                       sample   4362   7.317 ± 0.094   ms/op
Client.listUser:listUser·p0.00        sample          3.076           ms/op
Client.listUser:listUser·p0.50        sample          7.029           ms/op
Client.listUser:listUser·p0.90        sample          9.568           ms/op
Client.listUser:listUser·p0.95        sample         10.486           ms/op
Client.listUser:listUser·p0.99        sample         14.533           ms/op
Client.listUser:listUser·p0.999       sample         18.109           ms/op
Client.listUser:listUser·p0.9999      sample         23.200           ms/op
Client.listUser:listUser·p1.00        sample         23.200           ms/op
