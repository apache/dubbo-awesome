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
# Warmup Iteration   1: 1.835 ops/ms
Iteration   1: 7.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.441 ops/ms


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
# Warmup Iteration   1: 6.258 ops/ms
Iteration   1: 12.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.511 ops/ms


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
# Warmup Iteration   1: 6.362 ops/ms
Iteration   1: 14.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.916 ops/ms


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
# Warmup Iteration   1: 5.175 ops/ms
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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.062 ms/op
Iteration   1: 2.073 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.073 ms/op


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
# Warmup Iteration   1: 3.001 ±(99.9%) 0.054 ms/op
Iteration   1: 1.910 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.910 ms/op


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
# Warmup Iteration   1: 2.867 ±(99.9%) 0.046 ms/op
Iteration   1: 1.936 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.936 ms/op


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.114 ms/op
Iteration   1: 3.515 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.515 ms/op


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.101 ms/op
Iteration   1: 2.004 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   1.851 ms/op
                 createUser·p0.90:   2.429 ms/op
                 createUser·p0.95:   2.783 ms/op
                 createUser·p0.99:   4.163 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 21.499 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15951
  mean =      2.004 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14543 
    [ 2.500,  5.000) = 1329 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.783 ms/op
     p(99.0000) =      4.163 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     21.499 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.119 ms/op
Iteration   1: 1.833 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   1.675 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  11.232 ms/op
                 existUser·p0.9999: 11.407 ms/op
                 existUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17430
  mean =      1.833 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 237 
    [ 1.250,  2.500) = 15904 
    [ 2.500,  3.750) = 1172 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =     11.232 ms/op
     p(99.9900) =     11.407 ms/op
     p(99.9990) =     11.420 ms/op
     p(99.9999) =     11.420 ms/op
    p(100.0000) =     11.420 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.085 ms/op
Iteration   1: 1.987 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.573 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.507 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   4.826 ms/op
                 getUser·p0.999:  16.400 ms/op
                 getUser·p0.9999: 16.626 ms/op
                 getUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16086
  mean =      1.987 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 481 
    [ 1.250,  2.500) = 13976 
    [ 2.500,  3.750) = 1413 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.826 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     16.626 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 4.290 ±(99.9%) 0.116 ms/op
Iteration   1: 2.916 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   2.736 ms/op
                 listUser·p0.90:   3.703 ms/op
                 listUser·p0.95:   4.026 ms/op
                 listUser·p0.99:   4.653 ms/op
                 listUser·p0.999:  12.272 ms/op
                 listUser·p0.9999: 12.574 ms/op
                 listUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 11034
  mean =      2.916 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1251 
    [ 2.500,  3.750) = 8756 
    [ 3.750,  5.000) = 941 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.736 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     12.574 ms/op
     p(99.9990) =     12.583 ms/op
     p(99.9999) =     12.583 ms/op
    p(100.0000) =     12.583 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.441          ops/ms
ClientSimple.existUser                       thrpt         12.511          ops/ms
ClientSimple.getUser                         thrpt         14.916          ops/ms
ClientSimple.listUser                        thrpt          8.375          ops/ms
ClientSimple.createUser                       avgt          2.073           ms/op
ClientSimple.existUser                        avgt          1.910           ms/op
ClientSimple.getUser                          avgt          1.936           ms/op
ClientSimple.listUser                         avgt          3.515           ms/op
ClientSimple.createUser                     sample  15951   2.004 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.774           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.851           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.429           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.783           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.163           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.742           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.499           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.889           ms/op
ClientSimple.existUser                      sample  17430   1.833 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.543           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.675           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.551           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.232           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.407           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.420           ms/op
ClientSimple.getUser                        sample  16086   1.987 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.573           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.826           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.400           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.626           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.646           ms/op
ClientSimple.listUser                       sample  11034   2.916 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.976           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.736           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.703           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.026           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.272           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.574           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.583           ms/op

Benchmark result is saved to 1721973970324.json
