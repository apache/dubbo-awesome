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
# Warmup Iteration   1: 1.803 ops/ms
Iteration   1: 7.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.030 ops/ms


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
# Warmup Iteration   1: 5.484 ops/ms
Iteration   1: 12.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.161 ops/ms


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
# Warmup Iteration   1: 4.775 ops/ms
Iteration   1: 12.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.727 ops/ms


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
# Warmup Iteration   1: 5.296 ops/ms
Iteration   1: 8.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.553 ops/ms


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.083 ms/op
Iteration   1: 2.326 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.326 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.054 ms/op
Iteration   1: 1.924 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.924 ms/op


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
# Warmup Iteration   1: 3.585 ±(99.9%) 0.076 ms/op
Iteration   1: 2.257 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.257 ms/op


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
# Warmup Iteration   1: 4.606 ±(99.9%) 0.103 ms/op
Iteration   1: 3.138 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.138 ms/op


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
# Warmup Iteration   1: 3.348 ±(99.9%) 0.089 ms/op
Iteration   1: 2.178 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.579 ms/op
                 createUser·p0.50:   1.913 ms/op
                 createUser·p0.90:   2.613 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   7.549 ms/op
                 createUser·p0.999:  17.084 ms/op
                 createUser·p0.9999: 17.322 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14628
  mean =      2.178 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 12785 
    [ 2.500,  3.750) = 1208 
    [ 3.750,  5.000) = 210 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      7.549 ms/op
     p(99.9000) =     17.084 ms/op
     p(99.9900) =     17.322 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.079 ms/op
Iteration   1: 2.179 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.311 ms/op
                 existUser·p0.50:   2.114 ms/op
                 existUser·p0.90:   2.695 ms/op
                 existUser·p0.95:   2.814 ms/op
                 existUser·p0.99:   3.218 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14808
  mean =      2.179 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 480 
    [ 1.250,  2.500) = 10980 
    [ 2.500,  3.750) = 3274 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 62 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.311 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      3.218 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 3.325 ±(99.9%) 0.082 ms/op
Iteration   1: 2.144 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.503 ms/op
                 getUser·p0.50:   1.995 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   4.198 ms/op
                 getUser·p0.999:  17.859 ms/op
                 getUser·p0.9999: 21.791 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14952
  mean =      2.144 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12893 
    [ 2.500,  5.000) = 1952 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      4.198 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.133 ms/op
Iteration   1: 3.373 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.318 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   5.648 ms/op
                 listUser·p0.999:  7.561 ms/op
                 listUser·p0.9999: 7.791 ms/op
                 listUser·p1.00:   7.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9475
  mean =      3.373 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 7 
    [1.500, 2.000) = 81 
    [2.000, 2.500) = 514 
    [2.500, 3.000) = 3193 
    [3.000, 3.500) = 1689 
    [3.500, 4.000) = 2337 
    [4.000, 4.500) = 1031 
    [4.500, 5.000) = 334 
    [5.000, 5.500) = 179 
    [5.500, 6.000) = 49 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 30 
    [7.000, 7.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.648 ms/op
     p(99.9000) =      7.561 ms/op
     p(99.9900) =      7.791 ms/op
     p(99.9990) =      7.791 ms/op
     p(99.9999) =      7.791 ms/op
    p(100.0000) =      7.791 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.030          ops/ms
ClientSimple.existUser                       thrpt         12.161          ops/ms
ClientSimple.getUser                         thrpt         12.727          ops/ms
ClientSimple.listUser                        thrpt          8.553          ops/ms
ClientSimple.createUser                       avgt          2.326           ms/op
ClientSimple.existUser                        avgt          1.924           ms/op
ClientSimple.getUser                          avgt          2.257           ms/op
ClientSimple.listUser                         avgt          3.138           ms/op
ClientSimple.createUser                     sample  14628   2.178 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.579           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.913           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.187           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.549           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.084           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.322           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.367           ms/op
ClientSimple.existUser                      sample  14808   2.179 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.311           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.114           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.814           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.218           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.367           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.465           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.465           ms/op
ClientSimple.getUser                        sample  14952   2.144 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.503           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.995           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.198           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.859           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.791           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.791           ms/op
ClientSimple.listUser                       sample   9475   3.373 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.921           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.318           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.648           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.561           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.791           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.791           ms/op

Benchmark result is saved to 1725150086291.json
