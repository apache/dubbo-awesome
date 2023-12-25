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
# Warmup Iteration   1: 2.536 ops/ms
Iteration   1: 5.641 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.641 ops/ms


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
# Warmup Iteration   1: 5.779 ops/ms
Iteration   1: 12.964 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.964 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ops/ms
Iteration   1: 9.286 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.286 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.020 ops/ms
Iteration   1: 2.999 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.999 ops/ms


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
# Warmup Iteration   1: 5.302 ±(99.9%) 0.057 ms/op
Iteration   1: 3.152 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.152 ms/op


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
# Warmup Iteration   1: 3.273 ±(99.9%) 0.036 ms/op
Iteration   1: 2.062 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.062 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.072 ms/op
Iteration   1: 3.501 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.501 ms/op


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
# Warmup Iteration   1: 12.140 ±(99.9%) 0.259 ms/op
Iteration   1: 8.353 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.353 ms/op


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
# Warmup Iteration   1: 5.535 ±(99.9%) 0.140 ms/op
Iteration   1: 2.961 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   2.773 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.181 ms/op
                 createUser·p0.999:  12.205 ms/op
                 createUser·p0.9999: 12.416 ms/op
                 createUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11049
  mean =      2.961 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 2331 
    [ 2.500,  3.750) = 7464 
    [ 3.750,  5.000) = 1064 
    [ 5.000,  6.250) = 134 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.181 ms/op
     p(99.9000) =     12.205 ms/op
     p(99.9900) =     12.416 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


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
# Warmup Iteration   1: 2.675 ±(99.9%) 0.067 ms/op
Iteration   1: 1.766 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   2.085 ms/op
                 existUser·p0.95:   2.290 ms/op
                 existUser·p0.99:   3.039 ms/op
                 existUser·p0.999:  19.232 ms/op
                 existUser·p0.9999: 19.637 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18096
  mean =      1.766 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 473 
    [ 1.250,  2.500) = 17240 
    [ 2.500,  3.750) = 294 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.085 ms/op
     p(95.0000) =      2.290 ms/op
     p(99.0000) =      3.039 ms/op
     p(99.9000) =     19.232 ms/op
     p(99.9900) =     19.637 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.706 ±(99.9%) 0.122 ms/op
Iteration   1: 3.176 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  7.942 ms/op
                 getUser·p0.9999: 9.566 ms/op
                 getUser·p1.00:   9.568 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10068
  mean =      3.176 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 17 
    [ 1.000,  2.000) = 247 
    [ 2.000,  3.000) = 4035 
    [ 3.000,  4.000) = 4651 
    [ 4.000,  5.000) = 810 
    [ 5.000,  6.000) = 195 
    [ 6.000,  7.000) = 72 
    [ 7.000,  8.000) = 33 
    [ 8.000,  9.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =      7.942 ms/op
     p(99.9900) =      9.566 ms/op
     p(99.9990) =      9.568 ms/op
     p(99.9999) =      9.568 ms/op
    p(100.0000) =      9.568 ms/op


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
# Warmup Iteration   1: 12.140 ±(99.9%) 0.390 ms/op
Iteration   1: 7.915 ±(99.9%) 0.098 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   7.635 ms/op
                 listUser·p0.90:   9.963 ms/op
                 listUser·p0.95:   10.764 ms/op
                 listUser·p0.99:   14.564 ms/op
                 listUser·p0.999:  21.621 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4028
  mean =      7.915 ±(99.9%) 0.098 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 85 
    [ 5.000,  7.500) = 1724 
    [ 7.500, 10.000) = 1824 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      7.635 ms/op
     p(90.0000) =      9.963 ms/op
     p(95.0000) =     10.764 ms/op
     p(99.0000) =     14.564 ms/op
     p(99.9000) =     21.621 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.641          ops/ms
Client.existUser                       thrpt         12.964          ops/ms
Client.getUser                         thrpt          9.286          ops/ms
Client.listUser                        thrpt          2.999          ops/ms
Client.createUser                       avgt          3.152           ms/op
Client.existUser                        avgt          2.062           ms/op
Client.getUser                          avgt          3.501           ms/op
Client.listUser                         avgt          8.353           ms/op
Client.createUser                     sample  11049   2.961 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.067           ms/op
Client.createUser:createUser·p0.50    sample          2.773           ms/op
Client.createUser:createUser·p0.90    sample          3.858           ms/op
Client.createUser:createUser·p0.95    sample          4.334           ms/op
Client.createUser:createUser·p0.99    sample          5.181           ms/op
Client.createUser:createUser·p0.999   sample         12.205           ms/op
Client.createUser:createUser·p0.9999  sample         12.416           ms/op
Client.createUser:createUser·p1.00    sample         12.419           ms/op
Client.existUser                      sample  18096   1.766 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.646           ms/op
Client.existUser:existUser·p0.50      sample          1.679           ms/op
Client.existUser:existUser·p0.90      sample          2.085           ms/op
Client.existUser:existUser·p0.95      sample          2.290           ms/op
Client.existUser:existUser·p0.99      sample          3.039           ms/op
Client.existUser:existUser·p0.999     sample         19.232           ms/op
Client.existUser:existUser·p0.9999    sample         19.637           ms/op
Client.existUser:existUser·p1.00      sample         19.956           ms/op
Client.getUser                        sample  10068   3.176 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.500           ms/op
Client.getUser:getUser·p0.50          sample          3.105           ms/op
Client.getUser:getUser·p0.90          sample          4.071           ms/op
Client.getUser:getUser·p0.95          sample          4.637           ms/op
Client.getUser:getUser·p0.99          sample          6.644           ms/op
Client.getUser:getUser·p0.999         sample          7.942           ms/op
Client.getUser:getUser·p0.9999        sample          9.566           ms/op
Client.getUser:getUser·p1.00          sample          9.568           ms/op
Client.listUser                       sample   4028   7.915 ± 0.098   ms/op
Client.listUser:listUser·p0.00        sample          2.367           ms/op
Client.listUser:listUser·p0.50        sample          7.635           ms/op
Client.listUser:listUser·p0.90        sample          9.963           ms/op
Client.listUser:listUser·p0.95        sample         10.764           ms/op
Client.listUser:listUser·p0.99        sample         14.564           ms/op
Client.listUser:listUser·p0.999       sample         21.621           ms/op
Client.listUser:listUser·p0.9999      sample         25.133           ms/op
Client.listUser:listUser·p1.00        sample         25.133           ms/op
