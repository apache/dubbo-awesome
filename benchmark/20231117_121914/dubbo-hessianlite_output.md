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
# Warmup Iteration   1: 2.465 ops/ms
Iteration   1: 6.121 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.121 ops/ms


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
# Warmup Iteration   1: 6.460 ops/ms
Iteration   1: 12.850 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.850 ops/ms


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
# Warmup Iteration   1: 4.751 ops/ms
Iteration   1: 8.636 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.636 ops/ms


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
# Warmup Iteration   1: 2.437 ops/ms
Iteration   1: 3.875 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.875 ops/ms


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.085 ms/op
Iteration   1: 3.357 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.357 ms/op


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
# Warmup Iteration   1: 3.085 ±(99.9%) 0.035 ms/op
Iteration   1: 1.798 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.798 ms/op


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.060 ms/op
Iteration   1: 3.019 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.019 ms/op


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
# Warmup Iteration   1: 11.996 ±(99.9%) 0.210 ms/op
Iteration   1: 8.197 ±(99.9%) 0.168 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.197 ms/op


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.089 ms/op
Iteration   1: 3.060 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.781 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   9.486 ms/op
                 createUser·p0.999:  15.887 ms/op
                 createUser·p0.9999: 16.024 ms/op
                 createUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10451
  mean =      3.060 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 3415 
    [ 2.500,  3.750) = 5847 
    [ 3.750,  5.000) = 773 
    [ 5.000,  6.250) = 166 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     15.887 ms/op
     p(99.9900) =     16.024 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.079 ms/op
Iteration   1: 1.785 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   1.677 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   3.298 ms/op
                 existUser·p0.999:  13.142 ms/op
                 existUser·p0.9999: 13.549 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17890
  mean =      1.785 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 553 
    [ 1.250,  2.500) = 16701 
    [ 2.500,  3.750) = 480 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.677 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      3.298 ms/op
     p(99.9000) =     13.142 ms/op
     p(99.9900) =     13.549 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 4.866 ±(99.9%) 0.115 ms/op
Iteration   1: 3.464 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   14.020 ms/op
                 getUser·p0.999:  18.179 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9229
  mean =      3.464 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 967 
    [ 2.500,  3.750) = 5768 
    [ 3.750,  5.000) = 2234 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =     14.020 ms/op
     p(99.9000) =     18.179 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 11.712 ±(99.9%) 0.326 ms/op
Iteration   1: 8.316 ±(99.9%) 0.111 ms/op
                 listUser·p0.00:   3.121 ms/op
                 listUser·p0.50:   8.012 ms/op
                 listUser·p0.90:   11.190 ms/op
                 listUser·p0.95:   12.467 ms/op
                 listUser·p0.99:   14.257 ms/op
                 listUser·p0.999:  18.659 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3881
  mean =      8.316 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 105 
    [ 5.000,  7.500) = 1312 
    [ 7.500, 10.000) = 1733 
    [10.000, 12.500) = 543 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.121 ms/op
     p(50.0000) =      8.012 ms/op
     p(90.0000) =     11.190 ms/op
     p(95.0000) =     12.467 ms/op
     p(99.0000) =     14.257 ms/op
     p(99.9000) =     18.659 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.121          ops/ms
Client.existUser                       thrpt         12.850          ops/ms
Client.getUser                         thrpt          8.636          ops/ms
Client.listUser                        thrpt          3.875          ops/ms
Client.createUser                       avgt          3.357           ms/op
Client.existUser                        avgt          1.798           ms/op
Client.getUser                          avgt          3.019           ms/op
Client.listUser                         avgt          8.197           ms/op
Client.createUser                     sample  10451   3.060 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          0.958           ms/op
Client.createUser:createUser·p0.50    sample          2.781           ms/op
Client.createUser:createUser·p0.90    sample          3.813           ms/op
Client.createUser:createUser·p0.95    sample          4.563           ms/op
Client.createUser:createUser·p0.99    sample          9.486           ms/op
Client.createUser:createUser·p0.999   sample         15.887           ms/op
Client.createUser:createUser·p0.9999  sample         16.024           ms/op
Client.createUser:createUser·p1.00    sample         16.024           ms/op
Client.existUser                      sample  17890   1.785 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.607           ms/op
Client.existUser:existUser·p0.50      sample          1.677           ms/op
Client.existUser:existUser·p0.90      sample          2.204           ms/op
Client.existUser:existUser·p0.95      sample          2.396           ms/op
Client.existUser:existUser·p0.99      sample          3.298           ms/op
Client.existUser:existUser·p0.999     sample         13.142           ms/op
Client.existUser:existUser·p0.9999    sample         13.549           ms/op
Client.existUser:existUser·p1.00      sample         13.730           ms/op
Client.getUser                        sample   9229   3.464 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample          0.679           ms/op
Client.getUser:getUser·p0.50          sample          3.305           ms/op
Client.getUser:getUser·p0.90          sample          4.166           ms/op
Client.getUser:getUser·p0.95          sample          4.407           ms/op
Client.getUser:getUser·p0.99          sample         14.020           ms/op
Client.getUser:getUser·p0.999         sample         18.179           ms/op
Client.getUser:getUser·p0.9999        sample         18.874           ms/op
Client.getUser:getUser·p1.00          sample         18.874           ms/op
Client.listUser                       sample   3881   8.316 ± 0.111   ms/op
Client.listUser:listUser·p0.00        sample          3.121           ms/op
Client.listUser:listUser·p0.50        sample          8.012           ms/op
Client.listUser:listUser·p0.90        sample         11.190           ms/op
Client.listUser:listUser·p0.95        sample         12.467           ms/op
Client.listUser:listUser·p0.99        sample         14.257           ms/op
Client.listUser:listUser·p0.999       sample         18.659           ms/op
Client.listUser:listUser·p0.9999      sample         21.987           ms/op
Client.listUser:listUser·p1.00        sample         21.987           ms/op
