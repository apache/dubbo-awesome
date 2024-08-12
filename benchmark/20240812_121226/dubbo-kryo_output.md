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
# Warmup Iteration   1: 1.556 ops/ms
Iteration   1: 6.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.743 ops/ms


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
# Warmup Iteration   1: 5.893 ops/ms
Iteration   1: 12.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.292 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.134 ops/ms
Iteration   1: 11.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.280 ops/ms


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
# Warmup Iteration   1: 4.745 ops/ms
Iteration   1: 7.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.607 ops/ms


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.070 ms/op
Iteration   1: 2.048 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.048 ms/op


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
# Warmup Iteration   1: 3.247 ±(99.9%) 0.049 ms/op
Iteration   1: 1.959 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.959 ms/op


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
# Warmup Iteration   1: 3.413 ±(99.9%) 0.057 ms/op
Iteration   1: 1.882 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.882 ms/op


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
# Warmup Iteration   1: 4.696 ±(99.9%) 0.092 ms/op
Iteration   1: 3.349 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.349 ms/op


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.115 ms/op
Iteration   1: 2.701 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.458 ms/op
                 createUser·p0.50:   2.327 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.844 ms/op
                 createUser·p0.99:   14.233 ms/op
                 createUser·p0.999:  18.618 ms/op
                 createUser·p0.9999: 20.962 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11829
  mean =      2.701 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6955 
    [ 2.500,  5.000) = 4445 
    [ 5.000,  7.500) = 160 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      2.327 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.844 ms/op
     p(99.0000) =     14.233 ms/op
     p(99.9000) =     18.618 ms/op
     p(99.9900) =     20.962 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 3.139 ±(99.9%) 0.076 ms/op
Iteration   1: 1.757 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   1.626 ms/op
                 existUser·p0.90:   2.058 ms/op
                 existUser·p0.95:   2.281 ms/op
                 existUser·p0.99:   3.459 ms/op
                 existUser·p0.999:  23.502 ms/op
                 existUser·p0.9999: 24.161 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18258
  mean =      1.757 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17733 
    [ 2.500,  5.000) = 428 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.626 ms/op
     p(90.0000) =      2.058 ms/op
     p(95.0000) =      2.281 ms/op
     p(99.0000) =      3.459 ms/op
     p(99.9000) =     23.502 ms/op
     p(99.9900) =     24.161 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 3.249 ±(99.9%) 0.079 ms/op
Iteration   1: 1.954 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   1.845 ms/op
                 getUser·p0.90:   2.413 ms/op
                 getUser·p0.95:   2.609 ms/op
                 getUser·p0.99:   3.057 ms/op
                 getUser·p0.999:  10.331 ms/op
                 getUser·p0.9999: 11.295 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16359
  mean =      1.954 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 15007 
    [ 2.500,  3.750) = 1132 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.057 ms/op
     p(99.9000) =     10.331 ms/op
     p(99.9900) =     11.295 ms/op
     p(99.9990) =     11.305 ms/op
     p(99.9999) =     11.305 ms/op
    p(100.0000) =     11.305 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.126 ms/op
Iteration   1: 3.544 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.604 ms/op
                 listUser·p0.50:   3.396 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   5.510 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9033
  mean =      3.544 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 323 
    [ 2.500,  3.750) = 5482 
    [ 3.750,  5.000) = 2914 
    [ 5.000,  6.250) = 259 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      5.510 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     16.810 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.743          ops/ms
ClientSimple.existUser                       thrpt         12.292          ops/ms
ClientSimple.getUser                         thrpt         11.280          ops/ms
ClientSimple.listUser                        thrpt          7.607          ops/ms
ClientSimple.createUser                       avgt          2.048           ms/op
ClientSimple.existUser                        avgt          1.959           ms/op
ClientSimple.getUser                          avgt          1.882           ms/op
ClientSimple.listUser                         avgt          3.349           ms/op
ClientSimple.createUser                     sample  11829   2.701 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.458           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.327           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.289           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.844           ms/op
ClientSimple.createUser:createUser·p0.99    sample         14.233           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.618           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.962           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.004           ms/op
ClientSimple.existUser                      sample  18258   1.757 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.484           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.626           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.058           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.459           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.502           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.161           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.216           ms/op
ClientSimple.getUser                        sample  16359   1.954 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.490           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.845           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.057           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.331           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.295           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.305           ms/op
ClientSimple.listUser                       sample   9033   3.544 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.604           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.396           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.510           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.187           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.810           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.810           ms/op

Benchmark result is saved to 1723464486930.json
