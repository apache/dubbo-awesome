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
# Warmup Iteration   1: 1.833 ops/ms
Iteration   1: 7.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.066 ops/ms


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
# Warmup Iteration   1: 6.430 ops/ms
Iteration   1: 12.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.661 ops/ms


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
# Warmup Iteration   1: 5.845 ops/ms
Iteration   1: 12.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.126 ops/ms


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
# Warmup Iteration   1: 4.616 ops/ms
Iteration   1: 8.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.896 ops/ms


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
# Warmup Iteration   1: 5.035 ±(99.9%) 0.108 ms/op
Iteration   1: 2.104 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.104 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.052 ms/op
Iteration   1: 1.822 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.822 ms/op


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
# Warmup Iteration   1: 3.340 ±(99.9%) 0.069 ms/op
Iteration   1: 2.024 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.024 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.102 ms/op
Iteration   1: 3.401 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.401 ms/op


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
# Warmup Iteration   1: 3.401 ±(99.9%) 0.103 ms/op
Iteration   1: 2.059 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   1.860 ms/op
                 createUser·p0.90:   2.363 ms/op
                 createUser·p0.95:   2.833 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  24.642 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15588
  mean =      2.059 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14472 
    [ 2.500,  5.000) = 802 
    [ 5.000,  7.500) = 210 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.833 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     24.642 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 3.561 ±(99.9%) 0.095 ms/op
Iteration   1: 2.186 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   2.071 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.723 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  14.424 ms/op
                 existUser·p0.9999: 14.582 ms/op
                 existUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14622
  mean =      2.186 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 365 
    [ 1.250,  2.500) = 12138 
    [ 2.500,  3.750) = 1856 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.723 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     14.424 ms/op
     p(99.9900) =     14.582 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.259 ±(99.9%) 0.084 ms/op
Iteration   1: 2.214 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   2.191 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   2.900 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  19.152 ms/op
                 getUser·p0.9999: 19.650 ms/op
                 getUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14634
  mean =      2.214 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 10672 
    [ 2.500,  3.750) = 3711 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =     19.152 ms/op
     p(99.9900) =     19.650 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.174 ms/op
Iteration   1: 3.789 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  26.169 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8475
  mean =      3.789 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 275 
    [ 2.500,  5.000) = 7984 
    [ 5.000,  7.500) = 182 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     26.169 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.066          ops/ms
ClientSimple.existUser                       thrpt         12.661          ops/ms
ClientSimple.getUser                         thrpt         12.126          ops/ms
ClientSimple.listUser                        thrpt          8.896          ops/ms
ClientSimple.createUser                       avgt          2.104           ms/op
ClientSimple.existUser                        avgt          1.822           ms/op
ClientSimple.getUser                          avgt          2.024           ms/op
ClientSimple.listUser                         avgt          3.401           ms/op
ClientSimple.createUser                     sample  15588   2.059 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.898           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.860           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.363           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.833           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.881           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.642           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.740           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.740           ms/op
ClientSimple.existUser                      sample  14622   2.186 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.450           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.071           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.723           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.857           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.424           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.582           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.582           ms/op
ClientSimple.getUser                        sample  14634   2.214 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.656           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.191           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.686           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.152           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.650           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.726           ms/op
ClientSimple.listUser                       sample   8475   3.789 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.149           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.748           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.743           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.169           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.706           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.706           ms/op

Benchmark result is saved to 1715364318231.json
