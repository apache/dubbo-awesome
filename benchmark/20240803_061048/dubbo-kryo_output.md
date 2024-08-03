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
# Warmup Iteration   1: 1.848 ops/ms
Iteration   1: 6.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.662 ops/ms


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
# Warmup Iteration   1: 6.579 ops/ms
Iteration   1: 12.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.142 ops/ms


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
# Warmup Iteration   1: 5.831 ops/ms
Iteration   1: 12.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.380 ops/ms


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
# Warmup Iteration   1: 6.088 ops/ms
Iteration   1: 8.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.165 ops/ms


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.078 ms/op
Iteration   1: 2.227 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.227 ms/op


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
# Warmup Iteration   1: 3.011 ±(99.9%) 0.051 ms/op
Iteration   1: 1.699 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.699 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.052 ms/op
Iteration   1: 1.823 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.823 ms/op


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.088 ms/op
Iteration   1: 3.984 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.984 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.085 ms/op
Iteration   1: 2.208 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   1.870 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14460
  mean =      2.208 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10292 
    [ 2.500,  5.000) = 4022 
    [ 5.000,  7.500) = 82 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.085 ms/op
Iteration   1: 1.907 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   1.847 ms/op
                 existUser·p0.90:   2.490 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   3.068 ms/op
                 existUser·p0.999:  12.292 ms/op
                 existUser·p0.9999: 14.385 ms/op
                 existUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16758
  mean =      1.907 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 974 
    [ 1.250,  2.500) = 14195 
    [ 2.500,  3.750) = 1524 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.068 ms/op
     p(99.9000) =     12.292 ms/op
     p(99.9900) =     14.385 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.077 ms/op
Iteration   1: 1.916 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.503 ms/op
                 getUser·p0.50:   1.847 ms/op
                 getUser·p0.90:   2.367 ms/op
                 getUser·p0.95:   2.519 ms/op
                 getUser·p0.99:   3.322 ms/op
                 getUser·p0.999:  13.467 ms/op
                 getUser·p0.9999: 14.401 ms/op
                 getUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16674
  mean =      1.916 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 345 
    [ 1.250,  2.500) = 15426 
    [ 2.500,  3.750) = 775 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.322 ms/op
     p(99.9000) =     13.467 ms/op
     p(99.9900) =     14.401 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.369 ±(99.9%) 0.163 ms/op
Iteration   1: 3.632 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.658 ms/op
                 listUser·p0.99:   6.120 ms/op
                 listUser·p0.999:  28.213 ms/op
                 listUser·p0.9999: 38.339 ms/op
                 listUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8886
  mean =      3.632 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 679 
    [ 2.500,  5.000) = 7998 
    [ 5.000,  7.500) = 158 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.658 ms/op
     p(99.0000) =      6.120 ms/op
     p(99.9000) =     28.213 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.662          ops/ms
ClientSimple.existUser                       thrpt         12.142          ops/ms
ClientSimple.getUser                         thrpt         12.380          ops/ms
ClientSimple.listUser                        thrpt          8.165          ops/ms
ClientSimple.createUser                       avgt          2.227           ms/op
ClientSimple.existUser                        avgt          1.699           ms/op
ClientSimple.getUser                          avgt          1.823           ms/op
ClientSimple.listUser                         avgt          3.984           ms/op
ClientSimple.createUser                     sample  14460   2.208 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.758           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.870           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.277           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.014           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.709           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.775           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.775           ms/op
ClientSimple.existUser                      sample  16758   1.907 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.684           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.847           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.068           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.292           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.385           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.385           ms/op
ClientSimple.getUser                        sample  16674   1.916 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.503           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.847           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.367           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.322           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.467           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.401           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.500           ms/op
ClientSimple.listUser                       sample   8886   3.632 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.985           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.658           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.120           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.213           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         38.339           ms/op
ClientSimple.listUser:listUser·p1.00        sample         38.339           ms/op

Benchmark result is saved to 1722665174478.json
