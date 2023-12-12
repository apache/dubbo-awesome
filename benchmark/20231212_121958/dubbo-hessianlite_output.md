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
# Warmup Iteration   1: 2.505 ops/ms
Iteration   1: 6.932 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.932 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.404 ops/ms
Iteration   1: 13.786 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.786 ops/ms


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
# Warmup Iteration   1: 4.655 ops/ms
Iteration   1: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.430 ops/ms


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
# Warmup Iteration   1: 2.349 ops/ms
Iteration   1: 3.829 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.829 ops/ms


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.062 ms/op
Iteration   1: 2.859 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.859 ms/op


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
# Warmup Iteration   1: 3.119 ±(99.9%) 0.037 ms/op
Iteration   1: 1.952 ±(99.9%) 0.014 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.755 ±(99.9%) 0.056 ms/op
Iteration   1: 2.797 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.797 ms/op


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
# Warmup Iteration   1: 13.049 ±(99.9%) 0.297 ms/op
Iteration   1: 7.480 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.480 ms/op


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
# Warmup Iteration   1: 4.969 ±(99.9%) 0.120 ms/op
Iteration   1: 3.060 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.769 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.567 ms/op
                 createUser·p0.99:   9.208 ms/op
                 createUser·p0.999:  23.219 ms/op
                 createUser·p0.9999: 23.297 ms/op
                 createUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10424
  mean =      3.060 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2388 
    [ 2.500,  5.000) = 7611 
    [ 5.000,  7.500) = 208 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.769 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.567 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     23.219 ms/op
     p(99.9900) =     23.297 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 3.073 ±(99.9%) 0.071 ms/op
Iteration   1: 1.623 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   1.538 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   3.117 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 9.259 ms/op
                 existUser·p1.00:   9.306 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19684
  mean =      1.623 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 278 
    [ 1.000,  2.000) = 16431 
    [ 2.000,  3.000) = 2757 
    [ 3.000,  4.000) = 138 
    [ 4.000,  5.000) = 45 
    [ 5.000,  6.000) = 3 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.538 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      3.117 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =      9.259 ms/op
     p(99.9990) =      9.306 ms/op
     p(99.9999) =      9.306 ms/op
    p(100.0000) =      9.306 ms/op


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.089 ms/op
Iteration   1: 2.846 ±(99.9%) 0.047 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.966 ms/op
                 getUser·p0.99:   5.942 ms/op
                 getUser·p0.999:  27.877 ms/op
                 getUser·p0.9999: 30.933 ms/op
                 getUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11255
  mean =      2.846 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4246 
    [ 2.500,  5.000) = 6858 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.966 ms/op
     p(99.0000) =      5.942 ms/op
     p(99.9000) =     27.877 ms/op
     p(99.9900) =     30.933 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 11.309 ±(99.9%) 0.332 ms/op
Iteration   1: 7.634 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   3.068 ms/op
                 listUser·p0.50:   7.324 ms/op
                 listUser·p0.90:   9.650 ms/op
                 listUser·p0.95:   10.797 ms/op
                 listUser·p0.99:   18.481 ms/op
                 listUser·p0.999:  25.941 ms/op
                 listUser·p0.9999: 29.164 ms/op
                 listUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4196
  mean =      7.634 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 191 
    [ 5.000,  7.500) = 2120 
    [ 7.500, 10.000) = 1553 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.068 ms/op
     p(50.0000) =      7.324 ms/op
     p(90.0000) =      9.650 ms/op
     p(95.0000) =     10.797 ms/op
     p(99.0000) =     18.481 ms/op
     p(99.9000) =     25.941 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.932          ops/ms
Client.existUser                       thrpt         13.786          ops/ms
Client.getUser                         thrpt          9.430          ops/ms
Client.listUser                        thrpt          3.829          ops/ms
Client.createUser                       avgt          2.859           ms/op
Client.existUser                        avgt          1.952           ms/op
Client.getUser                          avgt          2.797           ms/op
Client.listUser                         avgt          7.480           ms/op
Client.createUser                     sample  10424   3.060 ± 0.049   ms/op
Client.createUser:createUser·p0.00    sample          0.932           ms/op
Client.createUser:createUser·p0.50    sample          2.769           ms/op
Client.createUser:createUser·p0.90    sample          3.867           ms/op
Client.createUser:createUser·p0.95    sample          4.567           ms/op
Client.createUser:createUser·p0.99    sample          9.208           ms/op
Client.createUser:createUser·p0.999   sample         23.219           ms/op
Client.createUser:createUser·p0.9999  sample         23.297           ms/op
Client.createUser:createUser·p1.00    sample         23.298           ms/op
Client.existUser                      sample  19684   1.623 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.536           ms/op
Client.existUser:existUser·p0.50      sample          1.538           ms/op
Client.existUser:existUser·p0.90      sample          2.138           ms/op
Client.existUser:existUser·p0.95      sample          2.355           ms/op
Client.existUser:existUser·p0.99      sample          3.117           ms/op
Client.existUser:existUser·p0.999     sample          8.798           ms/op
Client.existUser:existUser·p0.9999    sample          9.259           ms/op
Client.existUser:existUser·p1.00      sample          9.306           ms/op
Client.getUser                        sample  11255   2.846 ± 0.047   ms/op
Client.getUser:getUser·p0.00          sample          1.033           ms/op
Client.getUser:getUser·p0.50          sample          2.634           ms/op
Client.getUser:getUser·p0.90          sample          3.535           ms/op
Client.getUser:getUser·p0.95          sample          3.966           ms/op
Client.getUser:getUser·p0.99          sample          5.942           ms/op
Client.getUser:getUser·p0.999         sample         27.877           ms/op
Client.getUser:getUser·p0.9999        sample         30.933           ms/op
Client.getUser:getUser·p1.00          sample         30.933           ms/op
Client.listUser                       sample   4196   7.634 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          3.068           ms/op
Client.listUser:listUser·p0.50        sample          7.324           ms/op
Client.listUser:listUser·p0.90        sample          9.650           ms/op
Client.listUser:listUser·p0.95        sample         10.797           ms/op
Client.listUser:listUser·p0.99        sample         18.481           ms/op
Client.listUser:listUser·p0.999       sample         25.941           ms/op
Client.listUser:listUser·p0.9999      sample         29.164           ms/op
Client.listUser:listUser·p1.00        sample         29.164           ms/op
