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
# Warmup Iteration   1: 2.444 ops/ms
Iteration   1: 6.222 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.222 ops/ms


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
# Warmup Iteration   1: 6.494 ops/ms
Iteration   1: 12.747 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.747 ops/ms


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
# Warmup Iteration   1: 4.308 ops/ms
Iteration   1: 8.121 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.121 ops/ms


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
# Warmup Iteration   1: 2.298 ops/ms
Iteration   1: 4.100 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.100 ops/ms


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
# Warmup Iteration   1: 4.773 ±(99.9%) 0.049 ms/op
Iteration   1: 3.165 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.165 ms/op


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
# Warmup Iteration   1: 2.924 ±(99.9%) 0.034 ms/op
Iteration   1: 1.673 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.673 ms/op


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.057 ms/op
Iteration   1: 3.024 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.024 ms/op


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
# Warmup Iteration   1: 11.060 ±(99.9%) 0.159 ms/op
Iteration   1: 8.209 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.209 ms/op


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
# Warmup Iteration   1: 5.005 ±(99.9%) 0.100 ms/op
Iteration   1: 2.906 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   7.979 ms/op
                 createUser·p0.999:  17.269 ms/op
                 createUser·p0.9999: 17.334 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11000
  mean =      2.906 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 3971 
    [ 2.500,  3.750) = 6163 
    [ 3.750,  5.000) = 591 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 2.796 ±(99.9%) 0.054 ms/op
Iteration   1: 1.690 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   1.995 ms/op
                 existUser·p0.95:   2.245 ms/op
                 existUser·p0.99:   2.925 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18980
  mean =      1.690 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 743 
    [ 1.250,  2.500) = 17750 
    [ 2.500,  3.750) = 444 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      1.995 ms/op
     p(95.0000) =      2.245 ms/op
     p(99.0000) =      2.925 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.129 ms/op
Iteration   1: 2.772 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   6.301 ms/op
                 getUser·p0.999:  18.481 ms/op
                 getUser·p0.9999: 20.122 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11543
  mean =      2.772 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5808 
    [ 2.500,  5.000) = 5543 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      6.301 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     20.122 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 11.167 ±(99.9%) 0.362 ms/op
Iteration   1: 8.092 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   7.709 ms/op
                 listUser·p0.90:   10.781 ms/op
                 listUser·p0.95:   11.780 ms/op
                 listUser·p0.99:   17.157 ms/op
                 listUser·p0.999:  21.066 ms/op
                 listUser·p0.9999: 22.217 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4039
  mean =      8.092 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 176 
    [ 5.000,  7.500) = 1640 
    [ 7.500, 10.000) = 1594 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.400 ms/op
     p(50.0000) =      7.709 ms/op
     p(90.0000) =     10.781 ms/op
     p(95.0000) =     11.780 ms/op
     p(99.0000) =     17.157 ms/op
     p(99.9000) =     21.066 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.222          ops/ms
Client.existUser                       thrpt         12.747          ops/ms
Client.getUser                         thrpt          8.121          ops/ms
Client.listUser                        thrpt          4.100          ops/ms
Client.createUser                       avgt          3.165           ms/op
Client.existUser                        avgt          1.673           ms/op
Client.getUser                          avgt          3.024           ms/op
Client.listUser                         avgt          8.209           ms/op
Client.createUser                     sample  11000   2.906 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.098           ms/op
Client.createUser:createUser·p0.50    sample          2.605           ms/op
Client.createUser:createUser·p0.90    sample          3.584           ms/op
Client.createUser:createUser·p0.95    sample          4.096           ms/op
Client.createUser:createUser·p0.99    sample          7.979           ms/op
Client.createUser:createUser·p0.999   sample         17.269           ms/op
Client.createUser:createUser·p0.9999  sample         17.334           ms/op
Client.createUser:createUser·p1.00    sample         17.334           ms/op
Client.existUser                      sample  18980   1.690 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.461           ms/op
Client.existUser:existUser·p0.50      sample          1.620           ms/op
Client.existUser:existUser·p0.90      sample          1.995           ms/op
Client.existUser:existUser·p0.95      sample          2.245           ms/op
Client.existUser:existUser·p0.99      sample          2.925           ms/op
Client.existUser:existUser·p0.999     sample         17.727           ms/op
Client.existUser:existUser·p0.9999    sample         18.022           ms/op
Client.existUser:existUser·p1.00      sample         18.022           ms/op
Client.getUser                        sample  11543   2.772 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.868           ms/op
Client.getUser:getUser·p0.50          sample          2.494           ms/op
Client.getUser:getUser·p0.90          sample          3.502           ms/op
Client.getUser:getUser·p0.95          sample          3.838           ms/op
Client.getUser:getUser·p0.99          sample          6.301           ms/op
Client.getUser:getUser·p0.999         sample         18.481           ms/op
Client.getUser:getUser·p0.9999        sample         20.122           ms/op
Client.getUser:getUser·p1.00          sample         20.152           ms/op
Client.listUser                       sample   4039   8.092 ± 0.119   ms/op
Client.listUser:listUser·p0.00        sample          2.400           ms/op
Client.listUser:listUser·p0.50        sample          7.709           ms/op
Client.listUser:listUser·p0.90        sample         10.781           ms/op
Client.listUser:listUser·p0.95        sample         11.780           ms/op
Client.listUser:listUser·p0.99        sample         17.157           ms/op
Client.listUser:listUser·p0.999       sample         21.066           ms/op
Client.listUser:listUser·p0.9999      sample         22.217           ms/op
Client.listUser:listUser·p1.00        sample         22.217           ms/op
