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
# Warmup Iteration   1: 1.857 ops/ms
Iteration   1: 6.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.262 ops/ms


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
# Warmup Iteration   1: 6.576 ops/ms
Iteration   1: 14.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.250 ops/ms


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
# Warmup Iteration   1: 5.448 ops/ms
Iteration   1: 12.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.873 ops/ms


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
# Warmup Iteration   1: 4.747 ops/ms
Iteration   1: 8.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.269 ops/ms


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.079 ms/op
Iteration   1: 2.030 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.030 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.049 ms/op
Iteration   1: 1.860 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


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
# Warmup Iteration   1: 3.504 ±(99.9%) 0.056 ms/op
Iteration   1: 1.935 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.935 ms/op


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
# Warmup Iteration   1: 4.365 ±(99.9%) 0.087 ms/op
Iteration   1: 3.191 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.191 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.107 ms/op
Iteration   1: 2.297 ±(99.9%) 0.090 ms/op
                 createUser·p0.00:   0.538 ms/op
                 createUser·p0.50:   1.824 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.929 ms/op
                 createUser·p0.99:   14.119 ms/op
                 createUser·p0.999:  41.157 ms/op
                 createUser·p0.9999: 69.838 ms/op
                 createUser·p1.00:   69.992 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13920
  mean =      2.297 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13543 
    [ 5.000, 10.000) = 110 
    [10.000, 15.000) = 134 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 18 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 30 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      1.824 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =     14.119 ms/op
     p(99.9000) =     41.157 ms/op
     p(99.9900) =     69.838 ms/op
     p(99.9990) =     69.992 ms/op
     p(99.9999) =     69.992 ms/op
    p(100.0000) =     69.992 ms/op


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
# Warmup Iteration   1: 2.995 ±(99.9%) 0.065 ms/op
Iteration   1: 1.703 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   1.858 ms/op
                 existUser·p0.95:   2.057 ms/op
                 existUser·p0.99:   2.724 ms/op
                 existUser·p0.999:  30.999 ms/op
                 existUser·p0.9999: 31.752 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18771
  mean =      1.703 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18444 
    [ 2.500,  5.000) = 251 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
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
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      1.858 ms/op
     p(95.0000) =      2.057 ms/op
     p(99.0000) =      2.724 ms/op
     p(99.9000) =     30.999 ms/op
     p(99.9900) =     31.752 ms/op
     p(99.9990) =     31.752 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.080 ms/op
Iteration   1: 2.079 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   1.800 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   2.990 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  15.956 ms/op
                 getUser·p0.9999: 16.903 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15556
  mean =      2.079 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 12391 
    [ 2.500,  3.750) = 2789 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =     15.956 ms/op
     p(99.9900) =     16.903 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.143 ms/op
Iteration   1: 3.647 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.796 ms/op
                 listUser·p0.99:   5.864 ms/op
                 listUser·p0.999:  8.602 ms/op
                 listUser·p0.9999: 8.651 ms/op
                 listUser·p1.00:   8.651 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8809
  mean =      3.647 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 49 
    [2.000, 2.500) = 325 
    [2.500, 3.000) = 1164 
    [3.000, 3.500) = 2319 
    [3.500, 4.000) = 2352 
    [4.000, 4.500) = 1655 
    [4.500, 5.000) = 672 
    [5.000, 5.500) = 140 
    [5.500, 6.000) = 48 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 38 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.796 ms/op
     p(99.0000) =      5.864 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =      8.651 ms/op
     p(99.9990) =      8.651 ms/op
     p(99.9999) =      8.651 ms/op
    p(100.0000) =      8.651 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.262          ops/ms
ClientSimple.existUser                       thrpt         14.250          ops/ms
ClientSimple.getUser                         thrpt         12.873          ops/ms
ClientSimple.listUser                        thrpt          8.269          ops/ms
ClientSimple.createUser                       avgt          2.030           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          1.935           ms/op
ClientSimple.listUser                         avgt          3.191           ms/op
ClientSimple.createUser                     sample  13920   2.297 ± 0.090   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.538           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.824           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.99    sample         14.119           ms/op
ClientSimple.createUser:createUser·p0.999   sample         41.157           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         69.838           ms/op
ClientSimple.createUser:createUser·p1.00    sample         69.992           ms/op
ClientSimple.existUser                      sample  18771   1.703 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.608           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.597           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.858           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.057           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.999           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.752           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.752           ms/op
ClientSimple.getUser                        sample  15556   2.079 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.597           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.800           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.990           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.964           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.956           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.903           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.695           ms/op
ClientSimple.listUser                       sample   8809   3.647 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.466           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.796           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.864           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.602           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.651           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.651           ms/op

Benchmark result is saved to 1716228318293.json
