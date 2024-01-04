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
# Warmup Iteration   1: 2.454 ops/ms
Iteration   1: 6.085 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.085 ops/ms


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
# Warmup Iteration   1: 6.063 ops/ms
Iteration   1: 13.448 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.448 ops/ms


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
# Warmup Iteration   1: 4.590 ops/ms
Iteration   1: 8.808 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.808 ops/ms


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
# Warmup Iteration   1: 1.962 ops/ms
Iteration   1: 3.718 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.718 ops/ms


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
# Warmup Iteration   1: 5.577 ±(99.9%) 0.073 ms/op
Iteration   1: 3.339 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.339 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.026 ms/op
Iteration   1: 2.141 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.141 ms/op


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
# Warmup Iteration   1: 4.505 ±(99.9%) 0.061 ms/op
Iteration   1: 3.115 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.115 ms/op


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
# Warmup Iteration   1: 12.340 ±(99.9%) 0.216 ms/op
Iteration   1: 7.472 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.472 ms/op


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
# Warmup Iteration   1: 4.693 ±(99.9%) 0.102 ms/op
Iteration   1: 2.820 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   8.396 ms/op
                 createUser·p0.999:  21.910 ms/op
                 createUser·p0.9999: 22.326 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11344
  mean =      2.820 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4587 
    [ 2.500,  5.000) = 6569 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      8.396 ms/op
     p(99.9000) =     21.910 ms/op
     p(99.9900) =     22.326 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.074 ms/op
Iteration   1: 1.712 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.054 ms/op
                 existUser·p0.95:   2.220 ms/op
                 existUser·p0.99:   3.318 ms/op
                 existUser·p0.999:  6.914 ms/op
                 existUser·p0.9999: 10.701 ms/op
                 existUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18670
  mean =      1.712 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 7 
    [ 1.000,  2.000) = 16346 
    [ 2.000,  3.000) = 2110 
    [ 3.000,  4.000) = 47 
    [ 4.000,  5.000) = 81 
    [ 5.000,  6.000) = 45 
    [ 6.000,  7.000) = 29 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.054 ms/op
     p(95.0000) =      2.220 ms/op
     p(99.0000) =      3.318 ms/op
     p(99.9000) =      6.914 ms/op
     p(99.9900) =     10.701 ms/op
     p(99.9990) =     10.715 ms/op
     p(99.9999) =     10.715 ms/op
    p(100.0000) =     10.715 ms/op


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.099 ms/op
Iteration   1: 3.013 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   4.034 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  7.559 ms/op
                 getUser·p0.9999: 7.634 ms/op
                 getUser·p1.00:   7.635 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10663
  mean =      3.013 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 43 
    [1.500, 2.000) = 242 
    [2.000, 2.500) = 1929 
    [2.500, 3.000) = 3421 
    [3.000, 3.500) = 3355 
    [3.500, 4.000) = 1106 
    [4.000, 4.500) = 248 
    [4.500, 5.000) = 105 
    [5.000, 5.500) = 25 
    [5.500, 6.000) = 62 
    [6.000, 6.500) = 68 
    [6.500, 7.000) = 23 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.034 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =      7.559 ms/op
     p(99.9900) =      7.634 ms/op
     p(99.9990) =      7.635 ms/op
     p(99.9999) =      7.635 ms/op
    p(100.0000) =      7.635 ms/op


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
# Warmup Iteration   1: 12.437 ±(99.9%) 0.404 ms/op
Iteration   1: 7.684 ±(99.9%) 0.102 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   7.414 ms/op
                 listUser·p0.90:   9.912 ms/op
                 listUser·p0.95:   10.856 ms/op
                 listUser·p0.99:   15.949 ms/op
                 listUser·p0.999:  21.498 ms/op
                 listUser·p0.9999: 30.245 ms/op
                 listUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4187
  mean =      7.684 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 191 
    [ 5.000,  7.500) = 1998 
    [ 7.500, 10.000) = 1605 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      7.414 ms/op
     p(90.0000) =      9.912 ms/op
     p(95.0000) =     10.856 ms/op
     p(99.0000) =     15.949 ms/op
     p(99.9000) =     21.498 ms/op
     p(99.9900) =     30.245 ms/op
     p(99.9990) =     30.245 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.085          ops/ms
Client.existUser                       thrpt         13.448          ops/ms
Client.getUser                         thrpt          8.808          ops/ms
Client.listUser                        thrpt          3.718          ops/ms
Client.createUser                       avgt          3.339           ms/op
Client.existUser                        avgt          2.141           ms/op
Client.getUser                          avgt          3.115           ms/op
Client.listUser                         avgt          7.472           ms/op
Client.createUser                     sample  11344   2.820 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          0.970           ms/op
Client.createUser:createUser·p0.50    sample          2.556           ms/op
Client.createUser:createUser·p0.90    sample          3.404           ms/op
Client.createUser:createUser·p0.95    sample          3.740           ms/op
Client.createUser:createUser·p0.99    sample          8.396           ms/op
Client.createUser:createUser·p0.999   sample         21.910           ms/op
Client.createUser:createUser·p0.9999  sample         22.326           ms/op
Client.createUser:createUser·p1.00    sample         22.348           ms/op
Client.existUser                      sample  18670   1.712 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.874           ms/op
Client.existUser:existUser·p0.50      sample          1.634           ms/op
Client.existUser:existUser·p0.90      sample          2.054           ms/op
Client.existUser:existUser·p0.95      sample          2.220           ms/op
Client.existUser:existUser·p0.99      sample          3.318           ms/op
Client.existUser:existUser·p0.999     sample          6.914           ms/op
Client.existUser:existUser·p0.9999    sample         10.701           ms/op
Client.existUser:existUser·p1.00      sample         10.715           ms/op
Client.getUser                        sample  10663   3.013 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.738           ms/op
Client.getUser:getUser·p0.50          sample          2.961           ms/op
Client.getUser:getUser·p0.90          sample          3.678           ms/op
Client.getUser:getUser·p0.95          sample          4.034           ms/op
Client.getUser:getUser·p0.99          sample          6.275           ms/op
Client.getUser:getUser·p0.999         sample          7.559           ms/op
Client.getUser:getUser·p0.9999        sample          7.634           ms/op
Client.getUser:getUser·p1.00          sample          7.635           ms/op
Client.listUser                       sample   4187   7.684 ± 0.102   ms/op
Client.listUser:listUser·p0.00        sample          2.179           ms/op
Client.listUser:listUser·p0.50        sample          7.414           ms/op
Client.listUser:listUser·p0.90        sample          9.912           ms/op
Client.listUser:listUser·p0.95        sample         10.856           ms/op
Client.listUser:listUser·p0.99        sample         15.949           ms/op
Client.listUser:listUser·p0.999       sample         21.498           ms/op
Client.listUser:listUser·p0.9999      sample         30.245           ms/op
Client.listUser:listUser·p1.00        sample         30.245           ms/op
