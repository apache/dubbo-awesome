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
# Warmup Iteration   1: 1.604 ops/ms
Iteration   1: 7.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.873 ops/ms


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
# Warmup Iteration   1: 6.201 ops/ms
Iteration   1: 11.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.164 ops/ms


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
# Warmup Iteration   1: 5.049 ops/ms
Iteration   1: 11.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.947 ops/ms


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
# Warmup Iteration   1: 4.070 ops/ms
Iteration   1: 8.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.276 ops/ms


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.080 ms/op
Iteration   1: 2.347 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.347 ms/op


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
# Warmup Iteration   1: 3.198 ±(99.9%) 0.055 ms/op
Iteration   1: 1.875 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.875 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.059 ms/op
Iteration   1: 2.006 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.006 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.081 ms/op
Iteration   1: 3.603 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.603 ms/op


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
# Warmup Iteration   1: 3.507 ±(99.9%) 0.098 ms/op
Iteration   1: 2.250 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.557 ms/op
                 createUser·p0.50:   2.077 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.748 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  40.763 ms/op
                 createUser·p0.9999: 41.597 ms/op
                 createUser·p1.00:   41.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14252
  mean =      2.250 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14088 
    [ 5.000, 10.000) = 36 
    [10.000, 15.000) = 88 
    [15.000, 20.000) = 8 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     40.763 ms/op
     p(99.9900) =     41.597 ms/op
     p(99.9990) =     41.681 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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
# Warmup Iteration   1: 3.023 ±(99.9%) 0.065 ms/op
Iteration   1: 1.911 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.352 ms/op
                 existUser·p0.99:   4.775 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 12.719 ms/op
                 existUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16756
  mean =      1.911 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 262 
    [ 1.250,  2.500) = 15929 
    [ 2.500,  3.750) = 315 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.352 ms/op
     p(99.0000) =      4.775 ms/op
     p(99.9000) =     12.583 ms/op
     p(99.9900) =     12.719 ms/op
     p(99.9990) =     12.730 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


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
# Warmup Iteration   1: 3.462 ±(99.9%) 0.113 ms/op
Iteration   1: 2.271 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.255 ms/op
                 getUser·p0.90:   2.867 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   4.253 ms/op
                 getUser·p0.999:  15.827 ms/op
                 getUser·p0.9999: 16.017 ms/op
                 getUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14082
  mean =      2.271 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 360 
    [ 1.250,  2.500) = 9254 
    [ 2.500,  3.750) = 4302 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.255 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      4.253 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     16.017 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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
# Warmup Iteration   1: 4.771 ±(99.9%) 0.144 ms/op
Iteration   1: 3.746 ±(99.9%) 0.059 ms/op
                 listUser·p0.00:   0.759 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  26.640 ms/op
                 listUser·p0.9999: 27.886 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8534
  mean =      3.746 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 522 
    [ 2.500,  5.000) = 7637 
    [ 5.000,  7.500) = 310 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     26.640 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.873          ops/ms
ClientSimple.existUser                       thrpt         11.164          ops/ms
ClientSimple.getUser                         thrpt         11.947          ops/ms
ClientSimple.listUser                        thrpt          8.276          ops/ms
ClientSimple.createUser                       avgt          2.347           ms/op
ClientSimple.existUser                        avgt          1.875           ms/op
ClientSimple.getUser                          avgt          2.006           ms/op
ClientSimple.listUser                         avgt          3.603           ms/op
ClientSimple.createUser                     sample  14252   2.250 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.557           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.077           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.636           ms/op
ClientSimple.createUser:createUser·p0.999   sample         40.763           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         41.597           ms/op
ClientSimple.createUser:createUser·p1.00    sample         41.681           ms/op
ClientSimple.existUser                      sample  16756   1.911 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.709           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.784           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.208           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.352           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.775           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.583           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.719           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.730           ms/op
ClientSimple.getUser                        sample  14082   2.271 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.584           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.255           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.056           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.253           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.827           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.017           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.024           ms/op
ClientSimple.listUser                       sample   8534   3.746 ± 0.059   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.759           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.703           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.619           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.640           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.886           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.886           ms/op

Benchmark result is saved to 1725343567654.json
