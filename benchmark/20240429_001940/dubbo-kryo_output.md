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
# Warmup Iteration   1: 1.972 ops/ms
Iteration   1: 6.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.591 ops/ms


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
# Warmup Iteration   1: 5.929 ops/ms
Iteration   1: 13.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.839 ops/ms


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
# Warmup Iteration   1: 4.519 ops/ms
Iteration   1: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.047 ops/ms


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
# Warmup Iteration   1: 3.538 ops/ms
Iteration   1: 7.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.375 ops/ms


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.115 ms/op
Iteration   1: 2.278 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.278 ms/op


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
# Warmup Iteration   1: 3.655 ±(99.9%) 0.070 ms/op
Iteration   1: 2.106 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.106 ms/op


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.079 ms/op
Iteration   1: 2.137 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.137 ms/op


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.077 ms/op
Iteration   1: 3.271 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.271 ms/op


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.095 ms/op
Iteration   1: 2.240 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  15.502 ms/op
                 createUser·p0.9999: 19.118 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14258
  mean =      2.240 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 12737 
    [ 2.500,  3.750) = 1097 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 129 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.502 ms/op
     p(99.9900) =     19.118 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 2.918 ±(99.9%) 0.075 ms/op
Iteration   1: 1.994 ±(99.9%) 0.057 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.728 ms/op
                 existUser·p0.99:   3.962 ms/op
                 existUser·p0.999:  47.907 ms/op
                 existUser·p0.9999: 48.562 ms/op
                 existUser·p1.00:   48.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16029
  mean =      1.994 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15953 
    [ 5.000, 10.000) = 12 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      3.962 ms/op
     p(99.9000) =     47.907 ms/op
     p(99.9900) =     48.562 ms/op
     p(99.9990) =     48.562 ms/op
     p(99.9999) =     48.562 ms/op
    p(100.0000) =     48.562 ms/op


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
# Warmup Iteration   1: 3.362 ±(99.9%) 0.093 ms/op
Iteration   1: 2.437 ±(99.9%) 0.113 ms/op
                 getUser·p0.00:   0.331 ms/op
                 getUser·p0.50:   2.142 ms/op
                 getUser·p0.90:   2.875 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   5.143 ms/op
                 getUser·p0.999:  81.640 ms/op
                 getUser·p0.9999: 89.745 ms/op
                 getUser·p1.00:   90.571 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13314
  mean =      2.437 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 13250 
    [ 10.000,  20.000) = 32 
    [ 20.000,  30.000) = 0 
    [ 30.000,  40.000) = 0 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 0 
    [ 60.000,  70.000) = 0 
    [ 70.000,  80.000) = 19 
    [ 80.000,  90.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.331 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      5.143 ms/op
     p(99.9000) =     81.640 ms/op
     p(99.9900) =     89.745 ms/op
     p(99.9990) =     90.571 ms/op
     p(99.9999) =     90.571 ms/op
    p(100.0000) =     90.571 ms/op


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
# Warmup Iteration   1: 4.836 ±(99.9%) 0.153 ms/op
Iteration   1: 3.509 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   0.687 ms/op
                 listUser·p0.50:   3.088 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.065 ms/op
                 listUser·p0.999:  23.735 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9224
  mean =      3.509 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 611 
    [ 2.500,  5.000) = 7883 
    [ 5.000,  7.500) = 585 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      8.065 ms/op
     p(99.9000) =     23.735 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.591          ops/ms
ClientSimple.existUser                       thrpt         13.839          ops/ms
ClientSimple.getUser                         thrpt         13.047          ops/ms
ClientSimple.listUser                        thrpt          7.375          ops/ms
ClientSimple.createUser                       avgt          2.278           ms/op
ClientSimple.existUser                        avgt          2.106           ms/op
ClientSimple.getUser                          avgt          2.137           ms/op
ClientSimple.listUser                         avgt          3.271           ms/op
ClientSimple.createUser                     sample  14258   2.240 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.133           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.906           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.502           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.118           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.202           ms/op
ClientSimple.existUser                      sample  16029   1.994 ± 0.057   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.598           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.786           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.962           ms/op
ClientSimple.existUser:existUser·p0.999     sample         47.907           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         48.562           ms/op
ClientSimple.existUser:existUser·p1.00      sample         48.562           ms/op
ClientSimple.getUser                        sample  13314   2.437 ± 0.113   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.331           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.142           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.158           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.143           ms/op
ClientSimple.getUser:getUser·p0.999         sample         81.640           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         89.745           ms/op
ClientSimple.getUser:getUser·p1.00          sample         90.571           ms/op
ClientSimple.listUser                       sample   9224   3.509 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.687           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.088           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.546           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.065           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.735           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.740           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.740           ms/op

Benchmark result is saved to 1714349724211.json
