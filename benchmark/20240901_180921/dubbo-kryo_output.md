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
# Warmup Iteration   1: 1.620 ops/ms
Iteration   1: 6.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.421 ops/ms


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
# Warmup Iteration   1: 7.098 ops/ms
Iteration   1: 13.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.839 ops/ms


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
# Warmup Iteration   1: 5.263 ops/ms
Iteration   1: 14.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.343 ops/ms


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
# Warmup Iteration   1: 4.150 ops/ms
Iteration   1: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.026 ops/ms


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.067 ms/op
Iteration   1: 2.071 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.071 ms/op


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.060 ms/op
Iteration   1: 1.841 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.841 ms/op


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.069 ms/op
Iteration   1: 2.009 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.009 ms/op


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
# Warmup Iteration   1: 4.584 ±(99.9%) 0.080 ms/op
Iteration   1: 3.239 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.239 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.107 ms/op
Iteration   1: 2.069 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   1.874 ms/op
                 createUser·p0.90:   2.540 ms/op
                 createUser·p0.95:   2.761 ms/op
                 createUser·p0.99:   5.776 ms/op
                 createUser·p0.999:  12.725 ms/op
                 createUser·p0.9999: 13.725 ms/op
                 createUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15347
  mean =      2.069 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 13387 
    [ 2.500,  3.750) = 1403 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      5.776 ms/op
     p(99.9000) =     12.725 ms/op
     p(99.9900) =     13.725 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.103 ms/op
Iteration   1: 2.081 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.062 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   3.738 ms/op
                 existUser·p0.999:  8.189 ms/op
                 existUser·p0.9999: 8.502 ms/op
                 existUser·p1.00:   8.520 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15365
  mean =      2.081 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 64 
    [1.000, 1.500) = 1576 
    [1.500, 2.000) = 5189 
    [2.000, 2.500) = 6519 
    [2.500, 3.000) = 1629 
    [3.000, 3.500) = 197 
    [3.500, 4.000) = 76 
    [4.000, 4.500) = 22 
    [4.500, 5.000) = 8 
    [5.000, 5.500) = 6 
    [5.500, 6.000) = 17 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 12 
    [7.000, 7.500) = 6 
    [7.500, 8.000) = 7 
    [8.000, 8.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.738 ms/op
     p(99.9000) =      8.189 ms/op
     p(99.9900) =      8.502 ms/op
     p(99.9990) =      8.520 ms/op
     p(99.9999) =      8.520 ms/op
    p(100.0000) =      8.520 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.090 ms/op
Iteration   1: 2.078 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   1.980 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.889 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  12.665 ms/op
                 getUser·p0.9999: 12.809 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15451
  mean =      2.078 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 13086 
    [ 2.500,  3.750) = 2119 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.889 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     12.809 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


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
# Warmup Iteration   1: 4.531 ±(99.9%) 0.138 ms/op
Iteration   1: 3.324 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.265 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.626 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.296 ms/op
                 listUser·p0.9999: 8.503 ms/op
                 listUser·p1.00:   8.503 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9665
  mean =      3.324 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 60 
    [2.000, 2.500) = 1210 
    [2.500, 3.000) = 2756 
    [3.000, 3.500) = 1668 
    [3.500, 4.000) = 2169 
    [4.000, 4.500) = 1231 
    [4.500, 5.000) = 301 
    [5.000, 5.500) = 151 
    [5.500, 6.000) = 64 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 4 
    [7.500, 8.000) = 15 
    [8.000, 8.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.626 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      8.296 ms/op
     p(99.9900) =      8.503 ms/op
     p(99.9990) =      8.503 ms/op
     p(99.9999) =      8.503 ms/op
    p(100.0000) =      8.503 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.421          ops/ms
ClientSimple.existUser                       thrpt         13.839          ops/ms
ClientSimple.getUser                         thrpt         14.343          ops/ms
ClientSimple.listUser                        thrpt          8.026          ops/ms
ClientSimple.createUser                       avgt          2.071           ms/op
ClientSimple.existUser                        avgt          1.841           ms/op
ClientSimple.getUser                          avgt          2.009           ms/op
ClientSimple.listUser                         avgt          3.239           ms/op
ClientSimple.createUser                     sample  15347   2.069 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.663           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.874           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.540           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.776           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.725           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.725           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.057           ms/op
ClientSimple.existUser                      sample  15365   2.081 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.720           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.062           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.738           ms/op
ClientSimple.existUser:existUser·p0.999     sample          8.189           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          8.502           ms/op
ClientSimple.existUser:existUser·p1.00      sample          8.520           ms/op
ClientSimple.getUser                        sample  15451   2.078 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.835           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.980           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.889           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.617           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.665           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.809           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.845           ms/op
ClientSimple.listUser                       sample   9665   3.324 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.300           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.265           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.626           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.562           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.296           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.503           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.503           ms/op

Benchmark result is saved to 1725213916129.json
