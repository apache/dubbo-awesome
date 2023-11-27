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
# Warmup Iteration   1: 1.986 ops/ms
Iteration   1: 5.786 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.786 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.303 ops/ms
Iteration   1: 11.555 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.555 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ops/ms
Iteration   1: 6.865 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.865 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.224 ops/ms
Iteration   1: 3.626 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.626 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.318 ±(99.9%) 0.092 ms/op
Iteration   1: 2.935 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.935 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.035 ms/op
Iteration   1: 1.913 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.913 ms/op


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
# Warmup Iteration   1: 5.164 ±(99.9%) 0.077 ms/op
Iteration   1: 2.915 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.915 ms/op


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
# Warmup Iteration   1: 11.666 ±(99.9%) 0.190 ms/op
Iteration   1: 8.690 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.690 ms/op


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.114 ms/op
Iteration   1: 3.266 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  17.334 ms/op
                 createUser·p0.9999: 17.924 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9857
  mean =      3.266 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1656 
    [ 2.500,  3.750) = 6487 
    [ 3.750,  5.000) = 1304 
    [ 5.000,  6.250) = 153 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.421 ±(99.9%) 0.084 ms/op
Iteration   1: 2.022 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   1.837 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.688 ms/op
                 existUser·p0.99:   5.599 ms/op
                 existUser·p0.999:  27.689 ms/op
                 existUser·p0.9999: 28.437 ms/op
                 existUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15816
  mean =      2.022 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13905 
    [ 2.500,  5.000) = 1742 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.688 ms/op
     p(99.0000) =      5.599 ms/op
     p(99.9000) =     27.689 ms/op
     p(99.9900) =     28.437 ms/op
     p(99.9990) =     28.475 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.095 ms/op
Iteration   1: 2.963 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.789 ms/op
                 getUser·p0.90:   3.947 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.076 ms/op
                 getUser·p0.999:  13.108 ms/op
                 getUser·p0.9999: 14.077 ms/op
                 getUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10923
  mean =      2.963 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 3750 
    [ 2.500,  3.750) = 5767 
    [ 3.750,  5.000) = 1176 
    [ 5.000,  6.250) = 137 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.947 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.076 ms/op
     p(99.9000) =     13.108 ms/op
     p(99.9900) =     14.077 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 12.659 ±(99.9%) 0.489 ms/op
Iteration   1: 8.237 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   7.873 ms/op
                 listUser·p0.90:   11.141 ms/op
                 listUser·p0.95:   12.272 ms/op
                 listUser·p0.99:   14.850 ms/op
                 listUser·p0.999:  17.919 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3871
  mean =      8.237 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 9 
    [ 2.500,  3.750) = 21 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 413 
    [ 6.250,  7.500) = 1133 
    [ 7.500,  8.750) = 891 
    [ 8.750, 10.000) = 550 
    [10.000, 11.250) = 388 
    [11.250, 12.500) = 205 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      7.873 ms/op
     p(90.0000) =     11.141 ms/op
     p(95.0000) =     12.272 ms/op
     p(99.0000) =     14.850 ms/op
     p(99.9000) =     17.919 ms/op
     p(99.9900) =     19.333 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.786          ops/ms
Client.existUser                       thrpt         11.555          ops/ms
Client.getUser                         thrpt          6.865          ops/ms
Client.listUser                        thrpt          3.626          ops/ms
Client.createUser                       avgt          2.935           ms/op
Client.existUser                        avgt          1.913           ms/op
Client.getUser                          avgt          2.915           ms/op
Client.listUser                         avgt          8.690           ms/op
Client.createUser                     sample   9857   3.266 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          0.841           ms/op
Client.createUser:createUser·p0.50    sample          3.068           ms/op
Client.createUser:createUser·p0.90    sample          4.055           ms/op
Client.createUser:createUser·p0.95    sample          4.669           ms/op
Client.createUser:createUser·p0.99    sample          9.175           ms/op
Client.createUser:createUser·p0.999   sample         17.334           ms/op
Client.createUser:createUser·p0.9999  sample         17.924           ms/op
Client.createUser:createUser·p1.00    sample         17.924           ms/op
Client.existUser                      sample  15816   2.022 ± 0.036   ms/op
Client.existUser:existUser·p0.00      sample          0.563           ms/op
Client.existUser:existUser·p0.50      sample          1.837           ms/op
Client.existUser:existUser·p0.90      sample          2.560           ms/op
Client.existUser:existUser·p0.95      sample          2.688           ms/op
Client.existUser:existUser·p0.99      sample          5.599           ms/op
Client.existUser:existUser·p0.999     sample         27.689           ms/op
Client.existUser:existUser·p0.9999    sample         28.437           ms/op
Client.existUser:existUser·p1.00      sample         28.475           ms/op
Client.getUser                        sample  10923   2.963 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          0.958           ms/op
Client.getUser:getUser·p0.50          sample          2.789           ms/op
Client.getUser:getUser·p0.90          sample          3.947           ms/op
Client.getUser:getUser·p0.95          sample          4.243           ms/op
Client.getUser:getUser·p0.99          sample          6.076           ms/op
Client.getUser:getUser·p0.999         sample         13.108           ms/op
Client.getUser:getUser·p0.9999        sample         14.077           ms/op
Client.getUser:getUser·p1.00          sample         14.090           ms/op
Client.listUser                       sample   3871   8.237 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          1.946           ms/op
Client.listUser:listUser·p0.50        sample          7.873           ms/op
Client.listUser:listUser·p0.90        sample         11.141           ms/op
Client.listUser:listUser·p0.95        sample         12.272           ms/op
Client.listUser:listUser·p0.99        sample         14.850           ms/op
Client.listUser:listUser·p0.999       sample         17.919           ms/op
Client.listUser:listUser·p0.9999      sample         19.333           ms/op
Client.listUser:listUser·p1.00        sample         19.333           ms/op
