# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.179 ops/ms
Iteration   1: 5.775 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.775 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.964 ops/ms
Iteration   1: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.871 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.239 ops/ms
Iteration   1: 7.644 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.644 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.678 ops/ms
Iteration   1: 3.208 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.208 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.658 ±(99.9%) 0.086 ms/op
Iteration   1: 3.164 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.164 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ±(99.9%) 0.054 ms/op
Iteration   1: 2.066 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.066 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ±(99.9%) 0.051 ms/op
Iteration   1: 3.368 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.368 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.017 ±(99.9%) 0.222 ms/op
Iteration   1: 8.657 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.657 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.948 ±(99.9%) 0.117 ms/op
Iteration   1: 2.963 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   2.712 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.142 ms/op
                 createUser·p0.99:   8.234 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10796
  mean =      2.963 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 3066 
    [ 2.500,  3.750) = 6743 
    [ 3.750,  5.000) = 725 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.712 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.142 ms/op
     p(99.0000) =      8.234 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.219 ±(99.9%) 0.103 ms/op
Iteration   1: 2.053 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   1.942 ms/op
                 existUser·p0.90:   2.716 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   4.152 ms/op
                 existUser·p0.999:  5.120 ms/op
                 existUser·p0.9999: 6.610 ms/op
                 existUser·p1.00:   6.873 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15640
  mean =      2.053 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 4 
    [0.500, 1.000) = 33 
    [1.000, 1.500) = 1320 
    [1.500, 2.000) = 7283 
    [2.000, 2.500) = 4398 
    [2.500, 3.000) = 1870 
    [3.000, 3.500) = 466 
    [3.500, 4.000) = 87 
    [4.000, 4.500) = 52 
    [4.500, 5.000) = 80 
    [5.000, 5.500) = 43 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      4.152 ms/op
     p(99.9000) =      5.120 ms/op
     p(99.9900) =      6.610 ms/op
     p(99.9990) =      6.873 ms/op
     p(99.9999) =      6.873 ms/op
    p(100.0000) =      6.873 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.121 ms/op
Iteration   1: 2.930 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.892 ms/op
                 getUser·p0.90:   3.754 ms/op
                 getUser·p0.95:   4.052 ms/op
                 getUser·p0.99:   4.757 ms/op
                 getUser·p0.999:  6.374 ms/op
                 getUser·p0.9999: 7.353 ms/op
                 getUser·p1.00:   7.381 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10933
  mean =      2.930 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 25 
    [1.500, 2.000) = 380 
    [2.000, 2.500) = 2669 
    [2.500, 3.000) = 3327 
    [3.000, 3.500) = 2606 
    [3.500, 4.000) = 1320 
    [4.000, 4.500) = 442 
    [4.500, 5.000) = 82 
    [5.000, 5.500) = 55 
    [5.500, 6.000) = 10 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.754 ms/op
     p(95.0000) =      4.052 ms/op
     p(99.0000) =      4.757 ms/op
     p(99.9000) =      6.374 ms/op
     p(99.9900) =      7.353 ms/op
     p(99.9990) =      7.381 ms/op
     p(99.9999) =      7.381 ms/op
    p(100.0000) =      7.381 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.940 ±(99.9%) 0.320 ms/op
Iteration   1: 8.897 ±(99.9%) 0.248 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   8.266 ms/op
                 listUser·p0.90:   11.567 ms/op
                 listUser·p0.95:   13.128 ms/op
                 listUser·p0.99:   33.486 ms/op
                 listUser·p0.999:  49.586 ms/op
                 listUser·p0.9999: 50.790 ms/op
                 listUser·p1.00:   50.790 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3593
  mean =      8.897 ±(99.9%) 0.248 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 161 
    [ 5.000, 10.000) = 2599 
    [10.000, 15.000) = 740 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 20 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 17 
    [45.000, 50.000) = 14 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.400 ms/op
     p(50.0000) =      8.266 ms/op
     p(90.0000) =     11.567 ms/op
     p(95.0000) =     13.128 ms/op
     p(99.0000) =     33.486 ms/op
     p(99.9000) =     49.586 ms/op
     p(99.9900) =     50.790 ms/op
     p(99.9990) =     50.790 ms/op
     p(99.9999) =     50.790 ms/op
    p(100.0000) =     50.790 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.775          ops/ms
Client.existUser                       thrpt         12.871          ops/ms
Client.getUser                         thrpt          7.644          ops/ms
Client.listUser                        thrpt          3.208          ops/ms
Client.createUser                       avgt          3.164           ms/op
Client.existUser                        avgt          2.066           ms/op
Client.getUser                          avgt          3.368           ms/op
Client.listUser                         avgt          8.657           ms/op
Client.createUser                     sample  10796   2.963 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          0.878           ms/op
Client.createUser:createUser·p0.50    sample          2.712           ms/op
Client.createUser:createUser·p0.90    sample          3.670           ms/op
Client.createUser:createUser·p0.95    sample          4.142           ms/op
Client.createUser:createUser·p0.99    sample          8.234           ms/op
Client.createUser:createUser·p0.999   sample         17.105           ms/op
Client.createUser:createUser·p0.9999  sample         17.236           ms/op
Client.createUser:createUser·p1.00    sample         17.236           ms/op
Client.existUser                      sample  15640   2.053 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.484           ms/op
Client.existUser:existUser·p0.50      sample          1.942           ms/op
Client.existUser:existUser·p0.90      sample          2.716           ms/op
Client.existUser:existUser·p0.95      sample          2.978           ms/op
Client.existUser:existUser·p0.99      sample          4.152           ms/op
Client.existUser:existUser·p0.999     sample          5.120           ms/op
Client.existUser:existUser·p0.9999    sample          6.610           ms/op
Client.existUser:existUser·p1.00      sample          6.873           ms/op
Client.getUser                        sample  10933   2.930 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.941           ms/op
Client.getUser:getUser·p0.50          sample          2.892           ms/op
Client.getUser:getUser·p0.90          sample          3.754           ms/op
Client.getUser:getUser·p0.95          sample          4.052           ms/op
Client.getUser:getUser·p0.99          sample          4.757           ms/op
Client.getUser:getUser·p0.999         sample          6.374           ms/op
Client.getUser:getUser·p0.9999        sample          7.353           ms/op
Client.getUser:getUser·p1.00          sample          7.381           ms/op
Client.listUser                       sample   3593   8.897 ± 0.248   ms/op
Client.listUser:listUser·p0.00        sample          2.400           ms/op
Client.listUser:listUser·p0.50        sample          8.266           ms/op
Client.listUser:listUser·p0.90        sample         11.567           ms/op
Client.listUser:listUser·p0.95        sample         13.128           ms/op
Client.listUser:listUser·p0.99        sample         33.486           ms/op
Client.listUser:listUser·p0.999       sample         49.586           ms/op
Client.listUser:listUser·p0.9999      sample         50.790           ms/op
Client.listUser:listUser·p1.00        sample         50.790           ms/op
