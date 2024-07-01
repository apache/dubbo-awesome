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
# Warmup Iteration   1: 1.917 ops/ms
Iteration   1: 6.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.674 ops/ms


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
# Warmup Iteration   1: 7.063 ops/ms
Iteration   1: 13.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.491 ops/ms


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
# Warmup Iteration   1: 5.028 ops/ms
Iteration   1: 12.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.608 ops/ms


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
# Warmup Iteration   1: 4.739 ops/ms
Iteration   1: 8.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.185 ops/ms


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
# Warmup Iteration   1: 3.790 ±(99.9%) 0.072 ms/op
Iteration   1: 2.365 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.365 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.057 ms/op
Iteration   1: 1.732 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.732 ms/op


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
# Warmup Iteration   1: 3.335 ±(99.9%) 0.079 ms/op
Iteration   1: 1.930 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.930 ms/op


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.083 ms/op
Iteration   1: 3.316 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.316 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.133 ms/op
Iteration   1: 2.513 ±(99.9%) 0.146 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.046 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   3.043 ms/op
                 createUser·p0.99:   13.042 ms/op
                 createUser·p0.999:  106.463 ms/op
                 createUser·p0.9999: 111.700 ms/op
                 createUser·p1.00:   112.853 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12749
  mean =      2.513 ±(99.9%) 0.146 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 12621 
    [ 12.500,  25.000) = 88 
    [ 25.000,  37.500) = 5 
    [ 37.500,  50.000) = 3 
    [ 50.000,  62.500) = 1 
    [ 62.500,  75.000) = 4 
    [ 75.000,  87.500) = 4 
    [ 87.500, 100.000) = 6 
    [100.000, 112.500) = 16 
    [112.500, 125.000) = 1 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =     13.042 ms/op
     p(99.9000) =    106.463 ms/op
     p(99.9900) =    111.700 ms/op
     p(99.9990) =    112.853 ms/op
     p(99.9999) =    112.853 ms/op
    p(100.0000) =    112.853 ms/op


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
# Warmup Iteration   1: 3.434 ±(99.9%) 0.119 ms/op
Iteration   1: 1.895 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   1.898 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.192 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 12.484 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16875
  mean =      1.895 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1837 
    [ 1.250,  2.500) = 13811 
    [ 2.500,  3.750) = 1158 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.192 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     12.484 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.080 ms/op
Iteration   1: 1.955 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.446 ms/op
                 getUser·p0.50:   1.845 ms/op
                 getUser·p0.90:   2.470 ms/op
                 getUser·p0.95:   2.688 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  11.939 ms/op
                 getUser·p0.9999: 12.616 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16575
  mean =      1.955 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 418 
    [ 1.250,  2.500) = 14711 
    [ 2.500,  3.750) = 1240 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.688 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =     11.939 ms/op
     p(99.9900) =     12.616 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.151 ms/op
Iteration   1: 3.133 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.030 ms/op
                 listUser·p0.999:  6.742 ms/op
                 listUser·p0.9999: 7.336 ms/op
                 listUser·p1.00:   7.340 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10194
  mean =      3.133 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 20 
    [1.500, 2.000) = 213 
    [2.000, 2.500) = 1838 
    [2.500, 3.000) = 3251 
    [3.000, 3.500) = 1663 
    [3.500, 4.000) = 1810 
    [4.000, 4.500) = 988 
    [4.500, 5.000) = 306 
    [5.000, 5.500) = 41 
    [5.500, 6.000) = 14 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 27 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =      6.742 ms/op
     p(99.9900) =      7.336 ms/op
     p(99.9990) =      7.340 ms/op
     p(99.9999) =      7.340 ms/op
    p(100.0000) =      7.340 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.674          ops/ms
ClientSimple.existUser                       thrpt          13.491          ops/ms
ClientSimple.getUser                         thrpt          12.608          ops/ms
ClientSimple.listUser                        thrpt           8.185          ops/ms
ClientSimple.createUser                       avgt           2.365           ms/op
ClientSimple.existUser                        avgt           1.732           ms/op
ClientSimple.getUser                          avgt           1.930           ms/op
ClientSimple.listUser                         avgt           3.316           ms/op
ClientSimple.createUser                     sample  12749    2.513 ± 0.146   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.922           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.046           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.043           ms/op
ClientSimple.createUser:createUser·p0.99    sample          13.042           ms/op
ClientSimple.createUser:createUser·p0.999   sample         106.463           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         111.700           ms/op
ClientSimple.createUser:createUser·p1.00    sample         112.853           ms/op
ClientSimple.existUser                      sample  16875    1.895 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.462           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.898           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.192           ms/op
ClientSimple.existUser:existUser·p0.999     sample          12.370           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          12.484           ms/op
ClientSimple.existUser:existUser·p1.00      sample          12.517           ms/op
ClientSimple.getUser                        sample  16575    1.955 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.446           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.845           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.470           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.688           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.895           ms/op
ClientSimple.getUser:getUser·p0.999         sample          11.939           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          12.616           ms/op
ClientSimple.getUser:getUser·p1.00          sample          12.616           ms/op
ClientSimple.listUser                       sample  10194    3.133 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.126           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.933           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.030           ms/op
ClientSimple.listUser:listUser·p0.999       sample           6.742           ms/op
ClientSimple.listUser:listUser·p0.9999      sample           7.336           ms/op
ClientSimple.listUser:listUser·p1.00        sample           7.340           ms/op

Benchmark result is saved to 1719835634801.json
