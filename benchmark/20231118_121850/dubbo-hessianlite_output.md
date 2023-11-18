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
# Warmup Iteration   1: 2.244 ops/ms
Iteration   1: 5.661 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.661 ops/ms


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
# Warmup Iteration   1: 6.656 ops/ms
Iteration   1: 13.001 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.001 ops/ms


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
# Warmup Iteration   1: 4.501 ops/ms
Iteration   1: 8.699 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.699 ops/ms


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
# Warmup Iteration   1: 2.369 ops/ms
Iteration   1: 3.643 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.643 ops/ms


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
# Warmup Iteration   1: 5.032 ±(99.9%) 0.058 ms/op
Iteration   1: 2.765 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.765 ms/op


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
# Warmup Iteration   1: 3.093 ±(99.9%) 0.030 ms/op
Iteration   1: 1.955 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.955 ms/op


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.064 ms/op
Iteration   1: 3.370 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.370 ms/op


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
# Warmup Iteration   1: 11.593 ±(99.9%) 0.197 ms/op
Iteration   1: 8.716 ±(99.9%) 0.135 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.716 ms/op


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
# Warmup Iteration   1: 4.814 ±(99.9%) 0.090 ms/op
Iteration   1: 2.963 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   2.720 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   7.626 ms/op
                 createUser·p0.999:  17.177 ms/op
                 createUser·p0.9999: 19.068 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10802
  mean =      2.963 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2259 
    [ 2.500,  3.750) = 7819 
    [ 3.750,  5.000) = 416 
    [ 5.000,  6.250) = 126 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      2.720 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      7.626 ms/op
     p(99.9000) =     17.177 ms/op
     p(99.9900) =     19.068 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.068 ms/op
Iteration   1: 2.198 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   2.154 ms/op
                 existUser·p0.90:   2.613 ms/op
                 existUser·p0.95:   2.840 ms/op
                 existUser·p0.99:   3.369 ms/op
                 existUser·p0.999:  15.064 ms/op
                 existUser·p0.9999: 15.206 ms/op
                 existUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14550
  mean =      2.198 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 307 
    [ 1.250,  2.500) = 11818 
    [ 2.500,  3.750) = 2322 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.840 ms/op
     p(99.0000) =      3.369 ms/op
     p(99.9000) =     15.064 ms/op
     p(99.9900) =     15.206 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.097 ms/op
Iteration   1: 2.952 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.859 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   6.131 ms/op
                 getUser·p0.999:  16.172 ms/op
                 getUser·p0.9999: 18.039 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10962
  mean =      2.952 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 3456 
    [ 2.500,  3.750) = 6189 
    [ 3.750,  5.000) = 1066 
    [ 5.000,  6.250) = 140 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.131 ms/op
     p(99.9000) =     16.172 ms/op
     p(99.9900) =     18.039 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 11.576 ±(99.9%) 0.311 ms/op
Iteration   1: 8.350 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   8.004 ms/op
                 listUser·p0.90:   11.207 ms/op
                 listUser·p0.95:   12.387 ms/op
                 listUser·p0.99:   16.253 ms/op
                 listUser·p0.999:  18.795 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3858
  mean =      8.350 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 15 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 539 
    [ 6.250,  7.500) = 934 
    [ 7.500,  8.750) = 810 
    [ 8.750, 10.000) = 663 
    [10.000, 11.250) = 422 
    [11.250, 12.500) = 194 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.671 ms/op
     p(50.0000) =      8.004 ms/op
     p(90.0000) =     11.207 ms/op
     p(95.0000) =     12.387 ms/op
     p(99.0000) =     16.253 ms/op
     p(99.9000) =     18.795 ms/op
     p(99.9900) =     19.333 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.661          ops/ms
Client.existUser                       thrpt         13.001          ops/ms
Client.getUser                         thrpt          8.699          ops/ms
Client.listUser                        thrpt          3.643          ops/ms
Client.createUser                       avgt          2.765           ms/op
Client.existUser                        avgt          1.955           ms/op
Client.getUser                          avgt          3.370           ms/op
Client.listUser                         avgt          8.716           ms/op
Client.createUser                     sample  10802   2.963 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          1.493           ms/op
Client.createUser:createUser·p0.50    sample          2.720           ms/op
Client.createUser:createUser·p0.90    sample          3.486           ms/op
Client.createUser:createUser·p0.95    sample          4.219           ms/op
Client.createUser:createUser·p0.99    sample          7.626           ms/op
Client.createUser:createUser·p0.999   sample         17.177           ms/op
Client.createUser:createUser·p0.9999  sample         19.068           ms/op
Client.createUser:createUser·p1.00    sample         19.071           ms/op
Client.existUser                      sample  14550   2.198 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.574           ms/op
Client.existUser:existUser·p0.50      sample          2.154           ms/op
Client.existUser:existUser·p0.90      sample          2.613           ms/op
Client.existUser:existUser·p0.95      sample          2.840           ms/op
Client.existUser:existUser·p0.99      sample          3.369           ms/op
Client.existUser:existUser·p0.999     sample         15.064           ms/op
Client.existUser:existUser·p0.9999    sample         15.206           ms/op
Client.existUser:existUser·p1.00      sample         15.221           ms/op
Client.getUser                        sample  10962   2.952 ± 0.033   ms/op
Client.getUser:getUser·p0.00          sample          0.667           ms/op
Client.getUser:getUser·p0.50          sample          2.859           ms/op
Client.getUser:getUser·p0.90          sample          3.822           ms/op
Client.getUser:getUser·p0.95          sample          4.051           ms/op
Client.getUser:getUser·p0.99          sample          6.131           ms/op
Client.getUser:getUser·p0.999         sample         16.172           ms/op
Client.getUser:getUser·p0.9999        sample         18.039           ms/op
Client.getUser:getUser·p1.00          sample         18.055           ms/op
Client.listUser                       sample   3858   8.350 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          2.671           ms/op
Client.listUser:listUser·p0.50        sample          8.004           ms/op
Client.listUser:listUser·p0.90        sample         11.207           ms/op
Client.listUser:listUser·p0.95        sample         12.387           ms/op
Client.listUser:listUser·p0.99        sample         16.253           ms/op
Client.listUser:listUser·p0.999       sample         18.795           ms/op
Client.listUser:listUser·p0.9999      sample         19.333           ms/op
Client.listUser:listUser·p1.00        sample         19.333           ms/op
