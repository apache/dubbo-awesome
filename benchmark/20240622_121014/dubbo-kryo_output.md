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
# Warmup Iteration   1: 1.683 ops/ms
Iteration   1: 7.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.401 ops/ms


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
# Warmup Iteration   1: 5.407 ops/ms
Iteration   1: 12.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.571 ops/ms


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
# Warmup Iteration   1: 4.878 ops/ms
Iteration   1: 13.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.006 ops/ms


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
# Warmup Iteration   1: 4.990 ops/ms
Iteration   1: 9.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.033 ops/ms


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
# Warmup Iteration   1: 3.555 ±(99.9%) 0.064 ms/op
Iteration   1: 2.382 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.382 ms/op


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.062 ms/op
Iteration   1: 1.994 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.994 ms/op


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
# Warmup Iteration   1: 3.271 ±(99.9%) 0.065 ms/op
Iteration   1: 2.006 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.006 ms/op


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
# Warmup Iteration   1: 4.675 ±(99.9%) 0.095 ms/op
Iteration   1: 3.363 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.363 ms/op


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.126 ms/op
Iteration   1: 2.338 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   2.122 ms/op
                 createUser·p0.90:   3.187 ms/op
                 createUser·p0.95:   3.482 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  21.987 ms/op
                 createUser·p0.9999: 22.205 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13703
  mean =      2.338 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10045 
    [ 2.500,  5.000) = 3472 
    [ 5.000,  7.500) = 153 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      3.187 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     22.205 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 3.094 ±(99.9%) 0.070 ms/op
Iteration   1: 1.926 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.468 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 14.353 ms/op
                 existUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16607
  mean =      1.926 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 15712 
    [ 2.500,  3.750) = 620 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.468 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     14.353 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.440 ±(99.9%) 0.097 ms/op
Iteration   1: 1.939 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   1.821 ms/op
                 getUser·p0.90:   2.439 ms/op
                 getUser·p0.95:   2.691 ms/op
                 getUser·p0.99:   4.175 ms/op
                 getUser·p0.999:  15.835 ms/op
                 getUser·p0.9999: 16.651 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16485
  mean =      1.939 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 231 
    [ 1.250,  2.500) = 14903 
    [ 2.500,  3.750) = 1140 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.439 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      4.175 ms/op
     p(99.9000) =     15.835 ms/op
     p(99.9900) =     16.651 ms/op
     p(99.9990) =     16.810 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.583 ±(99.9%) 0.140 ms/op
Iteration   1: 3.626 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.763 ms/op
                 listUser·p0.99:   6.674 ms/op
                 listUser·p0.999:  27.325 ms/op
                 listUser·p0.9999: 28.574 ms/op
                 listUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8830
  mean =      3.626 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 519 
    [ 2.500,  5.000) = 7989 
    [ 5.000,  7.500) = 253 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.763 ms/op
     p(99.0000) =      6.674 ms/op
     p(99.9000) =     27.325 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.401          ops/ms
ClientSimple.existUser                       thrpt         12.571          ops/ms
ClientSimple.getUser                         thrpt         13.006          ops/ms
ClientSimple.listUser                        thrpt          9.033          ops/ms
ClientSimple.createUser                       avgt          2.382           ms/op
ClientSimple.existUser                        avgt          1.994           ms/op
ClientSimple.getUser                          avgt          2.006           ms/op
ClientSimple.listUser                         avgt          3.363           ms/op
ClientSimple.createUser                     sample  13703   2.338 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.829           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.122           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.187           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.482           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.078           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.987           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.205           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.217           ms/op
ClientSimple.existUser                      sample  16607   1.926 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.677           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.833           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.468           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.604           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.877           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.353           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.385           ms/op
ClientSimple.getUser                        sample  16485   1.939 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.932           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.821           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.439           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.175           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.835           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.651           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.810           ms/op
ClientSimple.listUser                       sample   8830   3.626 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.952           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.523           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.763           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.674           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.325           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.574           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.574           ms/op

Benchmark result is saved to 1719057961541.json
