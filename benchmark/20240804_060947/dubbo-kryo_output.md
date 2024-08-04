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
# Warmup Iteration   1: 1.776 ops/ms
Iteration   1: 6.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.992 ops/ms


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
# Warmup Iteration   1: 6.612 ops/ms
Iteration   1: 13.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.754 ops/ms


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
# Warmup Iteration   1: 5.509 ops/ms
Iteration   1: 13.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.321 ops/ms


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
# Warmup Iteration   1: 4.315 ops/ms
Iteration   1: 8.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.457 ops/ms


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.061 ms/op
Iteration   1: 1.908 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.908 ms/op


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
# Warmup Iteration   1: 3.149 ±(99.9%) 0.070 ms/op
Iteration   1: 1.885 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.885 ms/op


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
# Warmup Iteration   1: 3.077 ±(99.9%) 0.047 ms/op
Iteration   1: 1.942 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.942 ms/op


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.077 ms/op
Iteration   1: 3.120 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.120 ms/op


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
# Warmup Iteration   1: 3.411 ±(99.9%) 0.079 ms/op
Iteration   1: 2.176 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   1.933 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   2.863 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  36.045 ms/op
                 createUser·p0.9999: 40.112 ms/op
                 createUser·p1.00:   40.174 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14697
  mean =      2.176 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14489 
    [ 5.000, 10.000) = 109 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     36.045 ms/op
     p(99.9900) =     40.112 ms/op
     p(99.9990) =     40.174 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.063 ms/op
Iteration   1: 1.934 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.227 ms/op
                 existUser·p0.50:   1.929 ms/op
                 existUser·p0.90:   2.462 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   3.326 ms/op
                 existUser·p0.999:  12.312 ms/op
                 existUser·p0.9999: 12.462 ms/op
                 existUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16525
  mean =      1.934 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 520 
    [ 1.250,  2.500) = 14586 
    [ 2.500,  3.750) = 1302 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.227 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.326 ms/op
     p(99.9000) =     12.312 ms/op
     p(99.9900) =     12.462 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.083 ms/op
Iteration   1: 1.940 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   1.810 ms/op
                 getUser·p0.90:   2.413 ms/op
                 getUser·p0.95:   2.585 ms/op
                 getUser·p0.99:   2.990 ms/op
                 getUser·p0.999:  20.906 ms/op
                 getUser·p0.9999: 21.061 ms/op
                 getUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16512
  mean =      1.940 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15334 
    [ 2.500,  5.000) = 1108 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      2.990 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     21.061 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.835 ±(99.9%) 0.132 ms/op
Iteration   1: 2.972 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   2.847 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   4.958 ms/op
                 listUser·p0.999:  6.642 ms/op
                 listUser·p0.9999: 9.130 ms/op
                 listUser·p1.00:   9.159 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10878
  mean =      2.972 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 7 
    [ 1.500,  2.000) = 131 
    [ 2.000,  2.500) = 1242 
    [ 2.500,  3.000) = 6079 
    [ 3.000,  3.500) = 1900 
    [ 3.500,  4.000) = 667 
    [ 4.000,  4.500) = 568 
    [ 4.500,  5.000) = 193 
    [ 5.000,  5.500) = 34 
    [ 5.500,  6.000) = 20 
    [ 6.000,  6.500) = 23 
    [ 6.500,  7.000) = 6 
    [ 7.000,  7.500) = 0 
    [ 7.500,  8.000) = 6 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      4.958 ms/op
     p(99.9000) =      6.642 ms/op
     p(99.9900) =      9.130 ms/op
     p(99.9990) =      9.159 ms/op
     p(99.9999) =      9.159 ms/op
    p(100.0000) =      9.159 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.992          ops/ms
ClientSimple.existUser                       thrpt         13.754          ops/ms
ClientSimple.getUser                         thrpt         13.321          ops/ms
ClientSimple.listUser                        thrpt          8.457          ops/ms
ClientSimple.createUser                       avgt          1.908           ms/op
ClientSimple.existUser                        avgt          1.885           ms/op
ClientSimple.getUser                          avgt          1.942           ms/op
ClientSimple.listUser                         avgt          3.120           ms/op
ClientSimple.createUser                     sample  14697   2.176 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.643           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.933           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.471           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.045           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         40.112           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.174           ms/op
ClientSimple.existUser                      sample  16525   1.934 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.227           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.929           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.326           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.312           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.462           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.665           ms/op
ClientSimple.getUser                        sample  16512   1.940 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.721           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.810           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.990           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.906           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.061           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.168           ms/op
ClientSimple.listUser                       sample  10878   2.972 ± 0.019   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.399           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.847           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.813           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.958           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.642           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.130           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.159           ms/op

Benchmark result is saved to 1722751540441.json
