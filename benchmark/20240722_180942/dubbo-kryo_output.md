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
# Warmup Iteration   1: 1.846 ops/ms
Iteration   1: 7.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.980 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.468 ops/ms
Iteration   1: 13.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.273 ops/ms


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
# Warmup Iteration   1: 6.007 ops/ms
Iteration   1: 13.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.863 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.373 ops/ms
Iteration   1: 8.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.375 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.113 ±(99.9%) 0.078 ms/op
Iteration   1: 2.198 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.198 ms/op


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
# Warmup Iteration   1: 2.768 ±(99.9%) 0.047 ms/op
Iteration   1: 1.737 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.737 ms/op


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
# Warmup Iteration   1: 3.373 ±(99.9%) 0.049 ms/op
Iteration   1: 2.063 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.063 ms/op


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.087 ms/op
Iteration   1: 3.487 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.487 ms/op


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
# Warmup Iteration   1: 3.530 ±(99.9%) 0.090 ms/op
Iteration   1: 2.093 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   1.780 ms/op
                 createUser·p0.90:   2.896 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   6.711 ms/op
                 createUser·p0.999:  15.132 ms/op
                 createUser·p0.9999: 15.196 ms/op
                 createUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15388
  mean =      2.093 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 11896 
    [ 2.500,  3.750) = 3080 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      6.711 ms/op
     p(99.9000) =     15.132 ms/op
     p(99.9900) =     15.196 ms/op
     p(99.9990) =     15.204 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ±(99.9%) 0.096 ms/op
Iteration   1: 1.888 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.725 ms/op
                 existUser·p0.99:   3.283 ms/op
                 existUser·p0.999:  12.634 ms/op
                 existUser·p0.9999: 12.919 ms/op
                 existUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16951
  mean =      1.888 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 833 
    [ 1.250,  2.500) = 14728 
    [ 2.500,  3.750) = 1302 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.725 ms/op
     p(99.0000) =      3.283 ms/op
     p(99.9000) =     12.634 ms/op
     p(99.9900) =     12.919 ms/op
     p(99.9990) =     12.976 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


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
# Warmup Iteration   1: 3.280 ±(99.9%) 0.090 ms/op
Iteration   1: 1.808 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   1.608 ms/op
                 getUser·p0.90:   2.245 ms/op
                 getUser·p0.95:   2.408 ms/op
                 getUser·p0.99:   3.206 ms/op
                 getUser·p0.999:  32.123 ms/op
                 getUser·p0.9999: 33.013 ms/op
                 getUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17668
  mean =      1.808 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17017 
    [ 2.500,  5.000) = 535 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.608 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      3.206 ms/op
     p(99.9000) =     32.123 ms/op
     p(99.9900) =     33.013 ms/op
     p(99.9990) =     33.063 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.114 ms/op
Iteration   1: 3.241 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  11.518 ms/op
                 listUser·p0.9999: 11.567 ms/op
                 listUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9895
  mean =      3.241 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 345 
    [ 2.500,  3.750) = 7843 
    [ 3.750,  5.000) = 1565 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     11.567 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.980          ops/ms
ClientSimple.existUser                       thrpt         13.273          ops/ms
ClientSimple.getUser                         thrpt         13.863          ops/ms
ClientSimple.listUser                        thrpt          8.375          ops/ms
ClientSimple.createUser                       avgt          2.198           ms/op
ClientSimple.existUser                        avgt          1.737           ms/op
ClientSimple.getUser                          avgt          2.063           ms/op
ClientSimple.listUser                         avgt          3.487           ms/op
ClientSimple.createUser                     sample  15388   2.093 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.686           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.780           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.133           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.711           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.132           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.196           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.204           ms/op
ClientSimple.existUser                      sample  16951   1.888 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.524           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.796           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.725           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.283           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.634           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.919           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.976           ms/op
ClientSimple.getUser                        sample  17668   1.808 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.675           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.608           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.245           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.206           ms/op
ClientSimple.getUser:getUser·p0.999         sample         32.123           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         33.013           ms/op
ClientSimple.getUser:getUser·p1.00          sample         33.063           ms/op
ClientSimple.listUser                       sample   9895   3.241 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.023           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.027           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.899           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.108           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.456           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.518           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.567           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.567           ms/op

Benchmark result is saved to 1721671515654.json
