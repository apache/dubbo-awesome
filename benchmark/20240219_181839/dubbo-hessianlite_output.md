# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.342 ops/ms
Iteration   1: 6.359 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.359 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.241 ops/ms
Iteration   1: 11.457 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.457 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.808 ops/ms
Iteration   1: 9.026 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.026 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.067 ops/ms
Iteration   1: 3.959 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.959 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.122 ±(99.9%) 0.069 ms/op
Iteration   1: 3.118 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.118 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.050 ±(99.9%) 0.028 ms/op
Iteration   1: 2.001 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.533 ±(99.9%) 0.061 ms/op
Iteration   1: 3.411 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.411 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.784 ±(99.9%) 0.209 ms/op
Iteration   1: 9.602 ±(99.9%) 0.113 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.602 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.087 ±(99.9%) 0.095 ms/op
Iteration   1: 2.972 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   2.785 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   8.507 ms/op
                 createUser·p0.999:  14.667 ms/op
                 createUser·p0.9999: 16.089 ms/op
                 createUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10775
  mean =      2.972 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 2950 
    [ 2.500,  3.750) = 6901 
    [ 3.750,  5.000) = 558 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      8.507 ms/op
     p(99.9000) =     14.667 ms/op
     p(99.9900) =     16.089 ms/op
     p(99.9990) =     16.089 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.151 ±(99.9%) 0.068 ms/op
Iteration   1: 1.841 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.958 ms/op
                 existUser·p0.999:  22.151 ms/op
                 existUser·p0.9999: 22.422 ms/op
                 existUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17380
  mean =      1.841 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16604 
    [ 2.500,  5.000) = 703 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.958 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     22.422 ms/op
     p(99.9990) =     22.446 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.793 ±(99.9%) 0.107 ms/op
Iteration   1: 3.318 ±(99.9%) 0.065 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  35.324 ms/op
                 getUser·p0.9999: 36.962 ms/op
                 getUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9668
  mean =      3.318 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1110 
    [ 2.500,  5.000) = 8288 
    [ 5.000,  7.500) = 231 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     35.324 ms/op
     p(99.9900) =     36.962 ms/op
     p(99.9990) =     36.962 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.648 ±(99.9%) 0.614 ms/op
Iteration   1: 8.251 ±(99.9%) 0.139 ms/op
                 listUser·p0.00:   3.092 ms/op
                 listUser·p0.50:   7.832 ms/op
                 listUser·p0.90:   10.420 ms/op
                 listUser·p0.95:   11.600 ms/op
                 listUser·p0.99:   16.024 ms/op
                 listUser·p0.999:  32.952 ms/op
                 listUser·p0.9999: 34.406 ms/op
                 listUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3874
  mean =      8.251 ±(99.9%) 0.139 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 72 
    [ 5.000,  7.500) = 1472 
    [ 7.500, 10.000) = 1855 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.092 ms/op
     p(50.0000) =      7.832 ms/op
     p(90.0000) =     10.420 ms/op
     p(95.0000) =     11.600 ms/op
     p(99.0000) =     16.024 ms/op
     p(99.9000) =     32.952 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.359          ops/ms
Client.existUser                       thrpt         11.457          ops/ms
Client.getUser                         thrpt          9.026          ops/ms
Client.listUser                        thrpt          3.959          ops/ms
Client.createUser                       avgt          3.118           ms/op
Client.existUser                        avgt          2.001           ms/op
Client.getUser                          avgt          3.411           ms/op
Client.listUser                         avgt          9.602           ms/op
Client.createUser                     sample  10775   2.972 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          0.580           ms/op
Client.createUser:createUser·p0.50    sample          2.785           ms/op
Client.createUser:createUser·p0.90    sample          3.600           ms/op
Client.createUser:createUser·p0.95    sample          4.243           ms/op
Client.createUser:createUser·p0.99    sample          8.507           ms/op
Client.createUser:createUser·p0.999   sample         14.667           ms/op
Client.createUser:createUser·p0.9999  sample         16.089           ms/op
Client.createUser:createUser·p1.00    sample         16.089           ms/op
Client.existUser                      sample  17380   1.841 ± 0.025   ms/op
Client.existUser:existUser·p0.00      sample          0.626           ms/op
Client.existUser:existUser·p0.50      sample          1.753           ms/op
Client.existUser:existUser·p0.90      sample          2.257           ms/op
Client.existUser:existUser·p0.95      sample          2.454           ms/op
Client.existUser:existUser·p0.99      sample          3.958           ms/op
Client.existUser:existUser·p0.999     sample         22.151           ms/op
Client.existUser:existUser·p0.9999    sample         22.422           ms/op
Client.existUser:existUser·p1.00      sample         22.446           ms/op
Client.getUser                        sample   9668   3.318 ± 0.065   ms/op
Client.getUser:getUser·p0.00          sample          0.814           ms/op
Client.getUser:getUser·p0.50          sample          3.142           ms/op
Client.getUser:getUser·p0.90          sample          4.022           ms/op
Client.getUser:getUser·p0.95          sample          4.473           ms/op
Client.getUser:getUser·p0.99          sample          6.849           ms/op
Client.getUser:getUser·p0.999         sample         35.324           ms/op
Client.getUser:getUser·p0.9999        sample         36.962           ms/op
Client.getUser:getUser·p1.00          sample         36.962           ms/op
Client.listUser                       sample   3874   8.251 ± 0.139   ms/op
Client.listUser:listUser·p0.00        sample          3.092           ms/op
Client.listUser:listUser·p0.50        sample          7.832           ms/op
Client.listUser:listUser·p0.90        sample         10.420           ms/op
Client.listUser:listUser·p0.95        sample         11.600           ms/op
Client.listUser:listUser·p0.99        sample         16.024           ms/op
Client.listUser:listUser·p0.999       sample         32.952           ms/op
Client.listUser:listUser·p0.9999      sample         34.406           ms/op
Client.listUser:listUser·p1.00        sample         34.406           ms/op
