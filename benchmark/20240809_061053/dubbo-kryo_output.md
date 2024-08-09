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
# Warmup Iteration   1: 1.933 ops/ms
Iteration   1: 7.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.818 ops/ms


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
# Warmup Iteration   1: 6.326 ops/ms
Iteration   1: 13.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.289 ops/ms


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
# Warmup Iteration   1: 6.553 ops/ms
Iteration   1: 13.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.644 ops/ms


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
# Warmup Iteration   1: 5.045 ops/ms
Iteration   1: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.225 ops/ms


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
# Warmup Iteration   1: 3.484 ±(99.9%) 0.056 ms/op
Iteration   1: 2.292 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.292 ms/op


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
# Warmup Iteration   1: 3.137 ±(99.9%) 0.057 ms/op
Iteration   1: 1.805 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.805 ms/op


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
# Warmup Iteration   1: 3.364 ±(99.9%) 0.058 ms/op
Iteration   1: 1.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.987 ms/op


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.090 ms/op
Iteration   1: 3.305 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.305 ms/op


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
# Warmup Iteration   1: 3.402 ±(99.9%) 0.088 ms/op
Iteration   1: 2.028 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   1.872 ms/op
                 createUser·p0.90:   2.392 ms/op
                 createUser·p0.95:   2.613 ms/op
                 createUser·p0.99:   6.449 ms/op
                 createUser·p0.999:  18.408 ms/op
                 createUser·p0.9999: 18.864 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15778
  mean =      2.028 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 618 
    [ 1.250,  2.500) = 14121 
    [ 2.500,  3.750) = 764 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      6.449 ms/op
     p(99.9000) =     18.408 ms/op
     p(99.9900) =     18.864 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.078 ms/op
Iteration   1: 1.900 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.308 ms/op
                 existUser·p0.999:  12.749 ms/op
                 existUser·p0.9999: 13.007 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16834
  mean =      1.900 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 501 
    [ 1.250,  2.500) = 14870 
    [ 2.500,  3.750) = 1365 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.308 ms/op
     p(99.9000) =     12.749 ms/op
     p(99.9900) =     13.007 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


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
# Warmup Iteration   1: 3.634 ±(99.9%) 0.097 ms/op
Iteration   1: 1.980 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.306 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.413 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   3.304 ms/op
                 getUser·p0.999:  10.886 ms/op
                 getUser·p0.9999: 11.039 ms/op
                 getUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16145
  mean =      1.980 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 346 
    [ 1.250,  2.500) = 14570 
    [ 2.500,  3.750) = 1113 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.306 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.304 ms/op
     p(99.9000) =     10.886 ms/op
     p(99.9900) =     11.039 ms/op
     p(99.9990) =     11.059 ms/op
     p(99.9999) =     11.059 ms/op
    p(100.0000) =     11.059 ms/op


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
# Warmup Iteration   1: 5.495 ±(99.9%) 0.198 ms/op
Iteration   1: 3.638 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.514 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.046 ms/op
                 listUser·p0.999:  21.339 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8785
  mean =      3.638 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 510 
    [ 2.500,  5.000) = 7889 
    [ 5.000,  7.500) = 318 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.046 ms/op
     p(99.9000) =     21.339 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.818          ops/ms
ClientSimple.existUser                       thrpt         13.289          ops/ms
ClientSimple.getUser                         thrpt         13.644          ops/ms
ClientSimple.listUser                        thrpt          8.225          ops/ms
ClientSimple.createUser                       avgt          2.292           ms/op
ClientSimple.existUser                        avgt          1.805           ms/op
ClientSimple.getUser                          avgt          1.987           ms/op
ClientSimple.listUser                         avgt          3.305           ms/op
ClientSimple.createUser                     sample  15778   2.028 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.539           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.872           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.392           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.449           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.408           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.864           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.940           ms/op
ClientSimple.existUser                      sample  16834   1.900 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.573           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.806           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.308           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.749           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.007           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.287           ms/op
ClientSimple.getUser                        sample  16145   1.980 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.306           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.304           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.886           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.039           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.059           ms/op
ClientSimple.listUser                       sample   8785   3.638 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.094           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.514           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.046           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.339           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.922           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.922           ms/op

Benchmark result is saved to 1723183558183.json
