# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.370 ops/ms
Iteration   1: 5.882 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.882 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.585 ops/ms
Iteration   1: 10.358 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.358 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ops/ms
Iteration   1: 8.751 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.751 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.418 ops/ms
Iteration   1: 3.697 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.697 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.611 ±(99.9%) 0.065 ms/op
Iteration   1: 3.103 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.103 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.301 ±(99.9%) 0.032 ms/op
Iteration   1: 1.787 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.787 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.942 ±(99.9%) 0.061 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.065 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.555 ±(99.9%) 0.240 ms/op
Iteration   1: 8.490 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.490 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.880 ±(99.9%) 0.114 ms/op
Iteration   1: 3.343 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   4.105 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   10.575 ms/op
                 createUser·p0.999:  18.940 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9558
  mean =      3.343 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1436 
    [ 2.500,  3.750) = 5964 
    [ 3.750,  5.000) = 1722 
    [ 5.000,  6.250) = 174 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      4.105 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =     10.575 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.062 ±(99.9%) 0.068 ms/op
Iteration   1: 1.983 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   1.911 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.757 ms/op
                 existUser·p0.99:   3.289 ms/op
                 existUser·p0.999:  7.430 ms/op
                 existUser·p0.9999: 7.983 ms/op
                 existUser·p1.00:   8.102 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16064
  mean =      1.983 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 68 
    [1.000, 1.500) = 1363 
    [1.500, 2.000) = 7833 
    [2.000, 2.500) = 5122 
    [2.500, 3.000) = 1329 
    [3.000, 3.500) = 245 
    [3.500, 4.000) = 48 
    [4.000, 4.500) = 14 
    [4.500, 5.000) = 3 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 19 
    [7.500, 8.000) = 12 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.289 ms/op
     p(99.9000) =      7.430 ms/op
     p(99.9900) =      7.983 ms/op
     p(99.9990) =      8.102 ms/op
     p(99.9999) =      8.102 ms/op
    p(100.0000) =      8.102 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.813 ±(99.9%) 0.124 ms/op
Iteration   1: 2.955 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.843 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.996 ms/op
                 getUser·p0.999:  16.140 ms/op
                 getUser·p0.9999: 16.351 ms/op
                 getUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10906
  mean =      2.955 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 2997 
    [ 2.500,  3.750) = 7098 
    [ 3.750,  5.000) = 649 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.996 ms/op
     p(99.9000) =     16.140 ms/op
     p(99.9900) =     16.351 ms/op
     p(99.9990) =     16.351 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.316 ±(99.9%) 0.373 ms/op
Iteration   1: 7.910 ±(99.9%) 0.132 ms/op
                 listUser·p0.00:   2.703 ms/op
                 listUser·p0.50:   7.487 ms/op
                 listUser·p0.90:   10.551 ms/op
                 listUser·p0.95:   12.108 ms/op
                 listUser·p0.99:   18.711 ms/op
                 listUser·p0.999:  25.186 ms/op
                 listUser·p0.9999: 26.313 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4047
  mean =      7.910 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 251 
    [ 5.000,  7.500) = 1788 
    [ 7.500, 10.000) = 1449 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.703 ms/op
     p(50.0000) =      7.487 ms/op
     p(90.0000) =     10.551 ms/op
     p(95.0000) =     12.108 ms/op
     p(99.0000) =     18.711 ms/op
     p(99.9000) =     25.186 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.882          ops/ms
Client.existUser                       thrpt         10.358          ops/ms
Client.getUser                         thrpt          8.751          ops/ms
Client.listUser                        thrpt          3.697          ops/ms
Client.createUser                       avgt          3.103           ms/op
Client.existUser                        avgt          1.787           ms/op
Client.getUser                          avgt          3.065           ms/op
Client.listUser                         avgt          8.490           ms/op
Client.createUser                     sample   9558   3.343 ± 0.055   ms/op
Client.createUser:createUser·p0.00    sample          1.354           ms/op
Client.createUser:createUser·p0.50    sample          2.941           ms/op
Client.createUser:createUser·p0.90    sample          4.105           ms/op
Client.createUser:createUser·p0.95    sample          4.768           ms/op
Client.createUser:createUser·p0.99    sample         10.575           ms/op
Client.createUser:createUser·p0.999   sample         18.940           ms/op
Client.createUser:createUser·p0.9999  sample         19.956           ms/op
Client.createUser:createUser·p1.00    sample         19.956           ms/op
Client.existUser                      sample  16064   1.983 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.507           ms/op
Client.existUser:existUser·p0.50      sample          1.911           ms/op
Client.existUser:existUser·p0.90      sample          2.515           ms/op
Client.existUser:existUser·p0.95      sample          2.757           ms/op
Client.existUser:existUser·p0.99      sample          3.289           ms/op
Client.existUser:existUser·p0.999     sample          7.430           ms/op
Client.existUser:existUser·p0.9999    sample          7.983           ms/op
Client.existUser:existUser·p1.00      sample          8.102           ms/op
Client.getUser                        sample  10906   2.955 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          0.945           ms/op
Client.getUser:getUser·p0.50          sample          2.843           ms/op
Client.getUser:getUser·p0.90          sample          3.625           ms/op
Client.getUser:getUser·p0.95          sample          3.916           ms/op
Client.getUser:getUser·p0.99          sample          5.996           ms/op
Client.getUser:getUser·p0.999         sample         16.140           ms/op
Client.getUser:getUser·p0.9999        sample         16.351           ms/op
Client.getUser:getUser·p1.00          sample         16.351           ms/op
Client.listUser                       sample   4047   7.910 ± 0.132   ms/op
Client.listUser:listUser·p0.00        sample          2.703           ms/op
Client.listUser:listUser·p0.50        sample          7.487           ms/op
Client.listUser:listUser·p0.90        sample         10.551           ms/op
Client.listUser:listUser·p0.95        sample         12.108           ms/op
Client.listUser:listUser·p0.99        sample         18.711           ms/op
Client.listUser:listUser·p0.999       sample         25.186           ms/op
Client.listUser:listUser·p0.9999      sample         26.313           ms/op
Client.listUser:listUser·p1.00        sample         26.313           ms/op
