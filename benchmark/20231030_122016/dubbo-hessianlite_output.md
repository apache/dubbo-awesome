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
# Warmup Iteration   1: 0.983 ops/ms
Iteration   1: 3.346 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.346 ops/ms


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
# Warmup Iteration   1: 4.938 ops/ms
Iteration   1: 9.675 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.675 ops/ms


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
# Warmup Iteration   1: 2.723 ops/ms
Iteration   1: 5.042 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.042 ops/ms


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
# Warmup Iteration   1: 1.124 ops/ms
Iteration   1: 1.810 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.810 ops/ms


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
# Warmup Iteration   1: 10.638 ±(99.9%) 0.229 ms/op
Iteration   1: 5.350 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.350 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.386 ±(99.9%) 0.113 ms/op
Iteration   1: 2.798 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.798 ms/op


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
# Warmup Iteration   1: 9.964 ±(99.9%) 0.159 ms/op
Iteration   1: 3.976 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.976 ms/op


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
# Warmup Iteration   1: 24.040 ±(99.9%) 0.511 ms/op
Iteration   1: 18.311 ±(99.9%) 0.293 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.311 ms/op


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
# Warmup Iteration   1: 9.077 ±(99.9%) 0.302 ms/op
Iteration   1: 3.577 ±(99.9%) 0.104 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   13.369 ms/op
                 createUser·p0.999:  44.302 ms/op
                 createUser·p0.9999: 44.499 ms/op
                 createUser·p1.00:   44.499 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8939
  mean =      3.577 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8261 
    [ 5.000, 10.000) = 519 
    [10.000, 15.000) = 95 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.636 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =     13.369 ms/op
     p(99.9000) =     44.302 ms/op
     p(99.9900) =     44.499 ms/op
     p(99.9990) =     44.499 ms/op
     p(99.9999) =     44.499 ms/op
    p(100.0000) =     44.499 ms/op


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
# Warmup Iteration   1: 6.179 ±(99.9%) 0.192 ms/op
Iteration   1: 2.262 ±(99.9%) 0.048 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   1.901 ms/op
                 existUser·p0.90:   2.843 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   9.320 ms/op
                 existUser·p0.999:  29.287 ms/op
                 existUser·p0.9999: 30.401 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14113
  mean =      2.262 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12000 
    [ 2.500,  5.000) = 1687 
    [ 5.000,  7.500) = 236 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.843 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      9.320 ms/op
     p(99.9000) =     29.287 ms/op
     p(99.9900) =     30.401 ms/op
     p(99.9990) =     30.441 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 11.207 ±(99.9%) 0.286 ms/op
Iteration   1: 4.599 ±(99.9%) 0.119 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   8.004 ms/op
                 getUser·p0.95:   10.846 ms/op
                 getUser·p0.99:   16.761 ms/op
                 getUser·p0.999:  25.014 ms/op
                 getUser·p0.9999: 29.688 ms/op
                 getUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6939
  mean =      4.599 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 309 
    [ 2.500,  5.000) = 5169 
    [ 5.000,  7.500) = 644 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      8.004 ms/op
     p(95.0000) =     10.846 ms/op
     p(99.0000) =     16.761 ms/op
     p(99.9000) =     25.014 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     29.688 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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
# Warmup Iteration   1: 26.310 ±(99.9%) 0.948 ms/op
Iteration   1: 22.136 ±(99.9%) 0.697 ms/op
                 listUser·p0.00:   2.666 ms/op
                 listUser·p0.50:   21.561 ms/op
                 listUser·p0.90:   29.131 ms/op
                 listUser·p0.95:   32.588 ms/op
                 listUser·p0.99:   58.733 ms/op
                 listUser·p0.999:  74.516 ms/op
                 listUser·p0.9999: 76.939 ms/op
                 listUser·p1.00:   76.939 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1429
  mean =     22.136 ±(99.9%) 0.697 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3 
    [ 5.000, 10.000) = 13 
    [10.000, 15.000) = 191 
    [15.000, 20.000) = 361 
    [20.000, 25.000) = 519 
    [25.000, 30.000) = 218 
    [30.000, 35.000) = 62 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 13 
    [60.000, 65.000) = 4 
    [65.000, 70.000) = 3 
    [70.000, 75.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.666 ms/op
     p(50.0000) =     21.561 ms/op
     p(90.0000) =     29.131 ms/op
     p(95.0000) =     32.588 ms/op
     p(99.0000) =     58.733 ms/op
     p(99.9000) =     74.516 ms/op
     p(99.9900) =     76.939 ms/op
     p(99.9990) =     76.939 ms/op
     p(99.9999) =     76.939 ms/op
    p(100.0000) =     76.939 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.346          ops/ms
Client.existUser                       thrpt          9.675          ops/ms
Client.getUser                         thrpt          5.042          ops/ms
Client.listUser                        thrpt          1.810          ops/ms
Client.createUser                       avgt          5.350           ms/op
Client.existUser                        avgt          2.798           ms/op
Client.getUser                          avgt          3.976           ms/op
Client.listUser                         avgt         18.311           ms/op
Client.createUser                     sample   8939   3.577 ± 0.104   ms/op
Client.createUser:createUser·p0.00    sample          1.636           ms/op
Client.createUser:createUser·p0.50    sample          2.929           ms/op
Client.createUser:createUser·p0.90    sample          4.415           ms/op
Client.createUser:createUser·p0.95    sample          6.865           ms/op
Client.createUser:createUser·p0.99    sample         13.369           ms/op
Client.createUser:createUser·p0.999   sample         44.302           ms/op
Client.createUser:createUser·p0.9999  sample         44.499           ms/op
Client.createUser:createUser·p1.00    sample         44.499           ms/op
Client.existUser                      sample  14113   2.262 ± 0.048   ms/op
Client.existUser:existUser·p0.00      sample          0.886           ms/op
Client.existUser:existUser·p0.50      sample          1.901           ms/op
Client.existUser:existUser·p0.90      sample          2.843           ms/op
Client.existUser:existUser·p0.95      sample          3.711           ms/op
Client.existUser:existUser·p0.99      sample          9.320           ms/op
Client.existUser:existUser·p0.999     sample         29.287           ms/op
Client.existUser:existUser·p0.9999    sample         30.401           ms/op
Client.existUser:existUser·p1.00      sample         30.441           ms/op
Client.getUser                        sample   6939   4.599 ± 0.119   ms/op
Client.getUser:getUser·p0.00          sample          0.610           ms/op
Client.getUser:getUser·p0.50          sample          3.637           ms/op
Client.getUser:getUser·p0.90          sample          8.004           ms/op
Client.getUser:getUser·p0.95          sample         10.846           ms/op
Client.getUser:getUser·p0.99          sample         16.761           ms/op
Client.getUser:getUser·p0.999         sample         25.014           ms/op
Client.getUser:getUser·p0.9999        sample         29.688           ms/op
Client.getUser:getUser·p1.00          sample         29.688           ms/op
Client.listUser                       sample   1429  22.136 ± 0.697   ms/op
Client.listUser:listUser·p0.00        sample          2.666           ms/op
Client.listUser:listUser·p0.50        sample         21.561           ms/op
Client.listUser:listUser·p0.90        sample         29.131           ms/op
Client.listUser:listUser·p0.95        sample         32.588           ms/op
Client.listUser:listUser·p0.99        sample         58.733           ms/op
Client.listUser:listUser·p0.999       sample         74.516           ms/op
Client.listUser:listUser·p0.9999      sample         76.939           ms/op
Client.listUser:listUser·p1.00        sample         76.939           ms/op
