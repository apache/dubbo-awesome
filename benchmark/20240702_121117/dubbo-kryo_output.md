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
# Warmup Iteration   1: 1.504 ops/ms
Iteration   1: 6.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.968 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.297 ops/ms
Iteration   1: 11.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.314 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.410 ops/ms
Iteration   1: 11.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.311 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.469 ops/ms
Iteration   1: 8.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.296 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ±(99.9%) 0.143 ms/op
Iteration   1: 2.162 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.162 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.144 ±(99.9%) 0.052 ms/op
Iteration   1: 1.821 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.821 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ±(99.9%) 0.061 ms/op
Iteration   1: 1.993 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.993 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.510 ±(99.9%) 0.091 ms/op
Iteration   1: 3.379 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.379 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.509 ±(99.9%) 0.098 ms/op
Iteration   1: 2.494 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   2.277 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   9.547 ms/op
                 createUser·p0.999:  30.048 ms/op
                 createUser·p0.9999: 31.409 ms/op
                 createUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12815
  mean =      2.494 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8837 
    [ 2.500,  5.000) = 3684 
    [ 5.000,  7.500) = 156 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      9.547 ms/op
     p(99.9000) =     30.048 ms/op
     p(99.9900) =     31.409 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 3.173 ±(99.9%) 0.070 ms/op
Iteration   1: 1.862 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.810 ms/op
                 existUser·p0.99:   4.369 ms/op
                 existUser·p0.999:  26.083 ms/op
                 existUser·p0.9999: 26.364 ms/op
                 existUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17166
  mean =      1.862 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15664 
    [ 2.500,  5.000) = 1422 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      4.369 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     26.364 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.164 ms/op
Iteration   1: 2.119 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.810 ms/op
                 getUser·p0.95:   3.006 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  14.664 ms/op
                 getUser·p0.9999: 15.450 ms/op
                 getUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15137
  mean =      2.119 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 11997 
    [ 2.500,  3.750) = 2819 
    [ 3.750,  5.000) = 148 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     15.450 ms/op
     p(99.9990) =     15.466 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 4.770 ±(99.9%) 0.163 ms/op
Iteration   1: 3.535 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.631 ms/op
                 listUser·p0.50:   3.387 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   11.613 ms/op
                 listUser·p0.999:  15.810 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9209
  mean =      3.535 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 344 
    [ 2.500,  3.750) = 6018 
    [ 3.750,  5.000) = 2535 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =     11.613 ms/op
     p(99.9000) =     15.810 ms/op
     p(99.9900) =     16.597 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.968          ops/ms
ClientSimple.existUser                       thrpt         11.314          ops/ms
ClientSimple.getUser                         thrpt         11.311          ops/ms
ClientSimple.listUser                        thrpt          8.296          ops/ms
ClientSimple.createUser                       avgt          2.162           ms/op
ClientSimple.existUser                        avgt          1.821           ms/op
ClientSimple.getUser                          avgt          1.993           ms/op
ClientSimple.listUser                         avgt          3.379           ms/op
ClientSimple.createUser                     sample  12815   2.494 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.819           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.277           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.580           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.547           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.048           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.409           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.621           ms/op
ClientSimple.existUser                      sample  17166   1.862 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.800           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.638           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.369           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.083           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.364           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.411           ms/op
ClientSimple.getUser                        sample  15137   2.119 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.810           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.006           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.317           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.664           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.450           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.466           ms/op
ClientSimple.listUser                       sample   9209   3.535 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.631           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.387           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.613           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.810           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.597           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.597           ms/op

Benchmark result is saved to 1719922024280.json
