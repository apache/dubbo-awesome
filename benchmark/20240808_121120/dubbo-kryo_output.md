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
# Warmup Iteration   1: 1.433 ops/ms
Iteration   1: 6.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.350 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ops/ms
Iteration   1: 11.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.213 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.513 ops/ms
Iteration   1: 12.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.392 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.300 ops/ms
Iteration   1: 8.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.437 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.084 ms/op
Iteration   1: 2.484 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.484 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.390 ±(99.9%) 0.060 ms/op
Iteration   1: 2.059 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.059 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.426 ±(99.9%) 0.085 ms/op
Iteration   1: 2.010 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.010 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.664 ±(99.9%) 0.088 ms/op
Iteration   1: 3.528 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.528 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.107 ms/op
Iteration   1: 2.285 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   2.015 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   8.891 ms/op
                 createUser·p0.999:  24.021 ms/op
                 createUser·p0.9999: 28.757 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13932
  mean =      2.285 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11427 
    [ 2.500,  5.000) = 2210 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      8.891 ms/op
     p(99.9000) =     24.021 ms/op
     p(99.9900) =     28.757 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.088 ms/op
Iteration   1: 1.910 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.362 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.640 ms/op
                 existUser·p0.95:   2.916 ms/op
                 existUser·p0.99:   4.008 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 14.920 ms/op
                 existUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16653
  mean =      1.910 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 665 
    [ 1.250,  2.500) = 13833 
    [ 2.500,  3.750) = 1969 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.640 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      4.008 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     14.920 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.337 ±(99.9%) 0.077 ms/op
Iteration   1: 2.180 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.422 ms/op
                 getUser·p0.50:   2.042 ms/op
                 getUser·p0.90:   2.671 ms/op
                 getUser·p0.95:   2.966 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  14.723 ms/op
                 getUser·p0.9999: 19.048 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14701
  mean =      2.180 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 12167 
    [ 2.500,  3.750) = 2118 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     14.723 ms/op
     p(99.9900) =     19.048 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.145 ms/op
Iteration   1: 3.657 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.699 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8743
  mean =      3.657 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 522 
    [ 2.500,  3.750) = 4390 
    [ 3.750,  5.000) = 3375 
    [ 5.000,  6.250) = 402 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.699 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.350          ops/ms
ClientSimple.existUser                       thrpt         11.213          ops/ms
ClientSimple.getUser                         thrpt         12.392          ops/ms
ClientSimple.listUser                        thrpt          8.437          ops/ms
ClientSimple.createUser                       avgt          2.484           ms/op
ClientSimple.existUser                        avgt          2.059           ms/op
ClientSimple.getUser                          avgt          2.010           ms/op
ClientSimple.listUser                         avgt          3.528           ms/op
ClientSimple.createUser                     sample  13932   2.285 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.555           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.015           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.330           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.891           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.021           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.757           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.770           ms/op
ClientSimple.existUser                      sample  16653   1.910 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.362           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.640           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.916           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.008           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.057           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.920           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.942           ms/op
ClientSimple.getUser                        sample  14701   2.180 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.422           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.042           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.472           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.723           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.048           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.464           ms/op
ClientSimple.listUser                       sample   8743   3.657 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.149           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.547           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.699           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.014           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.661           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.924           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.055           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.055           ms/op

Benchmark result is saved to 1723118815841.json
