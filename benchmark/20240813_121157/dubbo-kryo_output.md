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
# Warmup Iteration   1: 1.910 ops/ms
Iteration   1: 6.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.769 ops/ms


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
# Warmup Iteration   1: 5.150 ops/ms
Iteration   1: 10.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.824 ops/ms


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
# Warmup Iteration   1: 6.068 ops/ms
Iteration   1: 14.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.139 ops/ms


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
# Warmup Iteration   1: 5.200 ops/ms
Iteration   1: 8.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.306 ops/ms


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.077 ms/op
Iteration   1: 2.282 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.282 ms/op


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
# Warmup Iteration   1: 3.031 ±(99.9%) 0.045 ms/op
Iteration   1: 1.864 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.864 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.053 ms/op
Iteration   1: 2.011 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.011 ms/op


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.081 ms/op
Iteration   1: 3.708 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.708 ms/op


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
# Warmup Iteration   1: 3.550 ±(99.9%) 0.100 ms/op
Iteration   1: 2.241 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.384 ms/op
                 createUser·p0.50:   2.081 ms/op
                 createUser·p0.90:   2.728 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   8.348 ms/op
                 createUser·p0.999:  16.298 ms/op
                 createUser·p0.9999: 16.991 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14276
  mean =      2.241 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 10905 
    [ 2.500,  3.750) = 2809 
    [ 3.750,  5.000) = 151 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.384 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     16.298 ms/op
     p(99.9900) =     16.991 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.095 ms/op
Iteration   1: 1.921 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.079 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 11.851 ms/op
                 existUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16919
  mean =      1.921 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 16001 
    [ 2.500,  3.750) = 632 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.079 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     11.851 ms/op
     p(99.9990) =     11.862 ms/op
     p(99.9999) =     11.862 ms/op
    p(100.0000) =     11.862 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.070 ms/op
Iteration   1: 1.912 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   1.802 ms/op
                 getUser·p0.90:   2.257 ms/op
                 getUser·p0.95:   2.482 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  11.059 ms/op
                 getUser·p0.9999: 11.177 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17039
  mean =      1.912 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 411 
    [ 1.250,  2.500) = 15810 
    [ 2.500,  3.750) = 588 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =     11.059 ms/op
     p(99.9900) =     11.177 ms/op
     p(99.9990) =     11.223 ms/op
     p(99.9999) =     11.223 ms/op
    p(100.0000) =     11.223 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.107 ms/op
Iteration   1: 3.457 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.449 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.513 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  23.315 ms/op
                 listUser·p0.9999: 24.347 ms/op
                 listUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9242
  mean =      3.457 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1501 
    [ 2.500,  5.000) = 7530 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.513 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     23.315 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.769          ops/ms
ClientSimple.existUser                       thrpt         10.824          ops/ms
ClientSimple.getUser                         thrpt         14.139          ops/ms
ClientSimple.listUser                        thrpt          8.306          ops/ms
ClientSimple.createUser                       avgt          2.282           ms/op
ClientSimple.existUser                        avgt          1.864           ms/op
ClientSimple.getUser                          avgt          2.011           ms/op
ClientSimple.listUser                         avgt          3.708           ms/op
ClientSimple.createUser                     sample  14276   2.241 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.384           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.081           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.348           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.298           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.991           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.334           ms/op
ClientSimple.existUser                      sample  16919   1.921 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.807           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.079           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.731           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.851           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.862           ms/op
ClientSimple.getUser                        sample  17039   1.912 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.555           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.802           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.257           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.301           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.059           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.177           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.223           ms/op
ClientSimple.listUser                       sample   9242   3.457 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.979           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.449           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.513           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.447           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.315           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.347           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.347           ms/op

Benchmark result is saved to 1723550852284.json
