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
# Warmup Iteration   1: 1.260 ops/ms
Iteration   1: 6.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.444 ops/ms


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
# Warmup Iteration   1: 5.621 ops/ms
Iteration   1: 13.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.622 ops/ms


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
# Warmup Iteration   1: 6.687 ops/ms
Iteration   1: 13.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.165 ops/ms


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
# Warmup Iteration   1: 5.290 ops/ms
Iteration   1: 9.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.185 ops/ms


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.064 ms/op
Iteration   1: 1.985 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.985 ms/op


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
# Warmup Iteration   1: 2.863 ±(99.9%) 0.048 ms/op
Iteration   1: 1.817 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.817 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.063 ms/op
Iteration   1: 1.948 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.948 ms/op


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.084 ms/op
Iteration   1: 3.199 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.199 ms/op


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
# Warmup Iteration   1: 3.601 ±(99.9%) 0.102 ms/op
Iteration   1: 2.090 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   1.898 ms/op
                 createUser·p0.90:   2.367 ms/op
                 createUser·p0.95:   2.687 ms/op
                 createUser·p0.99:   8.217 ms/op
                 createUser·p0.999:  17.258 ms/op
                 createUser·p0.9999: 23.817 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15325
  mean =      2.090 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14207 
    [ 2.500,  5.000) = 844 
    [ 5.000,  7.500) = 89 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     17.258 ms/op
     p(99.9900) =     23.817 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.073 ms/op
Iteration   1: 1.665 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   1.591 ms/op
                 existUser·p0.90:   1.894 ms/op
                 existUser·p0.95:   2.220 ms/op
                 existUser·p0.99:   2.834 ms/op
                 existUser·p0.999:  11.377 ms/op
                 existUser·p0.9999: 12.994 ms/op
                 existUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19639
  mean =      1.665 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 435 
    [ 1.250,  2.500) = 18638 
    [ 2.500,  3.750) = 468 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      1.591 ms/op
     p(90.0000) =      1.894 ms/op
     p(95.0000) =      2.220 ms/op
     p(99.0000) =      2.834 ms/op
     p(99.9000) =     11.377 ms/op
     p(99.9900) =     12.994 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


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
# Warmup Iteration   1: 3.439 ±(99.9%) 0.104 ms/op
Iteration   1: 2.054 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.374 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.511 ms/op
                 getUser·p0.95:   2.720 ms/op
                 getUser·p0.99:   3.925 ms/op
                 getUser·p0.999:  19.038 ms/op
                 getUser·p0.9999: 19.184 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15636
  mean =      2.054 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 277 
    [ 1.250,  2.500) = 13713 
    [ 2.500,  3.750) = 1476 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.925 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     19.184 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.128 ms/op
Iteration   1: 3.553 ±(99.9%) 0.085 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   3.449 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.234 ms/op
                 listUser·p0.999:  44.433 ms/op
                 listUser·p0.9999: 55.050 ms/op
                 listUser·p1.00:   55.050 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9011
  mean =      3.553 ±(99.9%) 0.085 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8776 
    [ 5.000, 10.000) = 196 
    [10.000, 15.000) = 4 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 19 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     44.433 ms/op
     p(99.9900) =     55.050 ms/op
     p(99.9990) =     55.050 ms/op
     p(99.9999) =     55.050 ms/op
    p(100.0000) =     55.050 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.444          ops/ms
ClientSimple.existUser                       thrpt         13.622          ops/ms
ClientSimple.getUser                         thrpt         13.165          ops/ms
ClientSimple.listUser                        thrpt          9.185          ops/ms
ClientSimple.createUser                       avgt          1.985           ms/op
ClientSimple.existUser                        avgt          1.817           ms/op
ClientSimple.getUser                          avgt          1.948           ms/op
ClientSimple.listUser                         avgt          3.199           ms/op
ClientSimple.createUser                     sample  15325   2.090 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.804           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.898           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.367           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.217           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.258           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.817           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.445           ms/op
ClientSimple.existUser                      sample  19639   1.665 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.777           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.591           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.894           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.834           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.377           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.994           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.468           ms/op
ClientSimple.getUser                        sample  15636   2.054 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.374           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.925           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.038           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.184           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.202           ms/op
ClientSimple.listUser                       sample   9011   3.553 ± 0.085   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.836           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.449           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.234           ms/op
ClientSimple.listUser:listUser·p0.999       sample         44.433           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         55.050           ms/op
ClientSimple.listUser:listUser·p1.00        sample         55.050           ms/op

Benchmark result is saved to 1725818705645.json
