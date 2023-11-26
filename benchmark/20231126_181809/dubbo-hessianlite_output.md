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
# Warmup Iteration   1: 2.685 ops/ms
Iteration   1: 5.961 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.961 ops/ms


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
# Warmup Iteration   1: 6.284 ops/ms
Iteration   1: 12.037 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.037 ops/ms


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
# Warmup Iteration   1: 4.543 ops/ms
Iteration   1: 10.174 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.174 ops/ms


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
# Warmup Iteration   1: 2.354 ops/ms
Iteration   1: 3.883 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.883 ops/ms


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
# Warmup Iteration   1: 5.326 ±(99.9%) 0.103 ms/op
Iteration   1: 2.886 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.886 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.028 ms/op
Iteration   1: 1.952 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.952 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.045 ms/op
Iteration   1: 2.945 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.945 ms/op


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
# Warmup Iteration   1: 11.805 ±(99.9%) 0.352 ms/op
Iteration   1: 7.984 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.984 ms/op


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
# Warmup Iteration   1: 4.984 ±(99.9%) 0.094 ms/op
Iteration   1: 3.172 ±(99.9%) 0.065 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   7.043 ms/op
                 createUser·p0.999:  29.917 ms/op
                 createUser·p0.9999: 30.145 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10111
  mean =      3.172 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1371 
    [ 2.500,  5.000) = 8574 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      7.043 ms/op
     p(99.9000) =     29.917 ms/op
     p(99.9900) =     30.145 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 2.821 ±(99.9%) 0.047 ms/op
Iteration   1: 2.090 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.367 ms/op
                 existUser·p0.50:   2.023 ms/op
                 existUser·p0.90:   2.630 ms/op
                 existUser·p0.95:   2.941 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  11.100 ms/op
                 existUser·p0.9999: 12.045 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15264
  mean =      2.090 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 682 
    [ 1.250,  2.500) = 12288 
    [ 2.500,  3.750) = 2048 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.367 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     11.100 ms/op
     p(99.9900) =     12.045 ms/op
     p(99.9990) =     12.157 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.093 ms/op
Iteration   1: 3.244 ±(99.9%) 0.056 ms/op
                 getUser·p0.00:   0.417 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   8.062 ms/op
                 getUser·p0.999:  28.349 ms/op
                 getUser·p0.9999: 28.901 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9855
  mean =      3.244 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1618 
    [ 2.500,  5.000) = 7940 
    [ 5.000,  7.500) = 197 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      8.062 ms/op
     p(99.9000) =     28.349 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 12.351 ±(99.9%) 0.385 ms/op
Iteration   1: 8.042 ±(99.9%) 0.136 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   7.537 ms/op
                 listUser·p0.90:   10.748 ms/op
                 listUser·p0.95:   12.190 ms/op
                 listUser·p0.99:   19.185 ms/op
                 listUser·p0.999:  25.624 ms/op
                 listUser·p0.9999: 36.962 ms/op
                 listUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3975
  mean =      8.042 ±(99.9%) 0.136 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 130 
    [ 5.000,  7.500) = 1816 
    [ 7.500, 10.000) = 1458 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.130 ms/op
     p(50.0000) =      7.537 ms/op
     p(90.0000) =     10.748 ms/op
     p(95.0000) =     12.190 ms/op
     p(99.0000) =     19.185 ms/op
     p(99.9000) =     25.624 ms/op
     p(99.9900) =     36.962 ms/op
     p(99.9990) =     36.962 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.961          ops/ms
Client.existUser                       thrpt         12.037          ops/ms
Client.getUser                         thrpt         10.174          ops/ms
Client.listUser                        thrpt          3.883          ops/ms
Client.createUser                       avgt          2.886           ms/op
Client.existUser                        avgt          1.952           ms/op
Client.getUser                          avgt          2.945           ms/op
Client.listUser                         avgt          7.984           ms/op
Client.createUser                     sample  10111   3.172 ± 0.065   ms/op
Client.createUser:createUser·p0.00    sample          0.949           ms/op
Client.createUser:createUser·p0.50    sample          2.908           ms/op
Client.createUser:createUser·p0.90    sample          3.650           ms/op
Client.createUser:createUser·p0.95    sample          3.973           ms/op
Client.createUser:createUser·p0.99    sample          7.043           ms/op
Client.createUser:createUser·p0.999   sample         29.917           ms/op
Client.createUser:createUser·p0.9999  sample         30.145           ms/op
Client.createUser:createUser·p1.00    sample         30.147           ms/op
Client.existUser                      sample  15264   2.090 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.367           ms/op
Client.existUser:existUser·p0.50      sample          2.023           ms/op
Client.existUser:existUser·p0.90      sample          2.630           ms/op
Client.existUser:existUser·p0.95      sample          2.941           ms/op
Client.existUser:existUser·p0.99      sample          6.021           ms/op
Client.existUser:existUser·p0.999     sample         11.100           ms/op
Client.existUser:existUser·p0.9999    sample         12.045           ms/op
Client.existUser:existUser·p1.00      sample         12.157           ms/op
Client.getUser                        sample   9855   3.244 ± 0.056   ms/op
Client.getUser:getUser·p0.00          sample          0.417           ms/op
Client.getUser:getUser·p0.50          sample          3.080           ms/op
Client.getUser:getUser·p0.90          sample          3.994           ms/op
Client.getUser:getUser·p0.95          sample          4.473           ms/op
Client.getUser:getUser·p0.99          sample          8.062           ms/op
Client.getUser:getUser·p0.999         sample         28.349           ms/op
Client.getUser:getUser·p0.9999        sample         28.901           ms/op
Client.getUser:getUser·p1.00          sample         28.901           ms/op
Client.listUser                       sample   3975   8.042 ± 0.136   ms/op
Client.listUser:listUser·p0.00        sample          2.130           ms/op
Client.listUser:listUser·p0.50        sample          7.537           ms/op
Client.listUser:listUser·p0.90        sample         10.748           ms/op
Client.listUser:listUser·p0.95        sample         12.190           ms/op
Client.listUser:listUser·p0.99        sample         19.185           ms/op
Client.listUser:listUser·p0.999       sample         25.624           ms/op
Client.listUser:listUser·p0.9999      sample         36.962           ms/op
Client.listUser:listUser·p1.00        sample         36.962           ms/op
