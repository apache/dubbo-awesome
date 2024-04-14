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
# Warmup Iteration   1: 1.670 ops/ms
Iteration   1: 7.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.063 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.523 ops/ms
Iteration   1: 13.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.514 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.983 ops/ms
Iteration   1: 13.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.174 ops/ms


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
# Warmup Iteration   1: 6.332 ops/ms
Iteration   1: 9.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.574 ops/ms


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
# Warmup Iteration   1: 3.660 ±(99.9%) 0.057 ms/op
Iteration   1: 2.067 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.067 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.054 ms/op
Iteration   1: 1.972 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.972 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.061 ms/op
Iteration   1: 1.836 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.836 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.097 ms/op
Iteration   1: 3.179 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.179 ms/op


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
# Warmup Iteration   1: 3.538 ±(99.9%) 0.088 ms/op
Iteration   1: 2.091 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.397 ms/op
                 createUser·p0.50:   1.855 ms/op
                 createUser·p0.90:   2.454 ms/op
                 createUser·p0.95:   2.798 ms/op
                 createUser·p0.99:   9.504 ms/op
                 createUser·p0.999:  16.531 ms/op
                 createUser·p0.9999: 20.632 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15293
  mean =      2.091 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13931 
    [ 2.500,  5.000) = 1026 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      9.504 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     20.632 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 2.869 ±(99.9%) 0.067 ms/op
Iteration   1: 1.672 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.346 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   2.159 ms/op
                 existUser·p0.95:   2.306 ms/op
                 existUser·p0.99:   2.937 ms/op
                 existUser·p0.999:  6.259 ms/op
                 existUser·p0.9999: 7.473 ms/op
                 existUser·p1.00:   7.578 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19109
  mean =      1.672 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 6 
    [0.500, 1.000) = 218 
    [1.000, 1.500) = 7858 
    [1.500, 2.000) = 7183 
    [2.000, 2.500) = 3404 
    [2.500, 3.000) = 271 
    [3.000, 3.500) = 31 
    [3.500, 4.000) = 25 
    [4.000, 4.500) = 32 
    [4.500, 5.000) = 33 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 32 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.306 ms/op
     p(99.0000) =      2.937 ms/op
     p(99.9000) =      6.259 ms/op
     p(99.9900) =      7.473 ms/op
     p(99.9990) =      7.578 ms/op
     p(99.9999) =      7.578 ms/op
    p(100.0000) =      7.578 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.092 ms/op
Iteration   1: 2.226 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.326 ms/op
                 getUser·p0.50:   2.040 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   3.058 ms/op
                 getUser·p0.99:   8.612 ms/op
                 getUser·p0.999:  17.748 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14366
  mean =      2.226 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 200 
    [ 1.250,  2.500) = 11593 
    [ 2.500,  3.750) = 2281 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      3.058 ms/op
     p(99.0000) =      8.612 ms/op
     p(99.9000) =     17.748 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 5.346 ±(99.9%) 0.186 ms/op
Iteration   1: 3.412 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   3.285 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.309 ms/op
                 listUser·p0.999:  11.529 ms/op
                 listUser·p0.9999: 11.780 ms/op
                 listUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9372
  mean =      3.412 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 844 
    [ 2.500,  3.750) = 5548 
    [ 3.750,  5.000) = 2689 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.309 ms/op
     p(99.9000) =     11.529 ms/op
     p(99.9900) =     11.780 ms/op
     p(99.9990) =     11.780 ms/op
     p(99.9999) =     11.780 ms/op
    p(100.0000) =     11.780 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.063          ops/ms
ClientSimple.existUser                       thrpt         13.514          ops/ms
ClientSimple.getUser                         thrpt         13.174          ops/ms
ClientSimple.listUser                        thrpt          9.574          ops/ms
ClientSimple.createUser                       avgt          2.067           ms/op
ClientSimple.existUser                        avgt          1.972           ms/op
ClientSimple.getUser                          avgt          1.836           ms/op
ClientSimple.listUser                         avgt          3.179           ms/op
ClientSimple.createUser                     sample  15293   2.091 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.397           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.855           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.504           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.531           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.632           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.840           ms/op
ClientSimple.existUser                      sample  19109   1.672 ± 0.011   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.346           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.620           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.159           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.937           ms/op
ClientSimple.existUser:existUser·p0.999     sample          6.259           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          7.473           ms/op
ClientSimple.existUser:existUser·p1.00      sample          7.578           ms/op
ClientSimple.getUser                        sample  14366   2.226 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.326           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.040           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.058           ms/op
ClientSimple.getUser:getUser·p0.99          sample          8.612           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.748           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.497           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.497           ms/op
ClientSimple.listUser                       sample   9372   3.412 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.874           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.285           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.309           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.529           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.780           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.780           ms/op

Benchmark result is saved to 1713076587465.json
