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
# Warmup Iteration   1: 0.865 ops/ms
Iteration   1: 5.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.749 ops/ms


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
# Warmup Iteration   1: 5.683 ops/ms
Iteration   1: 12.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.212 ops/ms


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
# Warmup Iteration   1: 5.679 ops/ms
Iteration   1: 12.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.631 ops/ms


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
# Warmup Iteration   1: 5.143 ops/ms
Iteration   1: 7.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.489 ops/ms


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.079 ms/op
Iteration   1: 2.167 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.167 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.059 ms/op
Iteration   1: 2.084 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.084 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.060 ms/op
Iteration   1: 1.908 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.449 ±(99.9%) 0.095 ms/op
Iteration   1: 3.854 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.854 ms/op


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
# Warmup Iteration   1: 3.473 ±(99.9%) 0.103 ms/op
Iteration   1: 2.275 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   1.995 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   12.206 ms/op
                 createUser·p0.999:  17.910 ms/op
                 createUser·p0.9999: 18.239 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14047
  mean =      2.275 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 11797 
    [ 2.500,  3.750) = 1782 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 134 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     17.910 ms/op
     p(99.9900) =     18.239 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.077 ms/op
Iteration   1: 2.072 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.389 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.724 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   6.313 ms/op
                 existUser·p0.999:  20.382 ms/op
                 existUser·p0.9999: 20.495 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15440
  mean =      2.072 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12309 
    [ 2.500,  5.000) = 2951 
    [ 5.000,  7.500) = 71 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      6.313 ms/op
     p(99.9000) =     20.382 ms/op
     p(99.9900) =     20.495 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 3.227 ±(99.9%) 0.075 ms/op
Iteration   1: 2.062 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   1.997 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   3.363 ms/op
                 getUser·p0.999:  15.620 ms/op
                 getUser·p0.9999: 16.214 ms/op
                 getUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15628
  mean =      2.062 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 202 
    [ 1.250,  2.500) = 13391 
    [ 2.500,  3.750) = 1942 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      3.363 ms/op
     p(99.9000) =     15.620 ms/op
     p(99.9900) =     16.214 ms/op
     p(99.9990) =     16.269 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 5.223 ±(99.9%) 0.158 ms/op
Iteration   1: 3.748 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   6.713 ms/op
                 listUser·p0.999:  15.032 ms/op
                 listUser·p0.9999: 15.139 ms/op
                 listUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8529
  mean =      3.748 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 345 
    [ 2.500,  3.750) = 4512 
    [ 3.750,  5.000) = 3216 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.713 ms/op
     p(99.9000) =     15.032 ms/op
     p(99.9900) =     15.139 ms/op
     p(99.9990) =     15.139 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.749          ops/ms
ClientSimple.existUser                       thrpt         12.212          ops/ms
ClientSimple.getUser                         thrpt         12.631          ops/ms
ClientSimple.listUser                        thrpt          7.489          ops/ms
ClientSimple.createUser                       avgt          2.167           ms/op
ClientSimple.existUser                        avgt          2.084           ms/op
ClientSimple.getUser                          avgt          1.908           ms/op
ClientSimple.listUser                         avgt          3.854           ms/op
ClientSimple.createUser                     sample  14047   2.275 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.648           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.995           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.088           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.206           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.910           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.239           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.252           ms/op
ClientSimple.existUser                      sample  15440   2.072 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.389           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.890           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.953           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.313           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.382           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.495           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.513           ms/op
ClientSimple.getUser                        sample  15628   2.062 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.599           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.363           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.620           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.214           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.269           ms/op
ClientSimple.listUser                       sample   8529   3.748 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.980           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.658           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.087           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.713           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.032           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.139           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.139           ms/op

Benchmark result is saved to 1718863538315.json
