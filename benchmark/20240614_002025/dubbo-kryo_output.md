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
# Warmup Iteration   1: 1.898 ops/ms
Iteration   1: 5.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.639 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.317 ops/ms
Iteration   1: 11.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.615 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ops/ms
Iteration   1: 10.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.751 ops/ms


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
# Warmup Iteration   1: 5.459 ops/ms
Iteration   1: 8.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.171 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.498 ±(99.9%) 0.091 ms/op
Iteration   1: 2.138 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.138 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.164 ±(99.9%) 0.096 ms/op
Iteration   1: 1.934 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.934 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ±(99.9%) 0.063 ms/op
Iteration   1: 2.191 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.191 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.183 ±(99.9%) 0.087 ms/op
Iteration   1: 3.250 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.250 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.521 ±(99.9%) 0.091 ms/op
Iteration   1: 2.238 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.093 ms/op
                 createUser·p0.90:   2.908 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   4.556 ms/op
                 createUser·p0.999:  12.894 ms/op
                 createUser·p0.9999: 13.763 ms/op
                 createUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14382
  mean =      2.238 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 10764 
    [ 2.500,  3.750) = 3365 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      4.556 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.898 ±(99.9%) 0.067 ms/op
Iteration   1: 1.890 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.357 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   3.451 ms/op
                 existUser·p0.999:  30.215 ms/op
                 existUser·p0.9999: 30.910 ms/op
                 existUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16915
  mean =      1.890 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16088 
    [ 2.500,  5.000) = 747 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.451 ms/op
     p(99.9000) =     30.215 ms/op
     p(99.9900) =     30.910 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 3.249 ±(99.9%) 0.086 ms/op
Iteration   1: 1.944 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   1.815 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  11.633 ms/op
                 getUser·p0.9999: 11.842 ms/op
                 getUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16441
  mean =      1.944 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 217 
    [ 1.250,  2.500) = 15095 
    [ 2.500,  3.750) = 928 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     11.842 ms/op
     p(99.9990) =     11.895 ms/op
     p(99.9999) =     11.895 ms/op
    p(100.0000) =     11.895 ms/op


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.170 ms/op
Iteration   1: 3.281 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.698 ms/op
                 listUser·p0.99:   6.060 ms/op
                 listUser·p0.999:  15.918 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9730
  mean =      3.281 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1073 
    [ 2.500,  3.750) = 6637 
    [ 3.750,  5.000) = 1783 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.698 ms/op
     p(99.0000) =      6.060 ms/op
     p(99.9000) =     15.918 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.639          ops/ms
ClientSimple.existUser                       thrpt         11.615          ops/ms
ClientSimple.getUser                         thrpt         10.751          ops/ms
ClientSimple.listUser                        thrpt          8.171          ops/ms
ClientSimple.createUser                       avgt          2.138           ms/op
ClientSimple.existUser                        avgt          1.934           ms/op
ClientSimple.getUser                          avgt          2.191           ms/op
ClientSimple.listUser                         avgt          3.250           ms/op
ClientSimple.createUser                     sample  14382   2.238 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.973           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.093           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.150           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.556           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.894           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.763           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.763           ms/op
ClientSimple.existUser                      sample  16915   1.890 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.357           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.451           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.215           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.910           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.933           ms/op
ClientSimple.getUser                        sample  16441   1.944 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.699           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.815           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.653           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.633           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.842           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.895           ms/op
ClientSimple.listUser                       sample   9730   3.281 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.085           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.064           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.698           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.060           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.918           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.431           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.431           ms/op

Benchmark result is saved to 1718324152943.json
