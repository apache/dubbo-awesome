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
# Warmup Iteration   1: 1.267 ops/ms
Iteration   1: 6.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.127 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.505 ops/ms
Iteration   1: 12.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.162 ops/ms


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
# Warmup Iteration   1: 4.892 ops/ms
Iteration   1: 11.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.536 ops/ms


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
# Warmup Iteration   1: 4.918 ops/ms
Iteration   1: 8.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.424 ops/ms


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
# Warmup Iteration   1: 4.839 ±(99.9%) 0.120 ms/op
Iteration   1: 2.541 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.541 ms/op


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
# Warmup Iteration   1: 2.918 ±(99.9%) 0.049 ms/op
Iteration   1: 1.924 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.924 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ±(99.9%) 0.081 ms/op
Iteration   1: 2.038 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.038 ms/op


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
# Warmup Iteration   1: 4.490 ±(99.9%) 0.100 ms/op
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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.096 ms/op
Iteration   1: 2.171 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   1.999 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   2.773 ms/op
                 createUser·p0.99:   9.361 ms/op
                 createUser·p0.999:  15.614 ms/op
                 createUser·p0.9999: 16.218 ms/op
                 createUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14764
  mean =      2.171 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 13076 
    [ 2.500,  3.750) = 1400 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      9.361 ms/op
     p(99.9000) =     15.614 ms/op
     p(99.9900) =     16.218 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 3.119 ±(99.9%) 0.087 ms/op
Iteration   1: 1.941 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.547 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  26.770 ms/op
                 existUser·p0.9999: 29.188 ms/op
                 existUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16521
  mean =      1.941 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15612 
    [ 2.500,  5.000) = 773 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.547 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =     26.770 ms/op
     p(99.9900) =     29.188 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 3.543 ±(99.9%) 0.113 ms/op
Iteration   1: 2.151 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   1.994 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  18.219 ms/op
                 getUser·p0.9999: 18.931 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14854
  mean =      2.151 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 12945 
    [ 2.500,  3.750) = 1486 
    [ 3.750,  5.000) = 153 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      1.994 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.931 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.115 ms/op
Iteration   1: 3.479 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.473 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.087 ms/op
                 listUser·p0.999:  20.637 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9200
  mean =      3.479 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1229 
    [ 2.500,  5.000) = 7722 
    [ 5.000,  7.500) = 202 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     20.637 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.127          ops/ms
ClientSimple.existUser                       thrpt         12.162          ops/ms
ClientSimple.getUser                         thrpt         11.536          ops/ms
ClientSimple.listUser                        thrpt          8.424          ops/ms
ClientSimple.createUser                       avgt          2.541           ms/op
ClientSimple.existUser                        avgt          1.924           ms/op
ClientSimple.getUser                          avgt          2.038           ms/op
ClientSimple.listUser                         avgt          3.727           ms/op
ClientSimple.createUser                     sample  14764   2.171 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.812           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.999           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.361           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.614           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.218           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.679           ms/op
ClientSimple.existUser                      sample  16521   1.941 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.637           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.796           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.547           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.366           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.770           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.188           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.769           ms/op
ClientSimple.getUser                        sample  14854   2.151 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.770           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.994           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.324           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.219           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.931           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.169           ms/op
ClientSimple.listUser                       sample   9200   3.479 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.939           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.473           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.087           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.637           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.135           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.135           ms/op

Benchmark result is saved to 1724181797886.json
