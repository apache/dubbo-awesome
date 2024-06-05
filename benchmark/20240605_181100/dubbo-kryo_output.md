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
# Warmup Iteration   1: 2.048 ops/ms
Iteration   1: 6.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.757 ops/ms


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
# Warmup Iteration   1: 6.099 ops/ms
Iteration   1: 11.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.447 ops/ms


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
# Warmup Iteration   1: 6.191 ops/ms
Iteration   1: 14.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.955 ops/ms


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
# Warmup Iteration   1: 4.551 ops/ms
Iteration   1: 7.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.882 ops/ms


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
# Warmup Iteration   1: 4.314 ±(99.9%) 0.086 ms/op
Iteration   1: 2.196 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.196 ms/op


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
# Warmup Iteration   1: 3.493 ±(99.9%) 0.060 ms/op
Iteration   1: 1.847 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.847 ms/op


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
# Warmup Iteration   1: 3.269 ±(99.9%) 0.060 ms/op
Iteration   1: 1.891 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.891 ms/op


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
# Warmup Iteration   1: 4.795 ±(99.9%) 0.084 ms/op
Iteration   1: 3.252 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.252 ms/op


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.137 ms/op
Iteration   1: 2.261 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   2.023 ms/op
                 createUser·p0.90:   2.753 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  26.673 ms/op
                 createUser·p0.9999: 29.494 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14162
  mean =      2.261 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11276 
    [ 2.500,  5.000) = 2593 
    [ 5.000,  7.500) = 160 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     26.673 ms/op
     p(99.9900) =     29.494 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 3.002 ±(99.9%) 0.073 ms/op
Iteration   1: 1.785 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   1.614 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   4.528 ms/op
                 existUser·p0.999:  14.418 ms/op
                 existUser·p0.9999: 14.959 ms/op
                 existUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17924
  mean =      1.785 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 215 
    [ 1.250,  2.500) = 16784 
    [ 2.500,  3.750) = 734 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      1.614 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      4.528 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     14.959 ms/op
     p(99.9990) =     14.959 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 3.587 ±(99.9%) 0.107 ms/op
Iteration   1: 2.110 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   1.907 ms/op
                 getUser·p0.90:   2.851 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  12.698 ms/op
                 getUser·p0.9999: 12.867 ms/op
                 getUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15300
  mean =      2.110 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 12796 
    [ 2.500,  3.750) = 2249 
    [ 3.750,  5.000) = 159 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     12.867 ms/op
     p(99.9990) =     12.911 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


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
# Warmup Iteration   1: 6.117 ±(99.9%) 0.164 ms/op
Iteration   1: 3.872 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   0.618 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   14.877 ms/op
                 listUser·p0.999:  62.718 ms/op
                 listUser·p0.9999: 68.813 ms/op
                 listUser·p1.00:   68.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8236
  mean =      3.872 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7834 
    [ 5.000, 10.000) = 293 
    [10.000, 15.000) = 36 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =     14.877 ms/op
     p(99.9000) =     62.718 ms/op
     p(99.9900) =     68.813 ms/op
     p(99.9990) =     68.813 ms/op
     p(99.9999) =     68.813 ms/op
    p(100.0000) =     68.813 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.757          ops/ms
ClientSimple.existUser                       thrpt         11.447          ops/ms
ClientSimple.getUser                         thrpt         14.955          ops/ms
ClientSimple.listUser                        thrpt          7.882          ops/ms
ClientSimple.createUser                       avgt          2.196           ms/op
ClientSimple.existUser                        avgt          1.847           ms/op
ClientSimple.getUser                          avgt          1.891           ms/op
ClientSimple.listUser                         avgt          3.252           ms/op
ClientSimple.createUser                     sample  14162   2.261 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.581           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.023           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.224           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.053           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.673           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.494           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.590           ms/op
ClientSimple.existUser                      sample  17924   1.785 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.676           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.614           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.528           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.418           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.959           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.959           ms/op
ClientSimple.getUser                        sample  15300   2.110 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.761           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.907           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.211           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.895           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.698           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.867           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.911           ms/op
ClientSimple.listUser                       sample   8236   3.872 ± 0.137   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.618           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.535           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample         14.877           ms/op
ClientSimple.listUser:listUser·p0.999       sample         62.718           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         68.813           ms/op
ClientSimple.listUser:listUser·p1.00        sample         68.813           ms/op

Benchmark result is saved to 1717610704740.json
