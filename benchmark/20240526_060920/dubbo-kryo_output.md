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
# Warmup Iteration   1: 1.531 ops/ms
Iteration   1: 6.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.874 ops/ms


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
# Warmup Iteration   1: 5.359 ops/ms
Iteration   1: 11.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.713 ops/ms


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
# Warmup Iteration   1: 6.285 ops/ms
Iteration   1: 14.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.730 ops/ms


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
# Warmup Iteration   1: 5.056 ops/ms
Iteration   1: 7.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.926 ops/ms


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.066 ms/op
Iteration   1: 2.188 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.188 ms/op


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.067 ms/op
Iteration   1: 2.083 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.083 ms/op


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
# Warmup Iteration   1: 3.337 ±(99.9%) 0.078 ms/op
Iteration   1: 2.185 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.185 ms/op


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
# Warmup Iteration   1: 4.277 ±(99.9%) 0.081 ms/op
Iteration   1: 3.084 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.084 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.110 ms/op
Iteration   1: 2.278 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.224 ms/op
                 createUser·p0.90:   2.793 ms/op
                 createUser·p0.95:   2.986 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  22.020 ms/op
                 createUser·p0.9999: 23.638 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14031
  mean =      2.278 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10722 
    [ 2.500,  5.000) = 3204 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =     22.020 ms/op
     p(99.9900) =     23.638 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 2.985 ±(99.9%) 0.063 ms/op
Iteration   1: 1.681 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   1.632 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.363 ms/op
                 existUser·p0.99:   2.818 ms/op
                 existUser·p0.999:  13.172 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19032
  mean =      1.681 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2181 
    [ 1.250,  2.500) = 16339 
    [ 2.500,  3.750) = 423 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.363 ms/op
     p(99.0000) =      2.818 ms/op
     p(99.9000) =     13.172 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


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
# Warmup Iteration   1: 3.491 ±(99.9%) 0.098 ms/op
Iteration   1: 2.082 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   1.917 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  26.247 ms/op
                 getUser·p0.9999: 26.313 ms/op
                 getUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15352
  mean =      2.082 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13462 
    [ 2.500,  5.000) = 1771 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     26.247 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.157 ms/op
Iteration   1: 3.207 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.987 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10013
  mean =      3.207 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1530 
    [ 2.500,  3.750) = 6332 
    [ 3.750,  5.000) = 1818 
    [ 5.000,  6.250) = 259 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.987 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.874          ops/ms
ClientSimple.existUser                       thrpt         11.713          ops/ms
ClientSimple.getUser                         thrpt         14.730          ops/ms
ClientSimple.listUser                        thrpt          7.926          ops/ms
ClientSimple.createUser                       avgt          2.188           ms/op
ClientSimple.existUser                        avgt          2.083           ms/op
ClientSimple.getUser                          avgt          2.185           ms/op
ClientSimple.listUser                         avgt          3.084           ms/op
ClientSimple.createUser                     sample  14031   2.278 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.791           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.224           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.629           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.020           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.638           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.757           ms/op
ClientSimple.existUser                      sample  19032   1.681 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.666           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.632           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.363           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.818           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.172           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.500           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.500           ms/op
ClientSimple.getUser                        sample  15352   2.082 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.961           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.917           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.342           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.247           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.313           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.313           ms/op
ClientSimple.listUser                       sample  10013   3.207 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.890           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.904           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.987           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.433           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.252           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.252           ms/op

Benchmark result is saved to 1716703496849.json
