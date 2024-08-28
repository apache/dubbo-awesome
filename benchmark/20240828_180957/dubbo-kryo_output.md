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
# Warmup Iteration   1: 1.418 ops/ms
Iteration   1: 6.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.493 ops/ms


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
# Warmup Iteration   1: 5.806 ops/ms
Iteration   1: 12.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.568 ops/ms


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
# Warmup Iteration   1: 5.204 ops/ms
Iteration   1: 13.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.522 ops/ms


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
# Warmup Iteration   1: 4.914 ops/ms
Iteration   1: 7.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.861 ops/ms


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.075 ms/op
Iteration   1: 2.079 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.079 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.068 ms/op
Iteration   1: 2.017 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.017 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.068 ms/op
Iteration   1: 2.111 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.111 ms/op


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
# Warmup Iteration   1: 4.452 ±(99.9%) 0.076 ms/op
Iteration   1: 3.444 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.444 ms/op


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
# Warmup Iteration   1: 3.392 ±(99.9%) 0.095 ms/op
Iteration   1: 1.933 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   1.731 ms/op
                 createUser·p0.90:   2.347 ms/op
                 createUser·p0.95:   2.601 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  21.407 ms/op
                 createUser·p0.9999: 21.703 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16709
  mean =      1.933 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15644 
    [ 2.500,  5.000) = 910 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =     21.407 ms/op
     p(99.9900) =     21.703 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 2.936 ±(99.9%) 0.062 ms/op
Iteration   1: 2.210 ±(99.9%) 0.061 ms/op
                 existUser·p0.00:   0.423 ms/op
                 existUser·p0.50:   2.032 ms/op
                 existUser·p0.90:   2.605 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   5.798 ms/op
                 existUser·p0.999:  43.555 ms/op
                 existUser·p0.9999: 44.309 ms/op
                 existUser·p1.00:   44.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14467
  mean =      2.210 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14287 
    [ 5.000, 10.000) = 84 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.798 ms/op
     p(99.9000) =     43.555 ms/op
     p(99.9900) =     44.309 ms/op
     p(99.9990) =     44.368 ms/op
     p(99.9999) =     44.368 ms/op
    p(100.0000) =     44.368 ms/op


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
# Warmup Iteration   1: 3.076 ±(99.9%) 0.073 ms/op
Iteration   1: 1.964 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   1.808 ms/op
                 getUser·p0.90:   2.322 ms/op
                 getUser·p0.95:   2.515 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  21.758 ms/op
                 getUser·p0.9999: 23.466 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16279
  mean =      1.964 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15428 
    [ 2.500,  5.000) = 696 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =     21.758 ms/op
     p(99.9900) =     23.466 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.136 ms/op
Iteration   1: 3.412 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.416 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.234 ms/op
                 listUser·p0.999:  15.829 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9380
  mean =      3.412 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1241 
    [ 2.500,  3.750) = 5316 
    [ 3.750,  5.000) = 2627 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     15.829 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.493          ops/ms
ClientSimple.existUser                       thrpt         12.568          ops/ms
ClientSimple.getUser                         thrpt         13.522          ops/ms
ClientSimple.listUser                        thrpt          7.861          ops/ms
ClientSimple.createUser                       avgt          2.079           ms/op
ClientSimple.existUser                        avgt          2.017           ms/op
ClientSimple.getUser                          avgt          2.111           ms/op
ClientSimple.listUser                         avgt          3.444           ms/op
ClientSimple.createUser                     sample  16709   1.933 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.725           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.731           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.347           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.751           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.407           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.703           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.725           ms/op
ClientSimple.existUser                      sample  14467   2.210 ± 0.061   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.423           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.032           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.798           ms/op
ClientSimple.existUser:existUser·p0.999     sample         43.555           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         44.309           ms/op
ClientSimple.existUser:existUser·p1.00      sample         44.368           ms/op
ClientSimple.getUser                        sample  16279   1.964 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.592           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.808           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.322           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.940           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.758           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.466           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.527           ms/op
ClientSimple.listUser                       sample   9380   3.412 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.000           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.416           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.234           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.829           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.777           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.777           ms/op

Benchmark result is saved to 1724868334965.json
