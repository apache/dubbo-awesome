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
# Warmup Iteration   1: 1.628 ops/ms
Iteration   1: 7.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.098 ops/ms


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
# Warmup Iteration   1: 6.615 ops/ms
Iteration   1: 12.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.686 ops/ms


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
# Warmup Iteration   1: 5.501 ops/ms
Iteration   1: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.021 ops/ms


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
# Warmup Iteration   1: 5.804 ops/ms
Iteration   1: 9.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.128 ops/ms


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.096 ms/op
Iteration   1: 2.081 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.081 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.055 ms/op
Iteration   1: 1.956 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.956 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.055 ms/op
Iteration   1: 2.049 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.049 ms/op


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
# Warmup Iteration   1: 4.532 ±(99.9%) 0.125 ms/op
Iteration   1: 3.952 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.952 ms/op


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
# Warmup Iteration   1: 3.481 ±(99.9%) 0.087 ms/op
Iteration   1: 2.535 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   2.269 ms/op
                 createUser·p0.90:   2.867 ms/op
                 createUser·p0.95:   3.583 ms/op
                 createUser·p0.99:   11.870 ms/op
                 createUser·p0.999:  25.277 ms/op
                 createUser·p0.9999: 25.706 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12606
  mean =      2.535 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9531 
    [ 2.500,  5.000) = 2601 
    [ 5.000,  7.500) = 244 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.583 ms/op
     p(99.0000) =     11.870 ms/op
     p(99.9000) =     25.277 ms/op
     p(99.9900) =     25.706 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 3.013 ±(99.9%) 0.080 ms/op
Iteration   1: 1.825 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   1.700 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   3.317 ms/op
                 existUser·p0.999:  12.882 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17516
  mean =      1.825 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1400 
    [ 1.250,  2.500) = 15018 
    [ 2.500,  3.750) = 958 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.317 ms/op
     p(99.9000) =     12.882 ms/op
     p(99.9900) =     13.468 ms/op
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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.103 ms/op
Iteration   1: 1.891 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   1.778 ms/op
                 getUser·p0.90:   2.437 ms/op
                 getUser·p0.95:   2.626 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  27.460 ms/op
                 getUser·p0.9999: 28.210 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16987
  mean =      1.891 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15592 
    [ 2.500,  5.000) = 1323 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =     27.460 ms/op
     p(99.9900) =     28.210 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.104 ms/op
Iteration   1: 3.730 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  7.224 ms/op
                 listUser·p0.9999: 8.061 ms/op
                 listUser·p1.00:   8.061 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8581
  mean =      3.730 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 31 
    [1.500, 2.000) = 152 
    [2.000, 2.500) = 326 
    [2.500, 3.000) = 582 
    [3.000, 3.500) = 1487 
    [3.500, 4.000) = 3213 
    [4.000, 4.500) = 2044 
    [4.500, 5.000) = 512 
    [5.000, 5.500) = 98 
    [5.500, 6.000) = 88 
    [6.000, 6.500) = 35 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 6 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =      7.224 ms/op
     p(99.9900) =      8.061 ms/op
     p(99.9990) =      8.061 ms/op
     p(99.9999) =      8.061 ms/op
    p(100.0000) =      8.061 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.098          ops/ms
ClientSimple.existUser                       thrpt         12.686          ops/ms
ClientSimple.getUser                         thrpt         13.021          ops/ms
ClientSimple.listUser                        thrpt          9.128          ops/ms
ClientSimple.createUser                       avgt          2.081           ms/op
ClientSimple.existUser                        avgt          1.956           ms/op
ClientSimple.getUser                          avgt          2.049           ms/op
ClientSimple.listUser                         avgt          3.952           ms/op
ClientSimple.createUser                     sample  12606   2.535 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.536           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.583           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.870           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.277           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.706           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.723           ms/op
ClientSimple.existUser                      sample  17516   1.825 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.583           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.700           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.317           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.882           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.468           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.468           ms/op
ClientSimple.getUser                        sample  16987   1.891 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.540           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.778           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.707           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.460           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.210           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.279           ms/op
ClientSimple.listUser                       sample   8581   3.730 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.083           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.789           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.751           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.224           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.061           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.061           ms/op

Benchmark result is saved to 1725170789033.json
