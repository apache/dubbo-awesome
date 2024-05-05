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
# Warmup Iteration   1: 1.763 ops/ms
Iteration   1: 6.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.626 ops/ms


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
# Warmup Iteration   1: 6.080 ops/ms
Iteration   1: 12.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.163 ops/ms


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
# Warmup Iteration   1: 4.651 ops/ms
Iteration   1: 11.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.341 ops/ms


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
# Warmup Iteration   1: 3.196 ops/ms
Iteration   1: 7.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.876 ops/ms


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.093 ms/op
Iteration   1: 2.140 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.140 ms/op


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
# Warmup Iteration   1: 3.299 ±(99.9%) 0.052 ms/op
Iteration   1: 2.124 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.124 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.057 ms/op
Iteration   1: 2.168 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.168 ms/op


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.114 ms/op
Iteration   1: 3.103 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.103 ms/op


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
# Warmup Iteration   1: 3.413 ±(99.9%) 0.086 ms/op
Iteration   1: 2.528 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   2.396 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 20.245 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12635
  mean =      2.528 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7282 
    [ 2.500,  5.000) = 5158 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.396 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     20.245 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.826 ±(99.9%) 0.065 ms/op
Iteration   1: 1.714 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   1.604 ms/op
                 existUser·p0.90:   2.097 ms/op
                 existUser·p0.95:   2.269 ms/op
                 existUser·p0.99:   3.065 ms/op
                 existUser·p0.999:  23.200 ms/op
                 existUser·p0.9999: 24.384 ms/op
                 existUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18720
  mean =      1.714 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18260 
    [ 2.500,  5.000) = 363 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      1.604 ms/op
     p(90.0000) =      2.097 ms/op
     p(95.0000) =      2.269 ms/op
     p(99.0000) =      3.065 ms/op
     p(99.9000) =     23.200 ms/op
     p(99.9900) =     24.384 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.086 ms/op
Iteration   1: 1.993 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   1.905 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.699 ms/op
                 getUser·p0.99:   3.775 ms/op
                 getUser·p0.999:  13.499 ms/op
                 getUser·p0.9999: 14.253 ms/op
                 getUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16083
  mean =      1.993 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 412 
    [ 1.250,  2.500) = 14171 
    [ 2.500,  3.750) = 1338 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.775 ms/op
     p(99.9000) =     13.499 ms/op
     p(99.9900) =     14.253 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 5.032 ±(99.9%) 0.151 ms/op
Iteration   1: 3.629 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.326 ms/op
                 listUser·p0.999:  16.498 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8839
  mean =      3.629 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 535 
    [ 2.500,  3.750) = 4848 
    [ 3.750,  5.000) = 3183 
    [ 5.000,  6.250) = 177 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.326 ms/op
     p(99.9000) =     16.498 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.626          ops/ms
ClientSimple.existUser                       thrpt         12.163          ops/ms
ClientSimple.getUser                         thrpt         11.341          ops/ms
ClientSimple.listUser                        thrpt          7.876          ops/ms
ClientSimple.createUser                       avgt          2.140           ms/op
ClientSimple.existUser                        avgt          2.124           ms/op
ClientSimple.getUser                          avgt          2.168           ms/op
ClientSimple.listUser                         avgt          3.103           ms/op
ClientSimple.createUser                     sample  12635   2.528 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.751           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.396           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.088           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.269           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.824           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.957           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.245           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.513           ms/op
ClientSimple.existUser                      sample  18720   1.714 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.478           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.604           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.065           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.200           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.384           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.412           ms/op
ClientSimple.getUser                        sample  16083   1.993 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.645           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.905           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.775           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.499           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.253           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.041           ms/op
ClientSimple.listUser                       sample   8839   3.629 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.006           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.326           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.498           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.760           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.760           ms/op

Benchmark result is saved to 1714868180706.json
