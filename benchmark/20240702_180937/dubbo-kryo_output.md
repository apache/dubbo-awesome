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
# Warmup Iteration   1: 1.756 ops/ms
Iteration   1: 7.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.511 ops/ms


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
# Warmup Iteration   1: 6.369 ops/ms
Iteration   1: 12.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.755 ops/ms


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
# Warmup Iteration   1: 4.958 ops/ms
Iteration   1: 11.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.616 ops/ms


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
# Warmup Iteration   1: 6.092 ops/ms
Iteration   1: 8.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.672 ops/ms


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
# Warmup Iteration   1: 4.256 ±(99.9%) 0.078 ms/op
Iteration   1: 2.177 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.177 ms/op


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
# Warmup Iteration   1: 3.156 ±(99.9%) 0.054 ms/op
Iteration   1: 1.892 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.892 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.061 ms/op
Iteration   1: 1.962 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.962 ms/op


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.079 ms/op
Iteration   1: 3.682 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.682 ms/op


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
# Warmup Iteration   1: 3.085 ±(99.9%) 0.077 ms/op
Iteration   1: 2.336 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  28.344 ms/op
                 createUser·p0.9999: 29.456 ms/op
                 createUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13964
  mean =      2.336 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11177 
    [ 2.500,  5.000) = 2672 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =     28.344 ms/op
     p(99.9900) =     29.456 ms/op
     p(99.9990) =     29.884 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 2.957 ±(99.9%) 0.070 ms/op
Iteration   1: 2.022 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.476 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.919 ms/op
                 existUser·p0.99:   4.257 ms/op
                 existUser·p0.999:  13.240 ms/op
                 existUser·p0.9999: 14.764 ms/op
                 existUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15865
  mean =      2.022 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 495 
    [ 1.250,  2.500) = 13880 
    [ 2.500,  3.750) = 1218 
    [ 3.750,  5.000) = 152 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.919 ms/op
     p(99.0000) =      4.257 ms/op
     p(99.9000) =     13.240 ms/op
     p(99.9900) =     14.764 ms/op
     p(99.9990) =     15.581 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 3.397 ±(99.9%) 0.077 ms/op
Iteration   1: 2.155 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.032 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.945 ms/op
                 getUser·p0.99:   4.438 ms/op
                 getUser·p0.999:  14.189 ms/op
                 getUser·p0.9999: 14.707 ms/op
                 getUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14845
  mean =      2.155 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 12317 
    [ 2.500,  3.750) = 2185 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      4.438 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     14.707 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.121 ms/op
Iteration   1: 3.601 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.391 ms/op
                 listUser·p0.999:  20.906 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8888
  mean =      3.601 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 657 
    [ 2.500,  5.000) = 7964 
    [ 5.000,  7.500) = 191 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.391 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.511          ops/ms
ClientSimple.existUser                       thrpt         12.755          ops/ms
ClientSimple.getUser                         thrpt         11.616          ops/ms
ClientSimple.listUser                        thrpt          8.672          ops/ms
ClientSimple.createUser                       avgt          2.177           ms/op
ClientSimple.existUser                        avgt          1.892           ms/op
ClientSimple.getUser                          avgt          1.962           ms/op
ClientSimple.listUser                         avgt          3.682           ms/op
ClientSimple.createUser                     sample  13964   2.336 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.664           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.092           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.637           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.344           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.456           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.884           ms/op
ClientSimple.existUser                      sample  15865   2.022 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.476           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.880           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.919           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.257           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.240           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.764           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.581           ms/op
ClientSimple.getUser                        sample  14845   2.155 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.995           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.032           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.945           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.438           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.189           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.707           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.778           ms/op
ClientSimple.listUser                       sample   8888   3.601 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.139           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.609           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.391           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.906           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.791           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.791           ms/op

Benchmark result is saved to 1719943522451.json
