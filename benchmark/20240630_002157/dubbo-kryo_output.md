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
# Warmup Iteration   1: 1.792 ops/ms
Iteration   1: 7.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.099 ops/ms


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
# Warmup Iteration   1: 5.713 ops/ms
Iteration   1: 9.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.816 ops/ms


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
# Warmup Iteration   1: 5.238 ops/ms
Iteration   1: 11.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.257 ops/ms


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
# Warmup Iteration   1: 4.304 ops/ms
Iteration   1: 8.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.221 ops/ms


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.078 ms/op
Iteration   1: 2.197 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.197 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.054 ms/op
Iteration   1: 2.043 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.043 ms/op


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
# Warmup Iteration   1: 3.423 ±(99.9%) 0.062 ms/op
Iteration   1: 2.165 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.165 ms/op


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.096 ms/op
Iteration   1: 3.225 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.225 ms/op


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.091 ms/op
Iteration   1: 2.305 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   2.064 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.724 ms/op
                 createUser·p0.99:   6.085 ms/op
                 createUser·p0.999:  28.541 ms/op
                 createUser·p0.9999: 31.790 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14209
  mean =      2.305 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12635 
    [ 2.500,  5.000) = 1398 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      6.085 ms/op
     p(99.9000) =     28.541 ms/op
     p(99.9900) =     31.790 ms/op
     p(99.9990) =     32.080 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.066 ms/op
Iteration   1: 1.854 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.477 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.511 ms/op
                 existUser·p0.99:   3.529 ms/op
                 existUser·p0.999:  24.340 ms/op
                 existUser·p0.9999: 26.092 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17238
  mean =      1.854 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16323 
    [ 2.500,  5.000) = 840 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      3.529 ms/op
     p(99.9000) =     24.340 ms/op
     p(99.9900) =     26.092 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.107 ms/op
Iteration   1: 1.994 ±(99.9%) 0.056 ms/op
                 getUser·p0.00:   0.418 ms/op
                 getUser·p0.50:   1.741 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.658 ms/op
                 getUser·p0.99:   4.464 ms/op
                 getUser·p0.999:  43.843 ms/op
                 getUser·p0.9999: 48.130 ms/op
                 getUser·p1.00:   48.169 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16003
  mean =      1.994 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15895 
    [ 5.000, 10.000) = 5 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      4.464 ms/op
     p(99.9000) =     43.843 ms/op
     p(99.9900) =     48.130 ms/op
     p(99.9990) =     48.169 ms/op
     p(99.9999) =     48.169 ms/op
    p(100.0000) =     48.169 ms/op


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.135 ms/op
Iteration   1: 3.522 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   3.342 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  6.281 ms/op
                 listUser·p0.9999: 8.184 ms/op
                 listUser·p1.00:   8.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9088
  mean =      3.522 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 11 
    [1.500, 2.000) = 25 
    [2.000, 2.500) = 368 
    [2.500, 3.000) = 2875 
    [3.000, 3.500) = 1664 
    [3.500, 4.000) = 1653 
    [4.000, 4.500) = 1174 
    [4.500, 5.000) = 866 
    [5.000, 5.500) = 298 
    [5.500, 6.000) = 102 
    [6.000, 6.500) = 47 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      6.281 ms/op
     p(99.9900) =      8.184 ms/op
     p(99.9990) =      8.184 ms/op
     p(99.9999) =      8.184 ms/op
    p(100.0000) =      8.184 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.099          ops/ms
ClientSimple.existUser                       thrpt          9.816          ops/ms
ClientSimple.getUser                         thrpt         11.257          ops/ms
ClientSimple.listUser                        thrpt          8.221          ops/ms
ClientSimple.createUser                       avgt          2.197           ms/op
ClientSimple.existUser                        avgt          2.043           ms/op
ClientSimple.getUser                          avgt          2.165           ms/op
ClientSimple.listUser                         avgt          3.225           ms/op
ClientSimple.createUser                     sample  14209   2.305 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.535           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.064           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.085           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.541           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.790           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.080           ms/op
ClientSimple.existUser                      sample  17238   1.854 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.477           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.702           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.529           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.340           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.092           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.116           ms/op
ClientSimple.getUser                        sample  16003   1.994 ± 0.056   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.418           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.741           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.464           ms/op
ClientSimple.getUser:getUser·p0.999         sample         43.843           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         48.130           ms/op
ClientSimple.getUser:getUser·p1.00          sample         48.169           ms/op
ClientSimple.listUser                       sample   9088   3.522 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.840           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.342           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.997           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.833           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.281           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.184           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.184           ms/op

Benchmark result is saved to 1719706672827.json
