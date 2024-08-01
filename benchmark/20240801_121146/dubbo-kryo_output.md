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
# Warmup Iteration   1: 1.734 ops/ms
Iteration   1: 6.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.981 ops/ms


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
# Warmup Iteration   1: 5.520 ops/ms
Iteration   1: 11.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.726 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.534 ops/ms
Iteration   1: 12.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.207 ops/ms


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
# Warmup Iteration   1: 4.117 ops/ms
Iteration   1: 8.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.346 ops/ms


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.076 ms/op
Iteration   1: 2.157 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.157 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.209 ±(99.9%) 0.068 ms/op
Iteration   1: 1.996 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.996 ms/op


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.126 ms/op
Iteration   1: 1.861 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.861 ms/op


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
# Warmup Iteration   1: 4.308 ±(99.9%) 0.095 ms/op
Iteration   1: 3.801 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.801 ms/op


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.093 ms/op
Iteration   1: 2.182 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   2.044 ms/op
                 createUser·p0.90:   2.814 ms/op
                 createUser·p0.95:   3.027 ms/op
                 createUser·p0.99:   5.060 ms/op
                 createUser·p0.999:  15.827 ms/op
                 createUser·p0.9999: 17.024 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14632
  mean =      2.182 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 11509 
    [ 2.500,  3.750) = 2845 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.044 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      5.060 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     17.024 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.156 ±(99.9%) 0.073 ms/op
Iteration   1: 2.116 ±(99.9%) 0.108 ms/op
                 existUser·p0.00:   0.393 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  87.687 ms/op
                 existUser·p0.9999: 89.952 ms/op
                 existUser·p1.00:   90.964 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15145
  mean =      2.116 ±(99.9%) 0.108 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 15047 
    [ 10.000,  20.000) = 66 
    [ 20.000,  30.000) = 0 
    [ 30.000,  40.000) = 0 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 0 
    [ 60.000,  70.000) = 0 
    [ 70.000,  80.000) = 0 
    [ 80.000,  90.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     87.687 ms/op
     p(99.9900) =     89.952 ms/op
     p(99.9990) =     90.964 ms/op
     p(99.9999) =     90.964 ms/op
    p(100.0000) =     90.964 ms/op


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.096 ms/op
Iteration   1: 2.206 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.064 ms/op
                 getUser·p0.90:   2.793 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  14.651 ms/op
                 getUser·p0.9999: 19.884 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14514
  mean =      2.206 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11442 
    [ 2.500,  5.000) = 2987 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     14.651 ms/op
     p(99.9900) =     19.884 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 4.732 ±(99.9%) 0.158 ms/op
Iteration   1: 3.225 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.730 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 15.352 ms/op
                 listUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9911
  mean =      3.225 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1567 
    [ 2.500,  3.750) = 6314 
    [ 3.750,  5.000) = 1639 
    [ 5.000,  6.250) = 258 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.730 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     15.352 ms/op
     p(99.9990) =     15.352 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.981          ops/ms
ClientSimple.existUser                       thrpt         11.726          ops/ms
ClientSimple.getUser                         thrpt         12.207          ops/ms
ClientSimple.listUser                        thrpt          8.346          ops/ms
ClientSimple.createUser                       avgt          2.157           ms/op
ClientSimple.existUser                        avgt          1.996           ms/op
ClientSimple.getUser                          avgt          1.861           ms/op
ClientSimple.listUser                         avgt          3.801           ms/op
ClientSimple.createUser                     sample  14632   2.182 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.522           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.044           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.027           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.060           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.827           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.024           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.039           ms/op
ClientSimple.existUser                      sample  15145   2.116 ± 0.108   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.393           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.806           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.087           ms/op
ClientSimple.existUser:existUser·p0.999     sample         87.687           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         89.952           ms/op
ClientSimple.existUser:existUser·p1.00      sample         90.964           ms/op
ClientSimple.getUser                        sample  14514   2.206 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.748           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.064           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.228           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.276           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.651           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.884           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.742           ms/op
ClientSimple.listUser                       sample   9911   3.225 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.964           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.929           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.730           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.390           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.582           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.352           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.352           ms/op

Benchmark result is saved to 1722514029153.json
