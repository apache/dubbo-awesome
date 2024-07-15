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
# Warmup Iteration   1: 2.354 ops/ms
Iteration   1: 7.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.777 ops/ms


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
# Warmup Iteration   1: 7.248 ops/ms
Iteration   1: 12.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.505 ops/ms


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
# Warmup Iteration   1: 5.439 ops/ms
Iteration   1: 14.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.004 ops/ms


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
# Warmup Iteration   1: 4.747 ops/ms
Iteration   1: 8.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.653 ops/ms


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.086 ms/op
Iteration   1: 2.130 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.130 ms/op


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
# Warmup Iteration   1: 3.459 ±(99.9%) 0.061 ms/op
Iteration   1: 1.997 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.997 ms/op


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
# Warmup Iteration   1: 3.475 ±(99.9%) 0.068 ms/op
Iteration   1: 2.068 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.068 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.085 ms/op
Iteration   1: 3.929 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.929 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.125 ms/op
Iteration   1: 2.181 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   2.023 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   3.031 ms/op
                 createUser·p0.99:   5.115 ms/op
                 createUser·p0.999:  18.623 ms/op
                 createUser·p0.9999: 19.698 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14658
  mean =      2.181 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 194 
    [ 1.250,  2.500) = 12591 
    [ 2.500,  3.750) = 1469 
    [ 3.750,  5.000) = 247 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      5.115 ms/op
     p(99.9000) =     18.623 ms/op
     p(99.9900) =     19.698 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.006 ±(99.9%) 0.066 ms/op
Iteration   1: 1.953 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.794 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  21.365 ms/op
                 existUser·p0.9999: 21.520 ms/op
                 existUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16370
  mean =      1.953 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14699 
    [ 2.500,  5.000) = 1609 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =     21.365 ms/op
     p(99.9900) =     21.520 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.136 ms/op
Iteration   1: 1.991 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   1.835 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.883 ms/op
                 getUser·p0.99:   3.547 ms/op
                 getUser·p0.999:  12.380 ms/op
                 getUser·p0.9999: 14.382 ms/op
                 getUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16061
  mean =      1.991 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 14254 
    [ 2.500,  3.750) = 1622 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.883 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =     12.380 ms/op
     p(99.9900) =     14.382 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 5.350 ±(99.9%) 0.325 ms/op
Iteration   1: 3.231 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.234 ms/op
                 listUser·p0.999:  19.765 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9910
  mean =      3.231 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1116 
    [ 2.500,  5.000) = 8581 
    [ 5.000,  7.500) = 152 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     19.765 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.777          ops/ms
ClientSimple.existUser                       thrpt         12.505          ops/ms
ClientSimple.getUser                         thrpt         14.004          ops/ms
ClientSimple.listUser                        thrpt          8.653          ops/ms
ClientSimple.createUser                       avgt          2.130           ms/op
ClientSimple.existUser                        avgt          1.997           ms/op
ClientSimple.getUser                          avgt          2.068           ms/op
ClientSimple.listUser                         avgt          3.929           ms/op
ClientSimple.createUser                     sample  14658   2.181 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.771           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.023           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.031           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.115           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.623           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.698           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.759           ms/op
ClientSimple.existUser                      sample  16370   1.953 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.644           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.794           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.482           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.365           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.520           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.561           ms/op
ClientSimple.getUser                        sample  16061   1.991 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.594           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.835           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.883           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.547           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.380           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.382           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.402           ms/op
ClientSimple.listUser                       sample   9910   3.231 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.112           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.916           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.125           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.234           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.765           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.840           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.840           ms/op

Benchmark result is saved to 1721066750803.json
