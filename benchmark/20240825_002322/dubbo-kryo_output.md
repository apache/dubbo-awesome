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
# Warmup Iteration   1: 1.907 ops/ms
Iteration   1: 7.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.067 ops/ms


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
# Warmup Iteration   1: 6.414 ops/ms
Iteration   1: 14.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.326 ops/ms


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
# Warmup Iteration   1: 6.702 ops/ms
Iteration   1: 13.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.417 ops/ms


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
# Warmup Iteration   1: 5.411 ops/ms
Iteration   1: 8.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.551 ops/ms


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.077 ms/op
Iteration   1: 2.344 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.344 ms/op


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
# Warmup Iteration   1: 2.965 ±(99.9%) 0.046 ms/op
Iteration   1: 1.720 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.720 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.055 ms/op
Iteration   1: 1.935 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.935 ms/op


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
# Warmup Iteration   1: 4.583 ±(99.9%) 0.112 ms/op
Iteration   1: 3.211 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.211 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.089 ms/op
Iteration   1: 2.219 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   2.009 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   2.732 ms/op
                 createUser·p0.99:   7.493 ms/op
                 createUser·p0.999:  28.336 ms/op
                 createUser·p0.9999: 29.461 ms/op
                 createUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14629
  mean =      2.219 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13109 
    [ 2.500,  5.000) = 1336 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      7.493 ms/op
     p(99.9000) =     28.336 ms/op
     p(99.9900) =     29.461 ms/op
     p(99.9990) =     30.310 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 3.240 ±(99.9%) 0.070 ms/op
Iteration   1: 2.043 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.434 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.818 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  11.928 ms/op
                 existUser·p0.9999: 12.356 ms/op
                 existUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15716
  mean =      2.043 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 13619 
    [ 2.500,  3.750) = 1882 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     12.356 ms/op
     p(99.9990) =     12.403 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


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
# Warmup Iteration   1: 3.383 ±(99.9%) 0.087 ms/op
Iteration   1: 1.880 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   1.706 ms/op
                 getUser·p0.90:   2.449 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  16.974 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17009
  mean =      1.880 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 343 
    [ 1.250,  2.500) = 15157 
    [ 2.500,  3.750) = 1323 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.332 ±(99.9%) 0.133 ms/op
Iteration   1: 3.313 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.269 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  7.307 ms/op
                 listUser·p0.9999: 7.741 ms/op
                 listUser·p1.00:   7.741 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9645
  mean =      3.313 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 12 
    [1.500, 2.000) = 149 
    [2.000, 2.500) = 545 
    [2.500, 3.000) = 2490 
    [3.000, 3.500) = 2996 
    [3.500, 4.000) = 2306 
    [4.000, 4.500) = 805 
    [4.500, 5.000) = 158 
    [5.000, 5.500) = 75 
    [5.500, 6.000) = 39 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =      7.741 ms/op
     p(99.9990) =      7.741 ms/op
     p(99.9999) =      7.741 ms/op
    p(100.0000) =      7.741 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.067          ops/ms
ClientSimple.existUser                       thrpt         14.326          ops/ms
ClientSimple.getUser                         thrpt         13.417          ops/ms
ClientSimple.listUser                        thrpt          8.551          ops/ms
ClientSimple.createUser                       avgt          2.344           ms/op
ClientSimple.existUser                        avgt          1.720           ms/op
ClientSimple.getUser                          avgt          1.935           ms/op
ClientSimple.listUser                         avgt          3.211           ms/op
ClientSimple.createUser                     sample  14629   2.219 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.424           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.009           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.493           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.336           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.461           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.310           ms/op
ClientSimple.existUser                      sample  15716   2.043 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.434           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.923           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.818           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.510           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.928           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.356           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.403           ms/op
ClientSimple.getUser                        sample  17009   1.880 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.748           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.706           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.449           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.858           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.974           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.072           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.072           ms/op
ClientSimple.listUser                       sample   9645   3.313 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.190           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.269           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.047           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.603           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.307           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.741           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.741           ms/op

Benchmark result is saved to 1724545124250.json
