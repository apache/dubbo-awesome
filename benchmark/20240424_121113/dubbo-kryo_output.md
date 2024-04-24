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
# Warmup Iteration   1: 1.811 ops/ms
Iteration   1: 7.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.206 ops/ms


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
# Warmup Iteration   1: 6.809 ops/ms
Iteration   1: 12.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.966 ops/ms


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
# Warmup Iteration   1: 6.200 ops/ms
Iteration   1: 12.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.822 ops/ms


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
# Warmup Iteration   1: 4.387 ops/ms
Iteration   1: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.045 ops/ms


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.069 ms/op
Iteration   1: 2.174 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.174 ms/op


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
# Warmup Iteration   1: 3.404 ±(99.9%) 0.059 ms/op
Iteration   1: 1.974 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.051 ms/op
Iteration   1: 2.279 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.279 ms/op


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.102 ms/op
Iteration   1: 3.391 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.391 ms/op


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.087 ms/op
Iteration   1: 2.298 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   2.032 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   8.913 ms/op
                 createUser·p0.999:  26.605 ms/op
                 createUser·p0.9999: 27.962 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14066
  mean =      2.298 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11592 
    [ 2.500,  5.000) = 2152 
    [ 5.000,  7.500) = 102 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     26.605 ms/op
     p(99.9900) =     27.962 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 3.023 ±(99.9%) 0.075 ms/op
Iteration   1: 2.029 ±(99.9%) 0.125 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   1.696 ms/op
                 existUser·p0.90:   2.163 ms/op
                 existUser·p0.95:   2.445 ms/op
                 existUser·p0.99:   3.957 ms/op
                 existUser·p0.999:  106.168 ms/op
                 existUser·p0.9999: 107.983 ms/op
                 existUser·p1.00:   108.134 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15757
  mean =      2.029 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 15693 
    [ 12.500,  25.000) = 32 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 32 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.163 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =    106.168 ms/op
     p(99.9900) =    107.983 ms/op
     p(99.9990) =    108.134 ms/op
     p(99.9999) =    108.134 ms/op
    p(100.0000) =    108.134 ms/op


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
# Warmup Iteration   1: 3.660 ±(99.9%) 0.097 ms/op
Iteration   1: 2.093 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.920 ms/op
                 getUser·p0.99:   3.930 ms/op
                 getUser·p0.999:  27.066 ms/op
                 getUser·p0.9999: 27.361 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15324
  mean =      2.093 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13087 
    [ 2.500,  5.000) = 2109 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      3.930 ms/op
     p(99.9000) =     27.066 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.133 ms/op
Iteration   1: 3.812 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.011 ms/op
                 listUser·p1.00:   10.011 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8460
  mean =      3.812 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 27 
    [ 2.000,  3.000) = 865 
    [ 3.000,  4.000) = 4591 
    [ 4.000,  5.000) = 2562 
    [ 5.000,  6.000) = 254 
    [ 6.000,  7.000) = 104 
    [ 7.000,  8.000) = 19 
    [ 8.000,  9.000) = 26 
    [ 9.000, 10.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     10.011 ms/op
     p(99.9990) =     10.011 ms/op
     p(99.9999) =     10.011 ms/op
    p(100.0000) =     10.011 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.206          ops/ms
ClientSimple.existUser                       thrpt          12.966          ops/ms
ClientSimple.getUser                         thrpt          12.822          ops/ms
ClientSimple.listUser                        thrpt           8.045          ops/ms
ClientSimple.createUser                       avgt           2.174           ms/op
ClientSimple.existUser                        avgt           1.974           ms/op
ClientSimple.getUser                          avgt           2.279           ms/op
ClientSimple.listUser                         avgt           3.391           ms/op
ClientSimple.createUser                     sample  14066    2.298 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.706           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.032           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.252           ms/op
ClientSimple.createUser:createUser·p0.99    sample           8.913           ms/op
ClientSimple.createUser:createUser·p0.999   sample          26.605           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          27.962           ms/op
ClientSimple.createUser:createUser·p1.00    sample          28.082           ms/op
ClientSimple.existUser                      sample  15757    2.029 ± 0.125   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.683           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.696           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.163           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.445           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.957           ms/op
ClientSimple.existUser:existUser·p0.999     sample         106.168           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         107.983           ms/op
ClientSimple.existUser:existUser·p1.00      sample         108.134           ms/op
ClientSimple.getUser                        sample  15324    2.093 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.566           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.920           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.930           ms/op
ClientSimple.getUser:getUser·p0.999         sample          27.066           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          27.361           ms/op
ClientSimple.getUser:getUser·p1.00          sample          27.361           ms/op
ClientSimple.listUser                       sample   8460    3.812 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.184           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.768           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.596           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.398           ms/op
ClientSimple.listUser:listUser·p0.999       sample           9.241           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          10.011           ms/op
ClientSimple.listUser:listUser·p1.00        sample          10.011           ms/op

Benchmark result is saved to 1713960419980.json
