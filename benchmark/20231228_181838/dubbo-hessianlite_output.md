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
# Warmup Iteration   1: 2.216 ops/ms
Iteration   1: 5.937 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.937 ops/ms


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
# Warmup Iteration   1: 5.671 ops/ms
Iteration   1: 13.203 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.203 ops/ms


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
# Warmup Iteration   1: 4.198 ops/ms
Iteration   1: 8.552 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.552 ops/ms


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
# Warmup Iteration   1: 2.217 ops/ms
Iteration   1: 4.237 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.237 ops/ms


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
# Warmup Iteration   1: 5.269 ±(99.9%) 0.064 ms/op
Iteration   1: 3.166 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.166 ms/op


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
# Warmup Iteration   1: 2.987 ±(99.9%) 0.034 ms/op
Iteration   1: 1.822 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.822 ms/op


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.048 ms/op
Iteration   1: 2.915 ±(99.9%) 0.013 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.735 ±(99.9%) 0.227 ms/op
Iteration   1: 8.484 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.484 ms/op


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.101 ms/op
Iteration   1: 3.460 ±(99.9%) 0.073 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.362 ms/op
                 createUser·p0.99:   8.995 ms/op
                 createUser·p0.999:  38.076 ms/op
                 createUser·p0.9999: 38.207 ms/op
                 createUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9390
  mean =      3.460 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 517 
    [ 2.500,  5.000) = 8598 
    [ 5.000,  7.500) = 170 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.362 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     38.076 ms/op
     p(99.9900) =     38.207 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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
# Warmup Iteration   1: 3.213 ±(99.9%) 0.063 ms/op
Iteration   1: 1.894 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   1.720 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  22.518 ms/op
                 existUser·p0.9999: 22.686 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16903
  mean =      1.894 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14912 
    [ 2.500,  5.000) = 1937 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      1.720 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =     22.518 ms/op
     p(99.9900) =     22.686 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 4.724 ±(99.9%) 0.117 ms/op
Iteration   1: 3.069 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.009 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  9.833 ms/op
                 getUser·p0.9999: 10.595 ms/op
                 getUser·p1.00:   10.600 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10434
  mean =      3.069 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 181 
    [ 2.000,  3.000) = 4988 
    [ 3.000,  4.000) = 4784 
    [ 4.000,  5.000) = 303 
    [ 5.000,  6.000) = 108 
    [ 6.000,  7.000) = 17 
    [ 7.000,  8.000) = 19 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.009 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      9.833 ms/op
     p(99.9900) =     10.595 ms/op
     p(99.9990) =     10.600 ms/op
     p(99.9999) =     10.600 ms/op
    p(100.0000) =     10.600 ms/op


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
# Warmup Iteration   1: 12.237 ±(99.9%) 0.481 ms/op
Iteration   1: 8.277 ±(99.9%) 0.110 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   8.004 ms/op
                 listUser·p0.90:   10.945 ms/op
                 listUser·p0.95:   12.182 ms/op
                 listUser·p0.99:   15.580 ms/op
                 listUser·p0.999:  18.857 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3869
  mean =      8.277 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 93 
    [ 5.000,  7.500) = 1392 
    [ 7.500, 10.000) = 1805 
    [10.000, 12.500) = 427 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.626 ms/op
     p(50.0000) =      8.004 ms/op
     p(90.0000) =     10.945 ms/op
     p(95.0000) =     12.182 ms/op
     p(99.0000) =     15.580 ms/op
     p(99.9000) =     18.857 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.937          ops/ms
Client.existUser                       thrpt         13.203          ops/ms
Client.getUser                         thrpt          8.552          ops/ms
Client.listUser                        thrpt          4.237          ops/ms
Client.createUser                       avgt          3.166           ms/op
Client.existUser                        avgt          1.822           ms/op
Client.getUser                          avgt          2.915           ms/op
Client.listUser                         avgt          8.484           ms/op
Client.createUser                     sample   9390   3.460 ± 0.073   ms/op
Client.createUser:createUser·p0.00    sample          0.952           ms/op
Client.createUser:createUser·p0.50    sample          3.215           ms/op
Client.createUser:createUser·p0.90    sample          4.047           ms/op
Client.createUser:createUser·p0.95    sample          4.362           ms/op
Client.createUser:createUser·p0.99    sample          8.995           ms/op
Client.createUser:createUser·p0.999   sample         38.076           ms/op
Client.createUser:createUser·p0.9999  sample         38.207           ms/op
Client.createUser:createUser·p1.00    sample         38.207           ms/op
Client.existUser                      sample  16903   1.894 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.655           ms/op
Client.existUser:existUser·p0.50      sample          1.720           ms/op
Client.existUser:existUser·p0.90      sample          2.564           ms/op
Client.existUser:existUser·p0.95      sample          2.822           ms/op
Client.existUser:existUser·p0.99      sample          3.637           ms/op
Client.existUser:existUser·p0.999     sample         22.518           ms/op
Client.existUser:existUser·p0.9999    sample         22.686           ms/op
Client.existUser:existUser·p1.00      sample         22.708           ms/op
Client.getUser                        sample  10434   3.069 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.757           ms/op
Client.getUser:getUser·p0.50          sample          3.009           ms/op
Client.getUser:getUser·p0.90          sample          3.736           ms/op
Client.getUser:getUser·p0.95          sample          3.969           ms/op
Client.getUser:getUser·p0.99          sample          5.267           ms/op
Client.getUser:getUser·p0.999         sample          9.833           ms/op
Client.getUser:getUser·p0.9999        sample         10.595           ms/op
Client.getUser:getUser·p1.00          sample         10.600           ms/op
Client.listUser                       sample   3869   8.277 ± 0.110   ms/op
Client.listUser:listUser·p0.00        sample          2.626           ms/op
Client.listUser:listUser·p0.50        sample          8.004           ms/op
Client.listUser:listUser·p0.90        sample         10.945           ms/op
Client.listUser:listUser·p0.95        sample         12.182           ms/op
Client.listUser:listUser·p0.99        sample         15.580           ms/op
Client.listUser:listUser·p0.999       sample         18.857           ms/op
Client.listUser:listUser·p0.9999      sample         20.382           ms/op
Client.listUser:listUser·p1.00        sample         20.382           ms/op
