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
# Warmup Iteration   1: 1.841 ops/ms
Iteration   1: 7.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.221 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.140 ops/ms
Iteration   1: 12.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.222 ops/ms


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
# Warmup Iteration   1: 5.160 ops/ms
Iteration   1: 12.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.167 ops/ms


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
# Warmup Iteration   1: 5.469 ops/ms
Iteration   1: 8.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.458 ops/ms


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.082 ms/op
Iteration   1: 2.288 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.288 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.487 ±(99.9%) 0.057 ms/op
Iteration   1: 1.908 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.908 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ±(99.9%) 0.062 ms/op
Iteration   1: 2.201 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.201 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.389 ±(99.9%) 0.089 ms/op
Iteration   1: 3.323 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.323 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.522 ±(99.9%) 0.093 ms/op
Iteration   1: 1.985 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   1.755 ms/op
                 createUser·p0.90:   2.503 ms/op
                 createUser·p0.95:   2.671 ms/op
                 createUser·p0.99:   3.423 ms/op
                 createUser·p0.999:  18.940 ms/op
                 createUser·p0.9999: 24.017 ms/op
                 createUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16114
  mean =      1.985 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14486 
    [ 2.500,  5.000) = 1505 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      1.755 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.423 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     24.017 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 2.842 ±(99.9%) 0.064 ms/op
Iteration   1: 2.050 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   1.954 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.736 ms/op
                 existUser·p0.99:   3.256 ms/op
                 existUser·p0.999:  23.265 ms/op
                 existUser·p0.9999: 24.269 ms/op
                 existUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15632
  mean =      2.050 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13167 
    [ 2.500,  5.000) = 2399 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      3.256 ms/op
     p(99.9000) =     23.265 ms/op
     p(99.9900) =     24.269 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 3.389 ±(99.9%) 0.087 ms/op
Iteration   1: 1.964 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.531 ms/op
                 getUser·p0.99:   3.015 ms/op
                 getUser·p0.999:  14.565 ms/op
                 getUser·p0.9999: 14.977 ms/op
                 getUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16293
  mean =      1.964 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 15219 
    [ 2.500,  3.750) = 936 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      3.015 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     14.977 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.154 ms/op
Iteration   1: 3.227 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.240 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.782 ms/op
                 listUser·p0.999:  7.954 ms/op
                 listUser·p0.9999: 8.094 ms/op
                 listUser·p1.00:   8.094 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9920
  mean =      3.227 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 267 
    [2.000, 2.500) = 1942 
    [2.500, 3.000) = 1781 
    [3.000, 3.500) = 2148 
    [3.500, 4.000) = 2449 
    [4.000, 4.500) = 876 
    [4.500, 5.000) = 227 
    [5.000, 5.500) = 75 
    [5.500, 6.000) = 59 
    [6.000, 6.500) = 11 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 28 
    [7.500, 8.000) = 32 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.782 ms/op
     p(99.9000) =      7.954 ms/op
     p(99.9900) =      8.094 ms/op
     p(99.9990) =      8.094 ms/op
     p(99.9999) =      8.094 ms/op
    p(100.0000) =      8.094 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.221          ops/ms
ClientSimple.existUser                       thrpt         12.222          ops/ms
ClientSimple.getUser                         thrpt         12.167          ops/ms
ClientSimple.listUser                        thrpt          8.458          ops/ms
ClientSimple.createUser                       avgt          2.288           ms/op
ClientSimple.existUser                        avgt          1.908           ms/op
ClientSimple.getUser                          avgt          2.201           ms/op
ClientSimple.listUser                         avgt          3.323           ms/op
ClientSimple.createUser                     sample  16114   1.985 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.885           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.755           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.503           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.423           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.940           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.017           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.117           ms/op
ClientSimple.existUser                      sample  15632   2.050 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.484           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.954           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.736           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.256           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.265           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.269           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.379           ms/op
ClientSimple.getUser                        sample  16293   1.964 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.820           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.015           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.565           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.977           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.008           ms/op
ClientSimple.listUser                       sample   9920   3.227 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.988           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.240           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.108           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.782           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.954           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.094           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.094           ms/op

Benchmark result is saved to 1715666785999.json
