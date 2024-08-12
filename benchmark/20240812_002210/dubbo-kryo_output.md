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
# Warmup Iteration   1: 1.929 ops/ms
Iteration   1: 6.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.624 ops/ms


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
# Warmup Iteration   1: 6.276 ops/ms
Iteration   1: 13.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.938 ops/ms


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
# Warmup Iteration   1: 5.050 ops/ms
Iteration   1: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.547 ops/ms


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
# Warmup Iteration   1: 3.995 ops/ms
Iteration   1: 8.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.603 ops/ms


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
# Warmup Iteration   1: 3.458 ±(99.9%) 0.056 ms/op
Iteration   1: 2.152 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.152 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.058 ms/op
Iteration   1: 1.780 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.780 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.056 ms/op
Iteration   1: 2.024 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.024 ms/op


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.084 ms/op
Iteration   1: 3.366 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.366 ms/op


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.091 ms/op
Iteration   1: 2.048 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   1.847 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.874 ms/op
                 createUser·p0.99:   10.355 ms/op
                 createUser·p0.999:  16.034 ms/op
                 createUser·p0.9999: 20.537 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15666
  mean =      2.048 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13146 
    [ 2.500,  5.000) = 2294 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.874 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     16.034 ms/op
     p(99.9900) =     20.537 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.869 ±(99.9%) 0.068 ms/op
Iteration   1: 2.013 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.541 ms/op
                 existUser·p0.50:   1.898 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  30.999 ms/op
                 existUser·p0.9999: 31.687 ms/op
                 existUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15880
  mean =      2.013 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14883 
    [ 2.500,  5.000) = 930 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =     30.999 ms/op
     p(99.9900) =     31.687 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 3.058 ±(99.9%) 0.072 ms/op
Iteration   1: 1.922 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   1.827 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   3.277 ms/op
                 getUser·p0.999:  11.409 ms/op
                 getUser·p0.9999: 12.300 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16629
  mean =      1.922 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 484 
    [ 1.250,  2.500) = 14917 
    [ 2.500,  3.750) = 1120 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =     11.409 ms/op
     p(99.9900) =     12.300 ms/op
     p(99.9990) =     12.485 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.147 ms/op
Iteration   1: 3.275 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.248 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.305 ms/op
                 listUser·p0.99:   5.213 ms/op
                 listUser·p0.999:  6.627 ms/op
                 listUser·p0.9999: 8.126 ms/op
                 listUser·p1.00:   8.126 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9768
  mean =      3.275 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 57 
    [2.000, 2.500) = 882 
    [2.500, 3.000) = 3219 
    [3.000, 3.500) = 1570 
    [3.500, 4.000) = 2804 
    [4.000, 4.500) = 944 
    [4.500, 5.000) = 155 
    [5.000, 5.500) = 71 
    [5.500, 6.000) = 32 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 6 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.305 ms/op
     p(99.0000) =      5.213 ms/op
     p(99.9000) =      6.627 ms/op
     p(99.9900) =      8.126 ms/op
     p(99.9990) =      8.126 ms/op
     p(99.9999) =      8.126 ms/op
    p(100.0000) =      8.126 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.624          ops/ms
ClientSimple.existUser                       thrpt         13.938          ops/ms
ClientSimple.getUser                         thrpt         10.547          ops/ms
ClientSimple.listUser                        thrpt          8.603          ops/ms
ClientSimple.createUser                       avgt          2.152           ms/op
ClientSimple.existUser                        avgt          1.780           ms/op
ClientSimple.getUser                          avgt          2.024           ms/op
ClientSimple.listUser                         avgt          3.366           ms/op
ClientSimple.createUser                     sample  15666   2.048 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.671           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.847           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.874           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.355           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.034           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.537           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.611           ms/op
ClientSimple.existUser                      sample  15880   2.013 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.541           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.898           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.030           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.999           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.687           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.687           ms/op
ClientSimple.getUser                        sample  16629   1.922 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.648           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.827           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.277           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.409           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.300           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.485           ms/op
ClientSimple.listUser                       sample   9768   3.275 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.020           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.248           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.305           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.213           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.627           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.126           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.126           ms/op

Benchmark result is saved to 1723421853937.json
