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
# Warmup Iteration   1: 1.559 ops/ms
Iteration   1: 6.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.332 ops/ms


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
# Warmup Iteration   1: 5.330 ops/ms
Iteration   1: 11.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.401 ops/ms


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
# Warmup Iteration   1: 4.577 ops/ms
Iteration   1: 11.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.386 ops/ms


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
# Warmup Iteration   1: 3.964 ops/ms
Iteration   1: 8.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.092 ops/ms


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
# Warmup Iteration   1: 4.270 ±(99.9%) 0.073 ms/op
Iteration   1: 2.442 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.442 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.060 ms/op
Iteration   1: 2.182 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.182 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.052 ms/op
Iteration   1: 1.960 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.960 ms/op


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
# Warmup Iteration   1: 5.175 ±(99.9%) 0.150 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.171 ms/op


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.086 ms/op
Iteration   1: 2.030 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   1.845 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.703 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 21.146 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16292
  mean =      2.030 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14677 
    [ 2.500,  5.000) = 1479 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     21.146 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 2.880 ±(99.9%) 0.069 ms/op
Iteration   1: 1.996 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   1.913 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.671 ms/op
                 existUser·p0.99:   3.960 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 12.596 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16001
  mean =      1.996 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 197 
    [ 1.250,  2.500) = 14479 
    [ 2.500,  3.750) = 1151 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.960 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     12.596 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.093 ms/op
Iteration   1: 2.328 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.446 ms/op
                 getUser·p0.50:   2.195 ms/op
                 getUser·p0.90:   2.879 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  18.083 ms/op
                 getUser·p0.9999: 19.631 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13716
  mean =      2.328 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9526 
    [ 2.500,  5.000) = 3988 
    [ 5.000,  7.500) = 154 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     18.083 ms/op
     p(99.9900) =     19.631 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.289 ±(99.9%) 0.118 ms/op
Iteration   1: 3.185 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   4.784 ms/op
                 listUser·p0.999:  32.899 ms/op
                 listUser·p0.9999: 32.965 ms/op
                 listUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10036
  mean =      3.185 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 872 
    [ 2.500,  5.000) = 9082 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =     32.899 ms/op
     p(99.9900) =     32.965 ms/op
     p(99.9990) =     32.965 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.332          ops/ms
ClientSimple.existUser                       thrpt         11.401          ops/ms
ClientSimple.getUser                         thrpt         11.386          ops/ms
ClientSimple.listUser                        thrpt          8.092          ops/ms
ClientSimple.createUser                       avgt          2.442           ms/op
ClientSimple.existUser                        avgt          2.182           ms/op
ClientSimple.getUser                          avgt          1.960           ms/op
ClientSimple.listUser                         avgt          3.171           ms/op
ClientSimple.createUser                     sample  16292   2.030 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.647           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.845           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.194           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.283           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.146           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.332           ms/op
ClientSimple.existUser                      sample  16001   1.996 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.529           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.913           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.960           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.452           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.596           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.616           ms/op
ClientSimple.getUser                        sample  13716   2.328 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.446           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.195           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.105           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.612           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.083           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.631           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.021           ms/op
ClientSimple.listUser                       sample  10036   3.185 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.317           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.908           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.928           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.899           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.965           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.965           ms/op

Benchmark result is saved to 1724242007812.json
