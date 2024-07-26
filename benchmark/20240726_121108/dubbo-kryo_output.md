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
# Warmup Iteration   1: 1.718 ops/ms
Iteration   1: 8.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.406 ops/ms


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
# Warmup Iteration   1: 6.002 ops/ms
Iteration   1: 11.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.374 ops/ms


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
# Warmup Iteration   1: 5.279 ops/ms
Iteration   1: 13.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.310 ops/ms


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
# Warmup Iteration   1: 4.102 ops/ms
Iteration   1: 8.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.292 ops/ms


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.062 ms/op
Iteration   1: 2.106 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.106 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.063 ms/op
Iteration   1: 1.947 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.947 ms/op


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
# Warmup Iteration   1: 3.552 ±(99.9%) 0.058 ms/op
Iteration   1: 2.002 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.002 ms/op


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.098 ms/op
Iteration   1: 3.192 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.192 ms/op


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
# Warmup Iteration   1: 3.379 ±(99.9%) 0.086 ms/op
Iteration   1: 2.074 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   1.874 ms/op
                 createUser·p0.90:   2.402 ms/op
                 createUser·p0.95:   2.601 ms/op
                 createUser·p0.99:   10.617 ms/op
                 createUser·p0.999:  18.590 ms/op
                 createUser·p0.9999: 19.982 ms/op
                 createUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15415
  mean =      2.074 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14278 
    [ 2.500,  5.000) = 945 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.402 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     18.590 ms/op
     p(99.9900) =     19.982 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 2.836 ±(99.9%) 0.062 ms/op
Iteration   1: 1.701 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   1.622 ms/op
                 existUser·p0.90:   1.989 ms/op
                 existUser·p0.95:   2.159 ms/op
                 existUser·p0.99:   4.105 ms/op
                 existUser·p0.999:  5.670 ms/op
                 existUser·p0.9999: 6.046 ms/op
                 existUser·p1.00:   6.046 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18879
  mean =      1.701 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 33 
    [1.000, 1.500) = 3766 
    [1.500, 2.000) = 13301 
    [2.000, 2.500) = 1304 
    [2.500, 3.000) = 212 
    [3.000, 3.500) = 38 
    [3.500, 4.000) = 25 
    [4.000, 4.500) = 46 
    [4.500, 5.000) = 52 
    [5.000, 5.500) = 75 
    [5.500, 6.000) = 22 
    [6.000, 6.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.622 ms/op
     p(90.0000) =      1.989 ms/op
     p(95.0000) =      2.159 ms/op
     p(99.0000) =      4.105 ms/op
     p(99.9000) =      5.670 ms/op
     p(99.9900) =      6.046 ms/op
     p(99.9990) =      6.046 ms/op
     p(99.9999) =      6.046 ms/op
    p(100.0000) =      6.046 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.099 ms/op
Iteration   1: 2.241 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.390 ms/op
                 getUser·p0.50:   2.298 ms/op
                 getUser·p0.90:   2.671 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   4.512 ms/op
                 getUser·p0.999:  13.795 ms/op
                 getUser·p0.9999: 14.592 ms/op
                 getUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14422
  mean =      2.241 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 317 
    [ 1.250,  2.500) = 10525 
    [ 2.500,  3.750) = 3340 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      2.298 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      4.512 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     14.592 ms/op
     p(99.9990) =     14.729 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 5.248 ±(99.9%) 0.163 ms/op
Iteration   1: 3.405 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   0.622 ms/op
                 listUser·p0.50:   3.269 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  25.415 ms/op
                 listUser·p0.9999: 25.690 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9393
  mean =      3.405 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1475 
    [ 2.500,  5.000) = 7544 
    [ 5.000,  7.500) = 304 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     25.415 ms/op
     p(99.9900) =     25.690 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.406          ops/ms
ClientSimple.existUser                       thrpt         11.374          ops/ms
ClientSimple.getUser                         thrpt         13.310          ops/ms
ClientSimple.listUser                        thrpt          8.292          ops/ms
ClientSimple.createUser                       avgt          2.106           ms/op
ClientSimple.existUser                        avgt          1.947           ms/op
ClientSimple.getUser                          avgt          2.002           ms/op
ClientSimple.listUser                         avgt          3.192           ms/op
ClientSimple.createUser                     sample  15415   2.074 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.710           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.874           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.402           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.617           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.590           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.982           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.283           ms/op
ClientSimple.existUser                      sample  18879   1.701 ± 0.010   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.660           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.622           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.989           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.159           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.105           ms/op
ClientSimple.existUser:existUser·p0.999     sample          5.670           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          6.046           ms/op
ClientSimple.existUser:existUser·p1.00      sample          6.046           ms/op
ClientSimple.getUser                        sample  14422   2.241 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.390           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.298           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.512           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.795           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.592           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.729           ms/op
ClientSimple.listUser                       sample   9393   3.405 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.622           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.269           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.094           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.415           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.690           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.690           ms/op

Benchmark result is saved to 1721995591821.json
