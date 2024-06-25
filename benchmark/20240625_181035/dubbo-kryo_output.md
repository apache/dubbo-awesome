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
# Warmup Iteration   1: 1.742 ops/ms
Iteration   1: 7.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.759 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.425 ops/ms
Iteration   1: 13.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.701 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.663 ops/ms
Iteration   1: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.819 ops/ms


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
# Warmup Iteration   1: 4.618 ops/ms
Iteration   1: 8.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.886 ops/ms


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.068 ms/op
Iteration   1: 2.270 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.270 ms/op


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
# Warmup Iteration   1: 3.138 ±(99.9%) 0.044 ms/op
Iteration   1: 1.992 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.992 ms/op


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
# Warmup Iteration   1: 3.418 ±(99.9%) 0.057 ms/op
Iteration   1: 2.245 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.245 ms/op


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.095 ms/op
Iteration   1: 3.453 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.453 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.089 ms/op
Iteration   1: 2.078 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   1.864 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   4.757 ms/op
                 createUser·p0.999:  18.067 ms/op
                 createUser·p0.9999: 19.296 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15629
  mean =      2.078 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 13781 
    [ 2.500,  3.750) = 1489 
    [ 3.750,  5.000) = 226 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      4.757 ms/op
     p(99.9000) =     18.067 ms/op
     p(99.9900) =     19.296 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 2.921 ±(99.9%) 0.059 ms/op
Iteration   1: 2.249 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   2.236 ms/op
                 existUser·p0.90:   2.679 ms/op
                 existUser·p0.95:   2.814 ms/op
                 existUser·p0.99:   3.745 ms/op
                 existUser·p0.999:  13.713 ms/op
                 existUser·p0.9999: 14.273 ms/op
                 existUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14217
  mean =      2.249 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 10679 
    [ 2.500,  3.750) = 3283 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.236 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      3.745 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     14.273 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.227 ±(99.9%) 0.087 ms/op
Iteration   1: 2.079 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.028 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   2.744 ms/op
                 getUser·p0.99:   3.388 ms/op
                 getUser·p0.999:  13.406 ms/op
                 getUser·p0.9999: 14.432 ms/op
                 getUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15379
  mean =      2.079 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 303 
    [ 1.250,  2.500) = 13092 
    [ 2.500,  3.750) = 1880 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.388 ms/op
     p(99.9000) =     13.406 ms/op
     p(99.9900) =     14.432 ms/op
     p(99.9990) =     14.467 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 4.936 ±(99.9%) 0.302 ms/op
Iteration   1: 3.612 ±(99.9%) 0.076 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.469 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.386 ms/op
                 listUser·p0.999:  36.179 ms/op
                 listUser·p0.9999: 36.504 ms/op
                 listUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8946
  mean =      3.612 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1400 
    [ 2.500,  5.000) = 7112 
    [ 5.000,  7.500) = 354 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.386 ms/op
     p(99.9000) =     36.179 ms/op
     p(99.9900) =     36.504 ms/op
     p(99.9990) =     36.504 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.759          ops/ms
ClientSimple.existUser                       thrpt         13.701          ops/ms
ClientSimple.getUser                         thrpt         12.819          ops/ms
ClientSimple.listUser                        thrpt          8.886          ops/ms
ClientSimple.createUser                       avgt          2.270           ms/op
ClientSimple.existUser                        avgt          1.992           ms/op
ClientSimple.getUser                          avgt          2.245           ms/op
ClientSimple.listUser                         avgt          3.453           ms/op
ClientSimple.createUser                     sample  15629   2.078 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.912           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.864           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.757           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.067           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.296           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.333           ms/op
ClientSimple.existUser                      sample  14217   2.249 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.739           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.679           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.814           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.745           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.713           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.273           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.287           ms/op
ClientSimple.getUser                        sample  15379   2.079 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.702           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.028           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.388           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.406           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.432           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.467           ms/op
ClientSimple.listUser                       sample   8946   3.612 ± 0.076   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.206           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.469           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.386           ms/op
ClientSimple.listUser:listUser·p0.999       sample         36.179           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         36.504           ms/op
ClientSimple.listUser:listUser·p1.00        sample         36.504           ms/op

Benchmark result is saved to 1719338779737.json
