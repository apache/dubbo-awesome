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
# Warmup Iteration   1: 1.129 ops/ms
Iteration   1: 5.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.856 ops/ms


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
# Warmup Iteration   1: 5.944 ops/ms
Iteration   1: 12.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.284 ops/ms


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
# Warmup Iteration   1: 4.759 ops/ms
Iteration   1: 12.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.112 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.795 ops/ms
Iteration   1: 9.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.238 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.859 ±(99.9%) 0.076 ms/op
Iteration   1: 2.407 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.407 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.053 ms/op
Iteration   1: 1.715 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.715 ms/op


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
# Warmup Iteration   1: 3.475 ±(99.9%) 0.067 ms/op
Iteration   1: 1.981 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.981 ms/op


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.094 ms/op
Iteration   1: 3.691 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.691 ms/op


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
# Warmup Iteration   1: 3.488 ±(99.9%) 0.096 ms/op
Iteration   1: 1.953 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   1.827 ms/op
                 createUser·p0.90:   2.367 ms/op
                 createUser·p0.95:   2.523 ms/op
                 createUser·p0.99:   3.913 ms/op
                 createUser·p0.999:  21.549 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16382
  mean =      1.953 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15422 
    [ 2.500,  5.000) = 844 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.913 ms/op
     p(99.9000) =     21.549 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 2.937 ±(99.9%) 0.067 ms/op
Iteration   1: 2.083 ±(99.9%) 0.130 ms/op
                 existUser·p0.00:   0.420 ms/op
                 existUser·p0.50:   1.710 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.643 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  103.814 ms/op
                 existUser·p0.9999: 109.969 ms/op
                 existUser·p1.00:   109.969 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15495
  mean =      2.083 ±(99.9%) 0.130 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 15416 
    [ 12.500,  25.000) = 15 
    [ 25.000,  37.500) = 32 
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
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.643 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =    103.814 ms/op
     p(99.9900) =    109.969 ms/op
     p(99.9990) =    109.969 ms/op
     p(99.9999) =    109.969 ms/op
    p(100.0000) =    109.969 ms/op


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
# Warmup Iteration   1: 3.477 ±(99.9%) 0.106 ms/op
Iteration   1: 2.343 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.426 ms/op
                 getUser·p0.50:   2.224 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.156 ms/op
                 getUser·p0.999:  17.275 ms/op
                 getUser·p0.9999: 17.465 ms/op
                 getUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13816
  mean =      2.343 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 306 
    [ 1.250,  2.500) = 8753 
    [ 2.500,  3.750) = 4555 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.156 ms/op
     p(99.9000) =     17.275 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.135 ms/op
Iteration   1: 3.508 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   3.396 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   5.708 ms/op
                 listUser·p0.999:  24.150 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9127
  mean =      3.508 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1275 
    [ 2.500,  5.000) = 7561 
    [ 5.000,  7.500) = 251 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      5.708 ms/op
     p(99.9000) =     24.150 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           5.856          ops/ms
ClientSimple.existUser                       thrpt          12.284          ops/ms
ClientSimple.getUser                         thrpt          12.112          ops/ms
ClientSimple.listUser                        thrpt           9.238          ops/ms
ClientSimple.createUser                       avgt           2.407           ms/op
ClientSimple.existUser                        avgt           1.715           ms/op
ClientSimple.getUser                          avgt           1.981           ms/op
ClientSimple.listUser                         avgt           3.691           ms/op
ClientSimple.createUser                     sample  16382    1.953 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.568           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.827           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.367           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.523           ms/op
ClientSimple.createUser:createUser·p0.99    sample           3.913           ms/op
ClientSimple.createUser:createUser·p0.999   sample          21.549           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          22.184           ms/op
ClientSimple.createUser:createUser·p1.00    sample          22.184           ms/op
ClientSimple.existUser                      sample  15495    2.083 ± 0.130   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.420           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.710           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.643           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.358           ms/op
ClientSimple.existUser:existUser·p0.999     sample         103.814           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         109.969           ms/op
ClientSimple.existUser:existUser·p1.00      sample         109.969           ms/op
ClientSimple.getUser                        sample  13816    2.343 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.426           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.224           ms/op
ClientSimple.getUser:getUser·p0.90          sample           3.019           ms/op
ClientSimple.getUser:getUser·p0.95          sample           3.219           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.156           ms/op
ClientSimple.getUser:getUser·p0.999         sample          17.275           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          17.465           ms/op
ClientSimple.getUser:getUser·p1.00          sample          17.465           ms/op
ClientSimple.listUser                       sample   9127    3.508 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.030           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.396           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.579           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.708           ms/op
ClientSimple.listUser:listUser·p0.999       sample          24.150           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          24.248           ms/op
ClientSimple.listUser:listUser·p1.00        sample          24.248           ms/op

Benchmark result is saved to 1716962742327.json
