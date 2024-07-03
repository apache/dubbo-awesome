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
# Warmup Iteration   1: 1.799 ops/ms
Iteration   1: 6.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.905 ops/ms


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
# Warmup Iteration   1: 6.347 ops/ms
Iteration   1: 11.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.818 ops/ms


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
# Warmup Iteration   1: 5.467 ops/ms
Iteration   1: 13.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.401 ops/ms


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
# Warmup Iteration   1: 5.219 ops/ms
Iteration   1: 8.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.639 ops/ms


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.076 ms/op
Iteration   1: 2.341 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.341 ms/op


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
# Warmup Iteration   1: 3.004 ±(99.9%) 0.049 ms/op
Iteration   1: 1.939 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.939 ms/op


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
# Warmup Iteration   1: 3.174 ±(99.9%) 0.052 ms/op
Iteration   1: 2.240 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.240 ms/op


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
# Warmup Iteration   1: 4.381 ±(99.9%) 0.091 ms/op
Iteration   1: 3.076 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.076 ms/op


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
# Warmup Iteration   1: 3.646 ±(99.9%) 0.093 ms/op
Iteration   1: 2.040 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.511 ms/op
                 createUser·p0.50:   1.745 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   8.416 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 17.532 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15676
  mean =      2.040 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 13839 
    [ 2.500,  3.750) = 1205 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      8.416 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     17.532 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 3.104 ±(99.9%) 0.075 ms/op
Iteration   1: 1.841 ±(99.9%) 0.042 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   1.669 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  29.753 ms/op
                 existUser·p0.9999: 31.168 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17358
  mean =      1.841 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16333 
    [ 2.500,  5.000) = 913 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =     29.753 ms/op
     p(99.9900) =     31.168 ms/op
     p(99.9990) =     31.457 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.079 ms/op
Iteration   1: 2.007 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.441 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.560 ms/op
                 getUser·p0.99:   3.342 ms/op
                 getUser·p0.999:  18.973 ms/op
                 getUser·p0.9999: 19.531 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15939
  mean =      2.007 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 14780 
    [ 2.500,  3.750) = 941 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      3.342 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     19.531 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 5.356 ±(99.9%) 0.167 ms/op
Iteration   1: 3.644 ±(99.9%) 0.064 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  28.785 ms/op
                 listUser·p0.9999: 29.721 ms/op
                 listUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8773
  mean =      3.644 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 771 
    [ 2.500,  5.000) = 7680 
    [ 5.000,  7.500) = 160 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     28.785 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.905          ops/ms
ClientSimple.existUser                       thrpt         11.818          ops/ms
ClientSimple.getUser                         thrpt         13.401          ops/ms
ClientSimple.listUser                        thrpt          8.639          ops/ms
ClientSimple.createUser                       avgt          2.341           ms/op
ClientSimple.existUser                        avgt          1.939           ms/op
ClientSimple.getUser                          avgt          2.240           ms/op
ClientSimple.listUser                         avgt          3.076           ms/op
ClientSimple.createUser                     sample  15676   2.040 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.511           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.745           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.416           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.170           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.532           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.662           ms/op
ClientSimple.existUser                      sample  17358   1.841 ± 0.042   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.552           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.669           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.748           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.753           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.168           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.457           ms/op
ClientSimple.getUser                        sample  15939   2.007 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.441           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.342           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.973           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.531           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.628           ms/op
ClientSimple.listUser                       sample   8773   3.644 ± 0.064   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.946           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.535           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.110           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.785           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.721           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.721           ms/op

Benchmark result is saved to 1720008401820.json
