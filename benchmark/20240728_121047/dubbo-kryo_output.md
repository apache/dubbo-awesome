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
# Warmup Iteration   1: 1.834 ops/ms
Iteration   1: 6.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.973 ops/ms


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
# Warmup Iteration   1: 4.524 ops/ms
Iteration   1: 11.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.870 ops/ms


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
# Warmup Iteration   1: 5.631 ops/ms
Iteration   1: 11.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.940 ops/ms


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
# Warmup Iteration   1: 5.897 ops/ms
Iteration   1: 8.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.732 ops/ms


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.091 ms/op
Iteration   1: 1.958 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.958 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.046 ms/op
Iteration   1: 1.833 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.833 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.057 ms/op
Iteration   1: 2.115 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.115 ms/op


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.084 ms/op
Iteration   1: 3.312 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.312 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.090 ms/op
Iteration   1: 1.950 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   1.794 ms/op
                 createUser·p0.90:   2.141 ms/op
                 createUser·p0.95:   2.504 ms/op
                 createUser·p0.99:   5.389 ms/op
                 createUser·p0.999:  25.112 ms/op
                 createUser·p0.9999: 27.092 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16413
  mean =      1.950 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15583 
    [ 2.500,  5.000) = 638 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.141 ms/op
     p(95.0000) =      2.504 ms/op
     p(99.0000) =      5.389 ms/op
     p(99.9000) =     25.112 ms/op
     p(99.9900) =     27.092 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 2.915 ±(99.9%) 0.064 ms/op
Iteration   1: 1.826 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.690 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  13.443 ms/op
                 existUser·p0.9999: 14.914 ms/op
                 existUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17507
  mean =      1.826 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 467 
    [ 1.250,  2.500) = 16000 
    [ 2.500,  3.750) = 808 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     13.443 ms/op
     p(99.9900) =     14.914 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 3.414 ±(99.9%) 0.114 ms/op
Iteration   1: 2.180 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.109 ms/op
                 getUser·p0.90:   2.703 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 13.616 ms/op
                 getUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14675
  mean =      2.180 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 11983 
    [ 2.500,  3.750) = 2450 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.616 ms/op
     p(99.9990) =     13.631 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.134 ms/op
Iteration   1: 3.279 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.252 ms/op
                 listUser·p0.90:   4.109 ms/op
                 listUser·p0.95:   4.379 ms/op
                 listUser·p0.99:   6.185 ms/op
                 listUser·p0.999:  9.622 ms/op
                 listUser·p0.9999: 9.847 ms/op
                 listUser·p1.00:   9.847 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9747
  mean =      3.279 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 92 
    [ 2.000,  3.000) = 3963 
    [ 3.000,  4.000) = 4374 
    [ 4.000,  5.000) = 1006 
    [ 5.000,  6.000) = 184 
    [ 6.000,  7.000) = 54 
    [ 7.000,  8.000) = 38 
    [ 8.000,  9.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      4.109 ms/op
     p(95.0000) =      4.379 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =      9.622 ms/op
     p(99.9900) =      9.847 ms/op
     p(99.9990) =      9.847 ms/op
     p(99.9999) =      9.847 ms/op
    p(100.0000) =      9.847 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.973          ops/ms
ClientSimple.existUser                       thrpt         11.870          ops/ms
ClientSimple.getUser                         thrpt         11.940          ops/ms
ClientSimple.listUser                        thrpt          8.732          ops/ms
ClientSimple.createUser                       avgt          1.958           ms/op
ClientSimple.existUser                        avgt          1.833           ms/op
ClientSimple.getUser                          avgt          2.115           ms/op
ClientSimple.listUser                         avgt          3.312           ms/op
ClientSimple.createUser                     sample  16413   1.950 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.571           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.794           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.141           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.504           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.389           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.112           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.092           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.197           ms/op
ClientSimple.existUser                      sample  17507   1.826 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.560           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.690           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.489           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.443           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.914           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.926           ms/op
ClientSimple.getUser                        sample  14675   2.180 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.953           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.109           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.777           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.058           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.616           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.631           ms/op
ClientSimple.listUser                       sample   9747   3.279 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.904           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.252           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.109           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.379           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.185           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.622           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.847           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.847           ms/op

Benchmark result is saved to 1722168380809.json
