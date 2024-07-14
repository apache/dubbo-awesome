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
# Warmup Iteration   1: 1.521 ops/ms
Iteration   1: 6.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.910 ops/ms


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
# Warmup Iteration   1: 7.194 ops/ms
Iteration   1: 12.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.754 ops/ms


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
# Warmup Iteration   1: 6.144 ops/ms
Iteration   1: 13.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.889 ops/ms


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
# Warmup Iteration   1: 5.105 ops/ms
Iteration   1: 8.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.217 ops/ms


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
# Warmup Iteration   1: 5.243 ±(99.9%) 0.119 ms/op
Iteration   1: 2.217 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.217 ms/op


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
# Warmup Iteration   1: 3.487 ±(99.9%) 0.052 ms/op
Iteration   1: 1.754 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.754 ms/op


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.068 ms/op
Iteration   1: 2.019 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.019 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.096 ms/op
Iteration   1: 3.135 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.135 ms/op


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
# Warmup Iteration   1: 3.421 ±(99.9%) 0.078 ms/op
Iteration   1: 1.969 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   1.843 ms/op
                 createUser·p0.90:   2.191 ms/op
                 createUser·p0.95:   2.392 ms/op
                 createUser·p0.99:   3.935 ms/op
                 createUser·p0.999:  21.572 ms/op
                 createUser·p0.9999: 23.339 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16219
  mean =      1.969 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15624 
    [ 2.500,  5.000) = 446 
    [ 5.000,  7.500) = 53 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      3.935 ms/op
     p(99.9000) =     21.572 ms/op
     p(99.9900) =     23.339 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 3.048 ±(99.9%) 0.077 ms/op
Iteration   1: 1.770 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.273 ms/op
                 existUser·p0.99:   2.806 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 14.093 ms/op
                 existUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18135
  mean =      1.770 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 17656 
    [ 2.500,  3.750) = 198 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.273 ms/op
     p(99.0000) =      2.806 ms/op
     p(99.9000) =     12.829 ms/op
     p(99.9900) =     14.093 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.114 ms/op
Iteration   1: 2.026 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   1.884 ms/op
                 getUser·p0.90:   2.727 ms/op
                 getUser·p0.95:   2.961 ms/op
                 getUser·p0.99:   4.381 ms/op
                 getUser·p0.999:  16.751 ms/op
                 getUser·p0.9999: 17.684 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15792
  mean =      2.026 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 414 
    [ 1.250,  2.500) = 13072 
    [ 2.500,  3.750) = 2103 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.727 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      4.381 ms/op
     p(99.9000) =     16.751 ms/op
     p(99.9900) =     17.684 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.122 ms/op
Iteration   1: 3.293 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.700 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  10.502 ms/op
                 listUser·p0.9999: 10.617 ms/op
                 listUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9700
  mean =      3.293 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 6 
    [ 1.000,  2.000) = 59 
    [ 2.000,  3.000) = 4471 
    [ 3.000,  4.000) = 3213 
    [ 4.000,  5.000) = 1708 
    [ 5.000,  6.000) = 109 
    [ 6.000,  7.000) = 81 
    [ 7.000,  8.000) = 19 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     10.502 ms/op
     p(99.9900) =     10.617 ms/op
     p(99.9990) =     10.617 ms/op
     p(99.9999) =     10.617 ms/op
    p(100.0000) =     10.617 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.910          ops/ms
ClientSimple.existUser                       thrpt         12.754          ops/ms
ClientSimple.getUser                         thrpt         13.889          ops/ms
ClientSimple.listUser                        thrpt          8.217          ops/ms
ClientSimple.createUser                       avgt          2.217           ms/op
ClientSimple.existUser                        avgt          1.754           ms/op
ClientSimple.getUser                          avgt          2.019           ms/op
ClientSimple.listUser                         avgt          3.135           ms/op
ClientSimple.createUser                     sample  16219   1.969 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.598           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.843           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.191           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.392           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.935           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.572           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.339           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.216           ms/op
ClientSimple.existUser                      sample  18135   1.770 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.716           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.671           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.806           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.829           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.093           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.107           ms/op
ClientSimple.getUser                        sample  15792   2.026 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.864           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.884           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.727           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.961           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.381           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.751           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.684           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.760           ms/op
ClientSimple.listUser                       sample   9700   3.293 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.700           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.035           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.578           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.502           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.617           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.617           ms/op

Benchmark result is saved to 1720959243530.json
