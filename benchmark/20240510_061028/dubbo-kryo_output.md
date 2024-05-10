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
# Warmup Iteration   1: 1.416 ops/ms
Iteration   1: 6.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.679 ops/ms


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
# Warmup Iteration   1: 5.570 ops/ms
Iteration   1: 11.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.724 ops/ms


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
# Warmup Iteration   1: 6.581 ops/ms
Iteration   1: 14.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.445 ops/ms


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
# Warmup Iteration   1: 5.192 ops/ms
Iteration   1: 9.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.199 ops/ms


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.078 ms/op
Iteration   1: 2.172 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.172 ms/op


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
# Warmup Iteration   1: 2.970 ±(99.9%) 0.041 ms/op
Iteration   1: 1.844 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.844 ms/op


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
# Warmup Iteration   1: 3.409 ±(99.9%) 0.061 ms/op
Iteration   1: 2.042 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.108 ms/op
Iteration   1: 3.289 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.289 ms/op


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
# Warmup Iteration   1: 3.452 ±(99.9%) 0.079 ms/op
Iteration   1: 2.551 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.368 ms/op
                 createUser·p0.50:   2.339 ms/op
                 createUser·p0.90:   2.892 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   8.847 ms/op
                 createUser·p0.999:  30.527 ms/op
                 createUser·p0.9999: 31.654 ms/op
                 createUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12616
  mean =      2.551 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8465 
    [ 2.500,  5.000) = 3853 
    [ 5.000,  7.500) = 153 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      2.339 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     30.527 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     31.654 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.093 ms/op
Iteration   1: 2.057 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   2.003 ms/op
                 existUser·p0.90:   2.621 ms/op
                 existUser·p0.95:   2.764 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  11.338 ms/op
                 existUser·p0.9999: 12.048 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15542
  mean =      2.057 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 804 
    [ 1.250,  2.500) = 12462 
    [ 2.500,  3.750) = 2076 
    [ 3.750,  5.000) = 166 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.003 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.764 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =     11.338 ms/op
     p(99.9900) =     12.048 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.081 ms/op
Iteration   1: 2.459 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   2.359 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   2.900 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  27.132 ms/op
                 getUser·p0.9999: 27.754 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13002
  mean =      2.459 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8662 
    [ 2.500,  5.000) = 4268 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      2.359 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =     27.132 ms/op
     p(99.9900) =     27.754 ms/op
     p(99.9990) =     27.754 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.104 ms/op
Iteration   1: 3.087 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.198 ms/op
                 listUser·p0.99:   5.225 ms/op
                 listUser·p0.999:  7.271 ms/op
                 listUser·p0.9999: 7.536 ms/op
                 listUser·p1.00:   7.545 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10410
  mean =      3.087 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 96 
    [2.000, 2.500) = 644 
    [2.500, 3.000) = 5771 
    [3.000, 3.500) = 1622 
    [3.500, 4.000) = 1401 
    [4.000, 4.500) = 501 
    [4.500, 5.000) = 227 
    [5.000, 5.500) = 54 
    [5.500, 6.000) = 32 
    [6.000, 6.500) = 19 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.198 ms/op
     p(99.0000) =      5.225 ms/op
     p(99.9000) =      7.271 ms/op
     p(99.9900) =      7.536 ms/op
     p(99.9990) =      7.545 ms/op
     p(99.9999) =      7.545 ms/op
    p(100.0000) =      7.545 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.679          ops/ms
ClientSimple.existUser                       thrpt         11.724          ops/ms
ClientSimple.getUser                         thrpt         14.445          ops/ms
ClientSimple.listUser                        thrpt          9.199          ops/ms
ClientSimple.createUser                       avgt          2.172           ms/op
ClientSimple.existUser                        avgt          1.844           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.289           ms/op
ClientSimple.createUser                     sample  12616   2.551 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.368           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.339           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.892           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.232           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.847           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.527           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.654           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.654           ms/op
ClientSimple.existUser                      sample  15542   2.057 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.596           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.003           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.764           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.916           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.338           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.048           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.239           ms/op
ClientSimple.getUser                        sample  13002   2.459 ± 0.045   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.044           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.359           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.166           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.132           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.754           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.754           ms/op
ClientSimple.listUser                       sample  10410   3.087 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.883           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.867           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.928           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.198           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.225           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.271           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.536           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.545           ms/op

Benchmark result is saved to 1715321116727.json
