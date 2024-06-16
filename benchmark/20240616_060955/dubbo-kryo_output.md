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
# Warmup Iteration   1: 1.759 ops/ms
Iteration   1: 6.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.760 ops/ms


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
# Warmup Iteration   1: 6.112 ops/ms
Iteration   1: 13.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.016 ops/ms


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
# Warmup Iteration   1: 6.490 ops/ms
Iteration   1: 14.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.600 ops/ms


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
# Warmup Iteration   1: 4.330 ops/ms
Iteration   1: 9.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.252 ops/ms


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.075 ms/op
Iteration   1: 2.080 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.080 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.072 ms/op
Iteration   1: 1.856 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.856 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.057 ms/op
Iteration   1: 2.137 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.137 ms/op


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.089 ms/op
Iteration   1: 3.860 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.860 ms/op


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.090 ms/op
Iteration   1: 2.258 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.281 ms/op
                 createUser·p0.50:   1.962 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.974 ms/op
                 createUser·p0.99:   8.728 ms/op
                 createUser·p0.999:  33.287 ms/op
                 createUser·p0.9999: 36.597 ms/op
                 createUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14155
  mean =      2.258 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12409 
    [ 2.500,  5.000) = 1484 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      1.962 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =      8.728 ms/op
     p(99.9000) =     33.287 ms/op
     p(99.9900) =     36.597 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 2.893 ±(99.9%) 0.082 ms/op
Iteration   1: 1.976 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   1.849 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.552 ms/op
                 existUser·p0.99:   3.273 ms/op
                 existUser·p0.999:  11.089 ms/op
                 existUser·p0.9999: 11.896 ms/op
                 existUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16179
  mean =      1.976 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 181 
    [ 1.250,  2.500) = 14956 
    [ 2.500,  3.750) = 938 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.552 ms/op
     p(99.0000) =      3.273 ms/op
     p(99.9000) =     11.089 ms/op
     p(99.9900) =     11.896 ms/op
     p(99.9990) =     11.977 ms/op
     p(99.9999) =     11.977 ms/op
    p(100.0000) =     11.977 ms/op


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
# Warmup Iteration   1: 3.500 ±(99.9%) 0.117 ms/op
Iteration   1: 2.132 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.266 ms/op
                 getUser·p0.50:   2.003 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.904 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  12.894 ms/op
                 getUser·p0.9999: 13.009 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15008
  mean =      2.132 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 195 
    [ 1.250,  2.500) = 12092 
    [ 2.500,  3.750) = 2467 
    [ 3.750,  5.000) = 127 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      2.003 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.114 ms/op
Iteration   1: 2.942 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   2.724 ms/op
                 listUser·p0.90:   3.844 ms/op
                 listUser·p0.95:   4.059 ms/op
                 listUser·p0.99:   4.940 ms/op
                 listUser·p0.999:  26.665 ms/op
                 listUser·p0.9999: 27.910 ms/op
                 listUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10874
  mean =      2.942 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2849 
    [ 2.500,  5.000) = 7933 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      2.724 ms/op
     p(90.0000) =      3.844 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =     26.665 ms/op
     p(99.9900) =     27.910 ms/op
     p(99.9990) =     27.918 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.760          ops/ms
ClientSimple.existUser                       thrpt         13.016          ops/ms
ClientSimple.getUser                         thrpt         14.600          ops/ms
ClientSimple.listUser                        thrpt          9.252          ops/ms
ClientSimple.createUser                       avgt          2.080           ms/op
ClientSimple.existUser                        avgt          1.856           ms/op
ClientSimple.getUser                          avgt          2.137           ms/op
ClientSimple.listUser                         avgt          3.860           ms/op
ClientSimple.createUser                     sample  14155   2.258 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.281           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.962           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.974           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.728           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.287           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.597           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.897           ms/op
ClientSimple.existUser                      sample  16179   1.976 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.559           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.849           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.552           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.273           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.089           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.896           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.977           ms/op
ClientSimple.getUser                        sample  15008   2.132 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.266           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.003           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.678           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.894           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.009           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.009           ms/op
ClientSimple.listUser                       sample  10874   2.942 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.102           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.724           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.844           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.059           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.665           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.910           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.918           ms/op

Benchmark result is saved to 1718517927938.json
