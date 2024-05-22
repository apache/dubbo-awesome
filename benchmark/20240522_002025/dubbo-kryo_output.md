# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.131 ops/ms
Iteration   1: 5.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.052 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ops/ms
Iteration   1: 9.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.958 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.563 ops/ms
Iteration   1: 9.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.228 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.282 ops/ms
Iteration   1: 6.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  6.887 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.431 ±(99.9%) 0.144 ms/op
Iteration   1: 2.667 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.667 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.791 ±(99.9%) 0.069 ms/op
Iteration   1: 2.209 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.209 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.984 ±(99.9%) 0.105 ms/op
Iteration   1: 2.505 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.505 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.611 ±(99.9%) 0.123 ms/op
Iteration   1: 4.073 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.073 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ±(99.9%) 0.120 ms/op
Iteration   1: 2.475 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.310 ms/op
                 createUser·p0.90:   2.940 ms/op
                 createUser·p0.95:   3.643 ms/op
                 createUser·p0.99:   7.133 ms/op
                 createUser·p0.999:  16.578 ms/op
                 createUser·p0.9999: 26.172 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13072
  mean =      2.475 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9127 
    [ 2.500,  5.000) = 3659 
    [ 5.000,  7.500) = 163 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      2.310 ms/op
     p(90.0000) =      2.940 ms/op
     p(95.0000) =      3.643 ms/op
     p(99.0000) =      7.133 ms/op
     p(99.9000) =     16.578 ms/op
     p(99.9900) =     26.172 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.837 ±(99.9%) 0.093 ms/op
Iteration   1: 2.152 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   1.937 ms/op
                 existUser·p0.90:   2.793 ms/op
                 existUser·p0.95:   3.228 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  26.320 ms/op
                 existUser·p0.9999: 26.724 ms/op
                 existUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14779
  mean =      2.152 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11943 
    [ 2.500,  5.000) = 2668 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     26.320 ms/op
     p(99.9900) =     26.724 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.326 ±(99.9%) 0.141 ms/op
Iteration   1: 2.261 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.114 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.432 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  14.330 ms/op
                 getUser·p0.9999: 14.851 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14178
  mean =      2.261 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 187 
    [ 1.250,  2.500) = 10323 
    [ 2.500,  3.750) = 3223 
    [ 3.750,  5.000) = 325 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.432 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =     14.330 ms/op
     p(99.9900) =     14.851 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.069 ±(99.9%) 0.165 ms/op
Iteration   1: 4.307 ±(99.9%) 0.073 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   4.182 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  23.683 ms/op
                 listUser·p0.9999: 24.576 ms/op
                 listUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7412
  mean =      4.307 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 218 
    [ 2.500,  5.000) = 6296 
    [ 5.000,  7.500) = 776 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      4.182 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     23.683 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:01:28

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.052          ops/ms
ClientSimple.existUser                       thrpt          9.958          ops/ms
ClientSimple.getUser                         thrpt          9.228          ops/ms
ClientSimple.listUser                        thrpt          6.887          ops/ms
ClientSimple.createUser                       avgt          2.667           ms/op
ClientSimple.existUser                        avgt          2.209           ms/op
ClientSimple.getUser                          avgt          2.505           ms/op
ClientSimple.listUser                         avgt          4.073           ms/op
ClientSimple.createUser                     sample  13072   2.475 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.986           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.310           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.940           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.643           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.133           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.578           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.172           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.182           ms/op
ClientSimple.existUser                      sample  14779   2.152 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.528           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.937           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.793           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.228           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.546           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.320           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.724           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.771           ms/op
ClientSimple.getUser                        sample  14178   2.261 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.984           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.114           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.432           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.727           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.330           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.851           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.926           ms/op
ClientSimple.listUser                       sample   7412   4.307 ± 0.073   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.292           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.079           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.159           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.683           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.576           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.576           ms/op

Benchmark result is saved to 1716336912498.json
