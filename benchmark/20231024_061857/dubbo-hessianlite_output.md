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
# Warmup Iteration   1: 1.272 ops/ms
Iteration   1: 3.696 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.696 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 3.571 ops/ms
Iteration   1: 9.155 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.155 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 2.601 ops/ms
Iteration   1: 4.858 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.858 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.110 ops/ms
Iteration   1: 1.624 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.624 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 11.907 ±(99.9%) 0.255 ms/op
Iteration   1: 5.387 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.387 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.225 ±(99.9%) 0.115 ms/op
Iteration   1: 2.905 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.905 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.388 ±(99.9%) 0.238 ms/op
Iteration   1: 4.913 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.913 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 23.441 ±(99.9%) 0.528 ms/op
Iteration   1: 14.954 ±(99.9%) 0.270 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  14.954 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.749 ±(99.9%) 0.244 ms/op
Iteration   1: 4.628 ±(99.9%) 0.155 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   8.872 ms/op
                 createUser·p0.95:   11.583 ms/op
                 createUser·p0.99:   17.650 ms/op
                 createUser·p0.999:  42.708 ms/op
                 createUser·p0.9999: 61.211 ms/op
                 createUser·p1.00:   61.211 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 7334
  mean =      4.628 ±(99.9%) 0.155 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5415 
    [ 5.000, 10.000) = 1345 
    [10.000, 15.000) = 477 
    [15.000, 20.000) = 46 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 23 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      8.872 ms/op
     p(95.0000) =     11.583 ms/op
     p(99.0000) =     17.650 ms/op
     p(99.9000) =     42.708 ms/op
     p(99.9900) =     61.211 ms/op
     p(99.9990) =     61.211 ms/op
     p(99.9999) =     61.211 ms/op
    p(100.0000) =     61.211 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.814 ±(99.9%) 0.210 ms/op
Iteration   1: 2.237 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   1.995 ms/op
                 existUser·p0.90:   2.703 ms/op
                 existUser·p0.95:   3.289 ms/op
                 existUser·p0.99:   6.958 ms/op
                 existUser·p0.999:  15.511 ms/op
                 existUser·p0.9999: 15.679 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14253
  mean =      2.237 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 11928 
    [ 2.500,  3.750) = 1797 
    [ 3.750,  5.000) = 174 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      6.958 ms/op
     p(99.9000) =     15.511 ms/op
     p(99.9900) =     15.679 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 9.489 ±(99.9%) 0.271 ms/op
Iteration   1: 3.515 ±(99.9%) 0.062 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   4.388 ms/op
                 getUser·p0.95:   5.737 ms/op
                 getUser·p0.99:   12.517 ms/op
                 getUser·p0.999:  21.103 ms/op
                 getUser·p0.9999: 24.117 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9052
  mean =      3.515 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 524 
    [ 2.500,  5.000) = 7924 
    [ 5.000,  7.500) = 405 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      4.388 ms/op
     p(95.0000) =      5.737 ms/op
     p(99.0000) =     12.517 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 24.128 ±(99.9%) 0.879 ms/op
Iteration   1: 16.135 ±(99.9%) 0.495 ms/op
                 listUser·p0.00:   3.961 ms/op
                 listUser·p0.50:   14.746 ms/op
                 listUser·p0.90:   24.543 ms/op
                 listUser·p0.95:   27.594 ms/op
                 listUser·p0.99:   42.524 ms/op
                 listUser·p0.999:  68.413 ms/op
                 listUser·p0.9999: 70.779 ms/op
                 listUser·p1.00:   70.779 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2037
  mean =     16.135 ±(99.9%) 0.495 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10 
    [ 5.000, 10.000) = 236 
    [10.000, 15.000) = 807 
    [15.000, 20.000) = 580 
    [20.000, 25.000) = 221 
    [25.000, 30.000) = 119 
    [30.000, 35.000) = 19 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 27 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 1 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.961 ms/op
     p(50.0000) =     14.746 ms/op
     p(90.0000) =     24.543 ms/op
     p(95.0000) =     27.594 ms/op
     p(99.0000) =     42.524 ms/op
     p(99.9000) =     68.413 ms/op
     p(99.9900) =     70.779 ms/op
     p(99.9990) =     70.779 ms/op
     p(99.9999) =     70.779 ms/op
    p(100.0000) =     70.779 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.696          ops/ms
Client.existUser                       thrpt          9.155          ops/ms
Client.getUser                         thrpt          4.858          ops/ms
Client.listUser                        thrpt          1.624          ops/ms
Client.createUser                       avgt          5.387           ms/op
Client.existUser                        avgt          2.905           ms/op
Client.getUser                          avgt          4.913           ms/op
Client.listUser                         avgt         14.954           ms/op
Client.createUser                     sample   7334   4.628 ± 0.155   ms/op
Client.createUser:createUser·p0.00    sample          1.217           ms/op
Client.createUser:createUser·p0.50    sample          3.314           ms/op
Client.createUser:createUser·p0.90    sample          8.872           ms/op
Client.createUser:createUser·p0.95    sample         11.583           ms/op
Client.createUser:createUser·p0.99    sample         17.650           ms/op
Client.createUser:createUser·p0.999   sample         42.708           ms/op
Client.createUser:createUser·p0.9999  sample         61.211           ms/op
Client.createUser:createUser·p1.00    sample         61.211           ms/op
Client.existUser                      sample  14253   2.237 ± 0.031   ms/op
Client.existUser:existUser·p0.00      sample          0.702           ms/op
Client.existUser:existUser·p0.50      sample          1.995           ms/op
Client.existUser:existUser·p0.90      sample          2.703           ms/op
Client.existUser:existUser·p0.95      sample          3.289           ms/op
Client.existUser:existUser·p0.99      sample          6.958           ms/op
Client.existUser:existUser·p0.999     sample         15.511           ms/op
Client.existUser:existUser·p0.9999    sample         15.679           ms/op
Client.existUser:existUser·p1.00      sample         15.679           ms/op
Client.getUser                        sample   9052   3.515 ± 0.062   ms/op
Client.getUser:getUser·p0.00          sample          0.871           ms/op
Client.getUser:getUser·p0.50          sample          3.125           ms/op
Client.getUser:getUser·p0.90          sample          4.388           ms/op
Client.getUser:getUser·p0.95          sample          5.737           ms/op
Client.getUser:getUser·p0.99          sample         12.517           ms/op
Client.getUser:getUser·p0.999         sample         21.103           ms/op
Client.getUser:getUser·p0.9999        sample         24.117           ms/op
Client.getUser:getUser·p1.00          sample         24.117           ms/op
Client.listUser                       sample   2037  16.135 ± 0.495   ms/op
Client.listUser:listUser·p0.00        sample          3.961           ms/op
Client.listUser:listUser·p0.50        sample         14.746           ms/op
Client.listUser:listUser·p0.90        sample         24.543           ms/op
Client.listUser:listUser·p0.95        sample         27.594           ms/op
Client.listUser:listUser·p0.99        sample         42.524           ms/op
Client.listUser:listUser·p0.999       sample         68.413           ms/op
Client.listUser:listUser·p0.9999      sample         70.779           ms/op
Client.listUser:listUser·p1.00        sample         70.779           ms/op
