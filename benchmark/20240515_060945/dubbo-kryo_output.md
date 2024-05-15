# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.922 ops/ms
Iteration   1: 7.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.975 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.276 ops/ms
Iteration   1: 12.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.333 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.941 ops/ms
Iteration   1: 14.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.690 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.311 ops/ms
Iteration   1: 9.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.632 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.463 ±(99.9%) 0.063 ms/op
Iteration   1: 1.953 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.529 ±(99.9%) 0.050 ms/op
Iteration   1: 1.788 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.788 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ±(99.9%) 0.060 ms/op
Iteration   1: 2.000 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.000 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.539 ±(99.9%) 0.111 ms/op
Iteration   1: 3.712 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.712 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ±(99.9%) 0.092 ms/op
Iteration   1: 2.150 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.432 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.748 ms/op
                 createUser·p0.99:   7.441 ms/op
                 createUser·p0.999:  26.378 ms/op
                 createUser·p0.9999: 29.105 ms/op
                 createUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14872
  mean =      2.150 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13079 
    [ 2.500,  5.000) = 1615 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      7.441 ms/op
     p(99.9000) =     26.378 ms/op
     p(99.9900) =     29.105 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.001 ±(99.9%) 0.082 ms/op
Iteration   1: 1.763 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   1.696 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.253 ms/op
                 existUser·p0.99:   2.653 ms/op
                 existUser·p0.999:  17.203 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18140
  mean =      1.763 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 574 
    [ 1.250,  2.500) = 17245 
    [ 2.500,  3.750) = 213 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.253 ms/op
     p(99.0000) =      2.653 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.152 ±(99.9%) 0.082 ms/op
Iteration   1: 2.271 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   2.171 ms/op
                 getUser·p0.90:   2.773 ms/op
                 getUser·p0.95:   2.978 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  15.106 ms/op
                 getUser·p0.9999: 15.259 ms/op
                 getUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14148
  mean =      2.271 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 10643 
    [ 2.500,  3.750) = 3154 
    [ 3.750,  5.000) = 139 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     15.259 ms/op
     p(99.9990) =     15.286 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.402 ±(99.9%) 0.173 ms/op
Iteration   1: 3.593 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.942 ms/op
                 listUser·p0.99:   7.652 ms/op
                 listUser·p0.999:  12.129 ms/op
                 listUser·p0.9999: 12.239 ms/op
                 listUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8893
  mean =      3.593 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1379 
    [ 2.500,  3.750) = 3505 
    [ 3.750,  5.000) = 3591 
    [ 5.000,  6.250) = 245 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.942 ms/op
     p(99.0000) =      7.652 ms/op
     p(99.9000) =     12.129 ms/op
     p(99.9900) =     12.239 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.975          ops/ms
ClientSimple.existUser                       thrpt         12.333          ops/ms
ClientSimple.getUser                         thrpt         14.690          ops/ms
ClientSimple.listUser                        thrpt          9.632          ops/ms
ClientSimple.createUser                       avgt          1.953           ms/op
ClientSimple.existUser                        avgt          1.788           ms/op
ClientSimple.getUser                          avgt          2.000           ms/op
ClientSimple.listUser                         avgt          3.712           ms/op
ClientSimple.createUser                     sample  14872   2.150 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.432           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.441           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.378           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.105           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.360           ms/op
ClientSimple.existUser                      sample  18140   1.763 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.586           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.696           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.253           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.653           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.203           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.022           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.022           ms/op
ClientSimple.getUser                        sample  14148   2.271 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.636           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.171           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.978           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.908           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.106           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.259           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.286           ms/op
ClientSimple.listUser                       sample   8893   3.593 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.202           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.678           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.942           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.652           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.129           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.239           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.239           ms/op

Benchmark result is saved to 1715753122964.json
