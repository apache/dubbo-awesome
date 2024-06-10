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
# Warmup Iteration   1: 1.983 ops/ms
Iteration   1: 6.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.797 ops/ms


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
# Warmup Iteration   1: 6.137 ops/ms
Iteration   1: 12.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.447 ops/ms


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
# Warmup Iteration   1: 5.254 ops/ms
Iteration   1: 11.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.015 ops/ms


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
# Warmup Iteration   1: 5.345 ops/ms
Iteration   1: 9.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.085 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.899 ±(99.9%) 0.056 ms/op
Iteration   1: 1.844 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.144 ±(99.9%) 0.050 ms/op
Iteration   1: 2.066 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.066 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.073 ms/op
Iteration   1: 1.987 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.987 ms/op


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
# Warmup Iteration   1: 5.697 ±(99.9%) 0.104 ms/op
Iteration   1: 3.417 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.417 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.075 ms/op
Iteration   1: 2.310 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.514 ms/op
                 createUser·p0.50:   2.216 ms/op
                 createUser·p0.90:   2.888 ms/op
                 createUser·p0.95:   3.059 ms/op
                 createUser·p0.99:   6.780 ms/op
                 createUser·p0.999:  19.399 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13841
  mean =      2.310 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10522 
    [ 2.500,  5.000) = 3167 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.059 ms/op
     p(99.0000) =      6.780 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 2.752 ±(99.9%) 0.061 ms/op
Iteration   1: 1.819 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   3.031 ms/op
                 existUser·p0.999:  25.324 ms/op
                 existUser·p0.9999: 25.976 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17591
  mean =      1.819 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16782 
    [ 2.500,  5.000) = 752 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.031 ms/op
     p(99.9000) =     25.324 ms/op
     p(99.9900) =     25.976 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 3.522 ±(99.9%) 0.103 ms/op
Iteration   1: 1.784 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   1.661 ms/op
                 getUser·p0.90:   2.294 ms/op
                 getUser·p0.95:   2.466 ms/op
                 getUser·p0.99:   3.289 ms/op
                 getUser·p0.999:  10.650 ms/op
                 getUser·p0.9999: 10.879 ms/op
                 getUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18136
  mean =      1.784 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 17190 
    [ 2.500,  3.750) = 616 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.289 ms/op
     p(99.9000) =     10.650 ms/op
     p(99.9900) =     10.879 ms/op
     p(99.9990) =     10.879 ms/op
     p(99.9999) =     10.879 ms/op
    p(100.0000) =     10.879 ms/op


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.125 ms/op
Iteration   1: 3.022 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  11.704 ms/op
                 listUser·p0.9999: 11.993 ms/op
                 listUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10644
  mean =      3.022 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 798 
    [ 2.500,  3.750) = 8725 
    [ 3.750,  5.000) = 844 
    [ 5.000,  6.250) = 144 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     11.704 ms/op
     p(99.9900) =     11.993 ms/op
     p(99.9990) =     11.993 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.797          ops/ms
ClientSimple.existUser                       thrpt         12.447          ops/ms
ClientSimple.getUser                         thrpt         11.015          ops/ms
ClientSimple.listUser                        thrpt          9.085          ops/ms
ClientSimple.createUser                       avgt          1.844           ms/op
ClientSimple.existUser                        avgt          2.066           ms/op
ClientSimple.getUser                          avgt          1.987           ms/op
ClientSimple.listUser                         avgt          3.417           ms/op
ClientSimple.createUser                     sample  13841   2.310 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.514           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.216           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.059           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.780           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.399           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.152           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.152           ms/op
ClientSimple.existUser                      sample  17591   1.819 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.519           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.031           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.324           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.976           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.051           ms/op
ClientSimple.getUser                        sample  18136   1.784 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.571           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.661           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.294           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.289           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.650           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.879           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.879           ms/op
ClientSimple.listUser                       sample  10644   3.022 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.767           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.826           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.768           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.357           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.704           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.993           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.993           ms/op

Benchmark result is saved to 1717978600456.json
