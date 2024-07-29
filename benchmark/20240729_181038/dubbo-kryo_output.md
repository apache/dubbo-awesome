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
# Warmup Iteration   1: 1.475 ops/ms
Iteration   1: 7.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.411 ops/ms


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
# Warmup Iteration   1: 5.929 ops/ms
Iteration   1: 11.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.816 ops/ms


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
# Warmup Iteration   1: 4.531 ops/ms
Iteration   1: 11.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.810 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.382 ops/ms
Iteration   1: 7.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.594 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.295 ±(99.9%) 0.082 ms/op
Iteration   1: 2.199 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.199 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.691 ±(99.9%) 0.069 ms/op
Iteration   1: 1.893 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.893 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.073 ms/op
Iteration   1: 2.097 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.097 ms/op


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
# Warmup Iteration   1: 7.093 ±(99.9%) 0.145 ms/op
Iteration   1: 3.904 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.904 ms/op


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.121 ms/op
Iteration   1: 2.175 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.620 ms/op
                 createUser·p0.50:   1.968 ms/op
                 createUser·p0.90:   2.566 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  20.706 ms/op
                 createUser·p0.9999: 21.853 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14685
  mean =      2.175 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12769 
    [ 2.500,  5.000) = 1643 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.566 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     20.706 ms/op
     p(99.9900) =     21.853 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.072 ms/op
Iteration   1: 2.148 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.661 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  29.360 ms/op
                 existUser·p0.9999: 30.294 ms/op
                 existUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14882
  mean =      2.148 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12667 
    [ 2.500,  5.000) = 2069 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.661 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     29.360 ms/op
     p(99.9900) =     30.294 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.100 ms/op
Iteration   1: 2.446 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.372 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.367 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  11.259 ms/op
                 getUser·p0.9999: 11.414 ms/op
                 getUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13258
  mean =      2.446 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 7741 
    [ 2.500,  3.750) = 5048 
    [ 3.750,  5.000) = 239 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.372 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =     11.259 ms/op
     p(99.9900) =     11.414 ms/op
     p(99.9990) =     11.420 ms/op
     p(99.9999) =     11.420 ms/op
    p(100.0000) =     11.420 ms/op


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
# Warmup Iteration   1: 5.649 ±(99.9%) 0.164 ms/op
Iteration   1: 3.677 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   8.468 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 15.368 ms/op
                 listUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8712
  mean =      3.677 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 590 
    [ 2.500,  3.750) = 4860 
    [ 3.750,  5.000) = 2737 
    [ 5.000,  6.250) = 324 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      8.468 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     15.368 ms/op
     p(99.9990) =     15.368 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.411          ops/ms
ClientSimple.existUser                       thrpt         11.816          ops/ms
ClientSimple.getUser                         thrpt         11.810          ops/ms
ClientSimple.listUser                        thrpt          7.594          ops/ms
ClientSimple.createUser                       avgt          2.199           ms/op
ClientSimple.existUser                        avgt          1.893           ms/op
ClientSimple.getUser                          avgt          2.097           ms/op
ClientSimple.listUser                         avgt          3.904           ms/op
ClientSimple.createUser                     sample  14685   2.175 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.620           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.968           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.566           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.004           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.706           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.853           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.053           ms/op
ClientSimple.existUser                      sample  14882   2.148 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.426           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.661           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.986           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.956           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.360           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.294           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.310           ms/op
ClientSimple.getUser                        sample  13258   2.446 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.874           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.367           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.964           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.259           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.414           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.420           ms/op
ClientSimple.listUser                       sample   8712   3.677 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.145           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.588           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.169           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.468           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.860           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.368           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.368           ms/op

Benchmark result is saved to 1722276320245.json
