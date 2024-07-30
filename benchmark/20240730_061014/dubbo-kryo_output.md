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
# Warmup Iteration   1: 1.826 ops/ms
Iteration   1: 6.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.639 ops/ms


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
# Warmup Iteration   1: 6.288 ops/ms
Iteration   1: 12.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.100 ops/ms


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
# Warmup Iteration   1: 6.513 ops/ms
Iteration   1: 12.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.696 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ops/ms
Iteration   1: 9.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.433 ops/ms


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.071 ms/op
Iteration   1: 2.444 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.444 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.050 ms/op
Iteration   1: 1.848 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.848 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.048 ms/op
Iteration   1: 1.963 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.963 ms/op


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.084 ms/op
Iteration   1: 3.250 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.250 ms/op


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
# Warmup Iteration   1: 3.948 ±(99.9%) 0.093 ms/op
Iteration   1: 2.200 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   2.083 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.847 ms/op
                 createUser·p0.99:   5.511 ms/op
                 createUser·p0.999:  14.876 ms/op
                 createUser·p0.9999: 16.430 ms/op
                 createUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14522
  mean =      2.200 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 12589 
    [ 2.500,  3.750) = 1593 
    [ 3.750,  5.000) = 147 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      5.511 ms/op
     p(99.9000) =     14.876 ms/op
     p(99.9900) =     16.430 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 2.997 ±(99.9%) 0.060 ms/op
Iteration   1: 1.757 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   1.677 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.249 ms/op
                 existUser·p0.99:   3.064 ms/op
                 existUser·p0.999:  10.335 ms/op
                 existUser·p0.9999: 10.622 ms/op
                 existUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18209
  mean =      1.757 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 218 
    [ 1.250,  2.500) = 17573 
    [ 2.500,  3.750) = 288 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.677 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.249 ms/op
     p(99.0000) =      3.064 ms/op
     p(99.9000) =     10.335 ms/op
     p(99.9900) =     10.622 ms/op
     p(99.9990) =     11.174 ms/op
     p(99.9999) =     11.174 ms/op
    p(100.0000) =     11.174 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.095 ms/op
Iteration   1: 2.008 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.544 ms/op
                 getUser·p0.99:   3.595 ms/op
                 getUser·p0.999:  13.517 ms/op
                 getUser·p0.9999: 13.625 ms/op
                 getUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15932
  mean =      2.008 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 14769 
    [ 2.500,  3.750) = 902 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      3.595 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     13.625 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 4.650 ±(99.9%) 0.140 ms/op
Iteration   1: 3.647 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  22.761 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8799
  mean =      3.647 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 285 
    [ 2.500,  5.000) = 8317 
    [ 5.000,  7.500) = 133 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     22.761 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.639          ops/ms
ClientSimple.existUser                       thrpt         12.100          ops/ms
ClientSimple.getUser                         thrpt         12.696          ops/ms
ClientSimple.listUser                        thrpt          9.433          ops/ms
ClientSimple.createUser                       avgt          2.444           ms/op
ClientSimple.existUser                        avgt          1.848           ms/op
ClientSimple.getUser                          avgt          1.963           ms/op
ClientSimple.listUser                         avgt          3.250           ms/op
ClientSimple.createUser                     sample  14522   2.200 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.762           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.083           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.511           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.876           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.430           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.482           ms/op
ClientSimple.existUser                      sample  18209   1.757 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.622           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.677           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.249           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.064           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.335           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.622           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.174           ms/op
ClientSimple.getUser                        sample  15932   2.008 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.844           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.544           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.595           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.517           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.625           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.664           ms/op
ClientSimple.listUser                       sample   8799   3.647 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.149           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.604           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.137           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.250           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.761           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.101           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.101           ms/op

Benchmark result is saved to 1722319571002.json
