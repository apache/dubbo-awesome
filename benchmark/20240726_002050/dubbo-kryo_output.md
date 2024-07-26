# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.093 ops/ms
Iteration   1: 7.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.150 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.399 ops/ms
Iteration   1: 13.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.865 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.149 ops/ms
Iteration   1: 13.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.337 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.660 ops/ms
Iteration   1: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.100 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.346 ±(99.9%) 0.128 ms/op
Iteration   1: 2.251 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.251 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.419 ±(99.9%) 0.062 ms/op
Iteration   1: 1.871 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.871 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.214 ±(99.9%) 0.050 ms/op
Iteration   1: 1.929 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.929 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.818 ±(99.9%) 0.071 ms/op
Iteration   1: 3.290 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.290 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.546 ±(99.9%) 0.084 ms/op
Iteration   1: 2.082 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   1.886 ms/op
                 createUser·p0.90:   2.454 ms/op
                 createUser·p0.95:   2.748 ms/op
                 createUser·p0.99:   4.944 ms/op
                 createUser·p0.999:  17.465 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15348
  mean =      2.082 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 13972 
    [ 2.500,  3.750) = 1056 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      4.944 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ±(99.9%) 0.078 ms/op
Iteration   1: 1.763 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   1.663 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   3.330 ms/op
                 existUser·p0.999:  16.876 ms/op
                 existUser·p0.9999: 16.980 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18135
  mean =      1.763 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1061 
    [ 1.250,  2.500) = 16176 
    [ 2.500,  3.750) = 755 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 9 
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
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.330 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     16.980 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.221 ±(99.9%) 0.079 ms/op
Iteration   1: 1.919 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   1.794 ms/op
                 getUser·p0.90:   2.331 ms/op
                 getUser·p0.95:   2.535 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  14.849 ms/op
                 getUser·p0.9999: 15.067 ms/op
                 getUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16714
  mean =      1.919 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 15665 
    [ 2.500,  3.750) = 753 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =     14.849 ms/op
     p(99.9900) =     15.067 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.121 ms/op
Iteration   1: 2.967 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   2.798 ms/op
                 listUser·p0.90:   3.641 ms/op
                 listUser·p0.95:   4.104 ms/op
                 listUser·p0.99:   5.311 ms/op
                 listUser·p0.999:  14.045 ms/op
                 listUser·p0.9999: 14.833 ms/op
                 listUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10766
  mean =      2.967 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1625 
    [ 2.500,  3.750) = 8217 
    [ 3.750,  5.000) = 766 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.311 ms/op
     p(99.9000) =     14.045 ms/op
     p(99.9900) =     14.833 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.150          ops/ms
ClientSimple.existUser                       thrpt         13.865          ops/ms
ClientSimple.getUser                         thrpt         13.337          ops/ms
ClientSimple.listUser                        thrpt          8.100          ops/ms
ClientSimple.createUser                       avgt          2.251           ms/op
ClientSimple.existUser                        avgt          1.871           ms/op
ClientSimple.getUser                          avgt          1.929           ms/op
ClientSimple.listUser                         avgt          3.290           ms/op
ClientSimple.createUser                     sample  15348   2.082 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.898           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.886           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.944           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.465           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.973           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.973           ms/op
ClientSimple.existUser                      sample  18135   1.763 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.566           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.663           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.330           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.876           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.980           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.007           ms/op
ClientSimple.getUser                        sample  16714   1.919 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.794           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.794           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.331           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.690           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.849           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.067           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.188           ms/op
ClientSimple.listUser                       sample  10766   2.967 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.290           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.798           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.641           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.104           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.311           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.045           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.833           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.844           ms/op

Benchmark result is saved to 1721952980572.json
