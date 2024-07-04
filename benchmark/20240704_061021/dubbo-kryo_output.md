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
# Warmup Iteration   1: 1.930 ops/ms
Iteration   1: 6.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.410 ops/ms


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
# Warmup Iteration   1: 6.201 ops/ms
Iteration   1: 11.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.672 ops/ms


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
# Warmup Iteration   1: 5.350 ops/ms
Iteration   1: 11.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.314 ops/ms


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
# Warmup Iteration   1: 5.634 ops/ms
Iteration   1: 7.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.786 ops/ms


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.059 ms/op
Iteration   1: 2.213 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.213 ms/op


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.068 ms/op
Iteration   1: 1.846 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.846 ms/op


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.096 ms/op
Iteration   1: 1.915 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.915 ms/op


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.088 ms/op
Iteration   1: 3.740 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.740 ms/op


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.095 ms/op
Iteration   1: 2.106 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   1.954 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.839 ms/op
                 createUser·p0.99:   3.537 ms/op
                 createUser·p0.999:  14.811 ms/op
                 createUser·p0.9999: 15.485 ms/op
                 createUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15178
  mean =      2.106 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 13185 
    [ 2.500,  3.750) = 1798 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      3.537 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     15.485 ms/op
     p(99.9990) =     15.647 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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
# Warmup Iteration   1: 3.099 ±(99.9%) 0.069 ms/op
Iteration   1: 1.850 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.227 ms/op
                 existUser·p0.50:   1.706 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   3.845 ms/op
                 existUser·p0.999:  31.865 ms/op
                 existUser·p0.9999: 32.284 ms/op
                 existUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17564
  mean =      1.850 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16865 
    [ 2.500,  5.000) = 597 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 3 
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
      p(0.0000) =      0.227 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      3.845 ms/op
     p(99.9000) =     31.865 ms/op
     p(99.9900) =     32.284 ms/op
     p(99.9990) =     32.408 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 3.028 ±(99.9%) 0.075 ms/op
Iteration   1: 1.932 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   1.837 ms/op
                 getUser·p0.90:   2.437 ms/op
                 getUser·p0.95:   2.605 ms/op
                 getUser·p0.99:   2.949 ms/op
                 getUser·p0.999:  10.466 ms/op
                 getUser·p0.9999: 11.447 ms/op
                 getUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16657
  mean =      1.932 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 245 
    [ 1.250,  2.500) = 15094 
    [ 2.500,  3.750) = 1236 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      2.949 ms/op
     p(99.9000) =     10.466 ms/op
     p(99.9900) =     11.447 ms/op
     p(99.9990) =     11.698 ms/op
     p(99.9999) =     11.698 ms/op
    p(100.0000) =     11.698 ms/op


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.123 ms/op
Iteration   1: 3.585 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  8.405 ms/op
                 listUser·p0.9999: 8.634 ms/op
                 listUser·p1.00:   8.634 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8930
  mean =      3.585 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 5 
    [1.500, 2.000) = 18 
    [2.000, 2.500) = 238 
    [2.500, 3.000) = 1511 
    [3.000, 3.500) = 2238 
    [3.500, 4.000) = 2972 
    [4.000, 4.500) = 1322 
    [4.500, 5.000) = 374 
    [5.000, 5.500) = 121 
    [5.500, 6.000) = 93 
    [6.000, 6.500) = 18 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =      8.634 ms/op
     p(99.9990) =      8.634 ms/op
     p(99.9999) =      8.634 ms/op
    p(100.0000) =      8.634 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.410          ops/ms
ClientSimple.existUser                       thrpt         11.672          ops/ms
ClientSimple.getUser                         thrpt         11.314          ops/ms
ClientSimple.listUser                        thrpt          7.786          ops/ms
ClientSimple.createUser                       avgt          2.213           ms/op
ClientSimple.existUser                        avgt          1.846           ms/op
ClientSimple.getUser                          avgt          1.915           ms/op
ClientSimple.listUser                         avgt          3.740           ms/op
ClientSimple.createUser                     sample  15178   2.106 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.752           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.954           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.537           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.811           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.485           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.647           ms/op
ClientSimple.existUser                      sample  17564   1.850 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.227           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.706           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.845           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.865           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.284           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.408           ms/op
ClientSimple.getUser                        sample  16657   1.932 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.699           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.837           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.466           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.447           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.698           ms/op
ClientSimple.listUser                       sample   8930   3.585 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.188           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.677           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.405           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.634           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.634           ms/op

Benchmark result is saved to 1720073153735.json
