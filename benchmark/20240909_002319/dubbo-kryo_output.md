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
# Warmup Iteration   1: 1.851 ops/ms
Iteration   1: 8.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.008 ops/ms


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
# Warmup Iteration   1: 6.129 ops/ms
Iteration   1: 13.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.395 ops/ms


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
# Warmup Iteration   1: 5.981 ops/ms
Iteration   1: 11.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.664 ops/ms


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
# Warmup Iteration   1: 6.559 ops/ms
Iteration   1: 9.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.567 ops/ms


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.067 ms/op
Iteration   1: 2.040 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.040 ms/op


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
# Warmup Iteration   1: 3.157 ±(99.9%) 0.049 ms/op
Iteration   1: 1.771 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.771 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.059 ms/op
Iteration   1: 2.299 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.299 ms/op


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.086 ms/op
Iteration   1: 3.727 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.727 ms/op


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
# Warmup Iteration   1: 3.318 ±(99.9%) 0.076 ms/op
Iteration   1: 2.213 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.395 ms/op
                 createUser·p0.50:   2.095 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   2.765 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  22.267 ms/op
                 createUser·p0.9999: 23.229 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14450
  mean =      2.213 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12094 
    [ 2.500,  5.000) = 2176 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.395 ms/op
     p(50.0000) =      2.095 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     22.267 ms/op
     p(99.9900) =     23.229 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 2.903 ±(99.9%) 0.067 ms/op
Iteration   1: 1.769 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   1.642 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   2.925 ms/op
                 existUser·p0.999:  14.007 ms/op
                 existUser·p0.9999: 14.201 ms/op
                 existUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18068
  mean =      1.769 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 950 
    [ 1.250,  2.500) = 15870 
    [ 2.500,  3.750) = 1182 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      2.925 ms/op
     p(99.9000) =     14.007 ms/op
     p(99.9900) =     14.201 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.161 ±(99.9%) 0.075 ms/op
Iteration   1: 2.228 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.608 ms/op
                 getUser·p0.50:   2.081 ms/op
                 getUser·p0.90:   2.650 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   7.217 ms/op
                 getUser·p0.999:  23.075 ms/op
                 getUser·p0.9999: 23.612 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14760
  mean =      2.228 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12428 
    [ 2.500,  5.000) = 2102 
    [ 5.000,  7.500) = 101 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     23.075 ms/op
     p(99.9900) =     23.612 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.129 ms/op
Iteration   1: 3.021 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   2.814 ms/op
                 listUser·p0.90:   3.841 ms/op
                 listUser·p0.95:   4.100 ms/op
                 listUser·p0.99:   5.278 ms/op
                 listUser·p0.999:  8.280 ms/op
                 listUser·p0.9999: 8.962 ms/op
                 listUser·p1.00:   8.962 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10571
  mean =      3.021 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 207 
    [2.000, 2.500) = 2425 
    [2.500, 3.000) = 3353 
    [3.000, 3.500) = 1798 
    [3.500, 4.000) = 2094 
    [4.000, 4.500) = 453 
    [4.500, 5.000) = 102 
    [5.000, 5.500) = 40 
    [5.500, 6.000) = 38 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 26 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.841 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.278 ms/op
     p(99.9000) =      8.280 ms/op
     p(99.9900) =      8.962 ms/op
     p(99.9990) =      8.962 ms/op
     p(99.9999) =      8.962 ms/op
    p(100.0000) =      8.962 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.008          ops/ms
ClientSimple.existUser                       thrpt         13.395          ops/ms
ClientSimple.getUser                         thrpt         11.664          ops/ms
ClientSimple.listUser                        thrpt          9.567          ops/ms
ClientSimple.createUser                       avgt          2.040           ms/op
ClientSimple.existUser                        avgt          1.771           ms/op
ClientSimple.getUser                          avgt          2.299           ms/op
ClientSimple.listUser                         avgt          3.727           ms/op
ClientSimple.createUser                     sample  14450   2.213 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.395           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.095           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.553           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.267           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.229           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.462           ms/op
ClientSimple.existUser                      sample  18068   1.769 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.659           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.642           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.925           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.007           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.201           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.320           ms/op
ClientSimple.getUser                        sample  14760   2.228 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.608           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.081           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          7.217           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.075           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.612           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.658           ms/op
ClientSimple.listUser                       sample  10571   3.021 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.219           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.814           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.841           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.278           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.280           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.962           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.962           ms/op

Benchmark result is saved to 1725841130882.json
