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
# Warmup Iteration   1: 1.685 ops/ms
Iteration   1: 7.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.127 ops/ms


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
# Warmup Iteration   1: 5.581 ops/ms
Iteration   1: 14.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.157 ops/ms


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
# Warmup Iteration   1: 5.849 ops/ms
Iteration   1: 12.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.047 ops/ms


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
# Warmup Iteration   1: 5.787 ops/ms
Iteration   1: 8.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.600 ops/ms


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.067 ms/op
Iteration   1: 2.564 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.564 ms/op


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
# Warmup Iteration   1: 3.148 ±(99.9%) 0.055 ms/op
Iteration   1: 2.053 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.053 ms/op


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
# Warmup Iteration   1: 3.449 ±(99.9%) 0.061 ms/op
Iteration   1: 2.218 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.218 ms/op


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.102 ms/op
Iteration   1: 3.572 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.572 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.084 ms/op
Iteration   1: 1.998 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   1.753 ms/op
                 createUser·p0.90:   2.269 ms/op
                 createUser·p0.95:   2.535 ms/op
                 createUser·p0.99:   10.879 ms/op
                 createUser·p0.999:  20.546 ms/op
                 createUser·p0.9999: 21.574 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15999
  mean =      1.998 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15147 
    [ 2.500,  5.000) = 571 
    [ 5.000,  7.500) = 87 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     21.574 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 3.028 ±(99.9%) 0.066 ms/op
Iteration   1: 2.018 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   1.905 ms/op
                 existUser·p0.90:   2.609 ms/op
                 existUser·p0.95:   2.814 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  19.803 ms/op
                 existUser·p0.9999: 20.311 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15828
  mean =      2.018 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13609 
    [ 2.500,  5.000) = 2138 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =     19.803 ms/op
     p(99.9900) =     20.311 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.082 ms/op
Iteration   1: 1.916 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   1.810 ms/op
                 getUser·p0.90:   2.380 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   3.122 ms/op
                 getUser·p0.999:  17.279 ms/op
                 getUser·p0.9999: 20.239 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16672
  mean =      1.916 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15633 
    [ 2.500,  5.000) = 954 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.122 ms/op
     p(99.9000) =     17.279 ms/op
     p(99.9900) =     20.239 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 4.801 ±(99.9%) 0.264 ms/op
Iteration   1: 3.736 ±(99.9%) 0.077 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   5.931 ms/op
                 listUser·p0.999:  37.618 ms/op
                 listUser·p0.9999: 38.207 ms/op
                 listUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8560
  mean =      3.736 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 503 
    [ 2.500,  5.000) = 7729 
    [ 5.000,  7.500) = 280 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     37.618 ms/op
     p(99.9900) =     38.207 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.127          ops/ms
ClientSimple.existUser                       thrpt         14.157          ops/ms
ClientSimple.getUser                         thrpt         12.047          ops/ms
ClientSimple.listUser                        thrpt          8.600          ops/ms
ClientSimple.createUser                       avgt          2.564           ms/op
ClientSimple.existUser                        avgt          2.053           ms/op
ClientSimple.getUser                          avgt          2.218           ms/op
ClientSimple.listUser                         avgt          3.572           ms/op
ClientSimple.createUser                     sample  15999   1.998 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.549           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.753           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.879           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.546           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.574           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.594           ms/op
ClientSimple.existUser                      sample  15828   2.018 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.462           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.905           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.814           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.555           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.803           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.311           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.349           ms/op
ClientSimple.getUser                        sample  16672   1.916 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.524           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.810           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.380           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.122           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.279           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.239           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.611           ms/op
ClientSimple.listUser                       sample   8560   3.736 ± 0.077   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.180           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.617           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.882           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.931           ms/op
ClientSimple.listUser:listUser·p0.999       sample         37.618           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         38.207           ms/op
ClientSimple.listUser:listUser·p1.00        sample         38.207           ms/op

Benchmark result is saved to 1721412316461.json
