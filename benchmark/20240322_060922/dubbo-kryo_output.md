# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.874 ops/ms
Iteration   1: 6.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.012 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.889 ops/ms
Iteration   1: 13.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.082 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.851 ops/ms
Iteration   1: 12.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.019 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ops/ms
Iteration   1: 8.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.843 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ±(99.9%) 0.077 ms/op
Iteration   1: 2.318 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.318 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.136 ±(99.9%) 0.067 ms/op
Iteration   1: 1.852 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.852 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.166 ±(99.9%) 0.049 ms/op
Iteration   1: 2.083 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.083 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.263 ±(99.9%) 0.108 ms/op
Iteration   1: 3.276 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.276 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.217 ±(99.9%) 0.341 ms/op
Iteration   1: 2.371 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   2.179 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   7.175 ms/op
                 createUser·p0.999:  38.207 ms/op
                 createUser·p0.9999: 38.512 ms/op
                 createUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13586
  mean =      2.371 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10305 
    [ 2.500,  5.000) = 3045 
    [ 5.000,  7.500) = 104 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      7.175 ms/op
     p(99.9000) =     38.207 ms/op
     p(99.9900) =     38.512 ms/op
     p(99.9990) =     38.535 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.056 ±(99.9%) 0.070 ms/op
Iteration   1: 1.660 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   1.608 ms/op
                 existUser·p0.90:   1.921 ms/op
                 existUser·p0.95:   2.075 ms/op
                 existUser·p0.99:   2.827 ms/op
                 existUser·p0.999:  6.961 ms/op
                 existUser·p0.9999: 11.854 ms/op
                 existUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19244
  mean =      1.660 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 780 
    [ 1.250,  2.500) = 18138 
    [ 2.500,  3.750) = 222 
    [ 3.750,  5.000) = 3 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      1.608 ms/op
     p(90.0000) =      1.921 ms/op
     p(95.0000) =      2.075 ms/op
     p(99.0000) =      2.827 ms/op
     p(99.9000) =      6.961 ms/op
     p(99.9900) =     11.854 ms/op
     p(99.9990) =     12.960 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.259 ±(99.9%) 0.099 ms/op
Iteration   1: 1.971 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.479 ms/op
                 getUser·p0.50:   1.819 ms/op
                 getUser·p0.90:   2.507 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  16.999 ms/op
                 getUser·p0.9999: 21.132 ms/op
                 getUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16218
  mean =      1.971 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14576 
    [ 2.500,  5.000) = 1473 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =     16.999 ms/op
     p(99.9900) =     21.132 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.826 ±(99.9%) 0.155 ms/op
Iteration   1: 3.417 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   3.162 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  25.231 ms/op
                 listUser·p0.9999: 25.756 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9350
  mean =      3.417 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 790 
    [ 2.500,  5.000) = 8299 
    [ 5.000,  7.500) = 164 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     25.231 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.012          ops/ms
ClientSimple.existUser                       thrpt         13.082          ops/ms
ClientSimple.getUser                         thrpt         12.019          ops/ms
ClientSimple.listUser                        thrpt          8.843          ops/ms
ClientSimple.createUser                       avgt          2.318           ms/op
ClientSimple.existUser                        avgt          1.852           ms/op
ClientSimple.getUser                          avgt          2.083           ms/op
ClientSimple.listUser                         avgt          3.276           ms/op
ClientSimple.createUser                     sample  13586   2.371 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.742           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.179           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.117           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.175           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.207           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.512           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.535           ms/op
ClientSimple.existUser                      sample  19244   1.660 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.573           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.608           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.921           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.075           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.827           ms/op
ClientSimple.existUser:existUser·p0.999     sample          6.961           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.854           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.960           ms/op
ClientSimple.getUser                        sample  16218   1.971 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.479           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.819           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.022           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.999           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.132           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.234           ms/op
ClientSimple.listUser                       sample   9350   3.417 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.425           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.162           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.741           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.231           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.756           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.756           ms/op

Benchmark result is saved to 1711087511934.json
