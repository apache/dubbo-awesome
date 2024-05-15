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
# Warmup Iteration   1: 2.016 ops/ms
Iteration   1: 7.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.157 ops/ms


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
# Warmup Iteration   1: 6.513 ops/ms
Iteration   1: 11.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.856 ops/ms


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
# Warmup Iteration   1: 6.038 ops/ms
Iteration   1: 13.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.782 ops/ms


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
# Warmup Iteration   1: 5.987 ops/ms
Iteration   1: 8.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.827 ops/ms


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.063 ms/op
Iteration   1: 2.264 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.264 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.042 ms/op
Iteration   1: 1.953 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.953 ms/op


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
# Warmup Iteration   1: 3.408 ±(99.9%) 0.077 ms/op
Iteration   1: 2.202 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.202 ms/op


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.091 ms/op
Iteration   1: 3.330 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.330 ms/op


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
# Warmup Iteration   1: 3.417 ±(99.9%) 0.091 ms/op
Iteration   1: 2.192 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.046 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   4.681 ms/op
                 createUser·p0.999:  18.294 ms/op
                 createUser·p0.9999: 18.400 ms/op
                 createUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14706
  mean =      2.192 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 12356 
    [ 2.500,  3.750) = 2056 
    [ 3.750,  5.000) = 133 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      4.681 ms/op
     p(99.9000) =     18.294 ms/op
     p(99.9900) =     18.400 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 2.856 ±(99.9%) 0.061 ms/op
Iteration   1: 1.736 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   1.589 ms/op
                 existUser·p0.90:   1.976 ms/op
                 existUser·p0.95:   2.216 ms/op
                 existUser·p0.99:   3.712 ms/op
                 existUser·p0.999:  26.771 ms/op
                 existUser·p0.9999: 27.502 ms/op
                 existUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18533
  mean =      1.736 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18067 
    [ 2.500,  5.000) = 346 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.589 ms/op
     p(90.0000) =      1.976 ms/op
     p(95.0000) =      2.216 ms/op
     p(99.0000) =      3.712 ms/op
     p(99.9000) =     26.771 ms/op
     p(99.9900) =     27.502 ms/op
     p(99.9990) =     27.558 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 3.227 ±(99.9%) 0.089 ms/op
Iteration   1: 1.944 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   0.225 ms/op
                 getUser·p0.50:   1.735 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.556 ms/op
                 getUser·p0.99:   3.839 ms/op
                 getUser·p0.999:  35.521 ms/op
                 getUser·p0.9999: 38.213 ms/op
                 getUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16458
  mean =      1.944 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15393 
    [ 2.500,  5.000) = 912 
    [ 5.000,  7.500) = 28 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.225 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.839 ms/op
     p(99.9000) =     35.521 ms/op
     p(99.9900) =     38.213 ms/op
     p(99.9990) =     39.059 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.126 ms/op
Iteration   1: 3.603 ±(99.9%) 0.064 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   8.285 ms/op
                 listUser·p0.999:  30.680 ms/op
                 listUser·p0.9999: 37.028 ms/op
                 listUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8865
  mean =      3.603 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 920 
    [ 2.500,  5.000) = 7636 
    [ 5.000,  7.500) = 185 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      8.285 ms/op
     p(99.9000) =     30.680 ms/op
     p(99.9900) =     37.028 ms/op
     p(99.9990) =     37.028 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.157          ops/ms
ClientSimple.existUser                       thrpt         11.856          ops/ms
ClientSimple.getUser                         thrpt         13.782          ops/ms
ClientSimple.listUser                        thrpt          8.827          ops/ms
ClientSimple.createUser                       avgt          2.264           ms/op
ClientSimple.existUser                        avgt          1.953           ms/op
ClientSimple.getUser                          avgt          2.202           ms/op
ClientSimple.listUser                         avgt          3.330           ms/op
ClientSimple.createUser                     sample  14706   2.192 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.798           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.046           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.681           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.294           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.400           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.416           ms/op
ClientSimple.existUser                      sample  18533   1.736 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.539           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.589           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.976           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.216           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.712           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.771           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.502           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.558           ms/op
ClientSimple.getUser                        sample  16458   1.944 ± 0.044   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.225           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.735           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.839           ms/op
ClientSimple.getUser:getUser·p0.999         sample         35.521           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         38.213           ms/op
ClientSimple.getUser:getUser·p1.00          sample         39.059           ms/op
ClientSimple.listUser                       sample   8865   3.603 ± 0.064   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.065           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.490           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.166           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.285           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.680           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         37.028           ms/op
ClientSimple.listUser:listUser·p1.00        sample         37.028           ms/op

Benchmark result is saved to 1715732132782.json
