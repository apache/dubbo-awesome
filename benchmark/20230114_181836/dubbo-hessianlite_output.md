# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.115 ops/ms
Iteration   1: 2.599 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.599 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 2.221 ops/ms
Iteration   1: 7.629 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.629 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.494 ops/ms
Iteration   1: 4.229 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.229 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.817 ops/ms
Iteration   1: 1.461 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.461 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 14.872 ±(99.9%) 0.293 ms/op
Iteration   1: 7.480 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.480 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.604 ±(99.9%) 0.082 ms/op
Iteration   1: 3.739 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.229 ±(99.9%) 0.126 ms/op
Iteration   1: 4.480 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.480 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 33.058 ±(99.9%) 0.408 ms/op
Iteration   1: 20.259 ±(99.9%) 0.129 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.259 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.928 ±(99.9%) 0.399 ms/op
Iteration   1: 5.714 ±(99.9%) 0.125 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   5.890 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   8.487 ms/op
                 createUser·p0.99:   20.382 ms/op
                 createUser·p0.999:  25.635 ms/op
                 createUser·p0.9999: 27.099 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5673
  mean =      5.714 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 2417 
    [ 5.000,  7.500) = 2862 
    [ 7.500, 10.000) = 203 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.322 ms/op
     p(50.0000) =      5.890 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     20.382 ms/op
     p(99.9000) =     25.635 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.790 ±(99.9%) 0.228 ms/op
Iteration   1: 4.314 ±(99.9%) 0.088 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   5.451 ms/op
                 existUser·p0.95:   9.191 ms/op
                 existUser·p0.99:   14.563 ms/op
                 existUser·p0.999:  15.345 ms/op
                 existUser·p0.9999: 15.368 ms/op
                 existUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7415
  mean =      4.314 ±(99.9%) 0.088 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 862 
    [ 2.500,  3.750) = 2526 
    [ 3.750,  5.000) = 3148 
    [ 5.000,  6.250) = 268 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.451 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     14.563 ms/op
     p(99.9000) =     15.345 ms/op
     p(99.9900) =     15.368 ms/op
     p(99.9990) =     15.368 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.691 ±(99.9%) 0.342 ms/op
Iteration   1: 4.638 ±(99.9%) 0.085 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   6.046 ms/op
                 getUser·p0.95:   7.217 ms/op
                 getUser·p0.99:   10.404 ms/op
                 getUser·p0.999:  29.524 ms/op
                 getUser·p0.9999: 29.557 ms/op
                 getUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6935
  mean =      4.638 ±(99.9%) 0.085 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 4738 
    [ 5.000,  7.500) = 1859 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     29.524 ms/op
     p(99.9900) =     29.557 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 28.264 ±(99.9%) 1.025 ms/op
Iteration   1: 19.995 ±(99.9%) 0.302 ms/op
                 listUser·p0.00:   5.104 ms/op
                 listUser·p0.50:   20.349 ms/op
                 listUser·p0.90:   22.544 ms/op
                 listUser·p0.95:   27.230 ms/op
                 listUser·p0.99:   31.708 ms/op
                 listUser·p0.999:  37.460 ms/op
                 listUser·p0.9999: 39.125 ms/op
                 listUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1604
  mean =     19.995 ±(99.9%) 0.302 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 436 
    [20.000, 22.500) = 772 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      5.104 ms/op
     p(50.0000) =     20.349 ms/op
     p(90.0000) =     22.544 ms/op
     p(95.0000) =     27.230 ms/op
     p(99.0000) =     31.708 ms/op
     p(99.9000) =     37.460 ms/op
     p(99.9900) =     39.125 ms/op
     p(99.9990) =     39.125 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.599          ops/ms
Client.existUser                       thrpt         7.629          ops/ms
Client.getUser                         thrpt         4.229          ops/ms
Client.listUser                        thrpt         1.461          ops/ms
Client.createUser                       avgt         7.480           ms/op
Client.existUser                        avgt         3.739           ms/op
Client.getUser                          avgt         4.480           ms/op
Client.listUser                         avgt        20.259           ms/op
Client.createUser                     sample  5673   5.714 ± 0.125   ms/op
Client.createUser:createUser·p0.00    sample         2.322           ms/op
Client.createUser:createUser·p0.50    sample         5.890           ms/op
Client.createUser:createUser·p0.90    sample         6.988           ms/op
Client.createUser:createUser·p0.95    sample         8.487           ms/op
Client.createUser:createUser·p0.99    sample        20.382           ms/op
Client.createUser:createUser·p0.999   sample        25.635           ms/op
Client.createUser:createUser·p0.9999  sample        27.099           ms/op
Client.createUser:createUser·p1.00    sample        27.099           ms/op
Client.existUser                      sample  7415   4.314 ± 0.088   ms/op
Client.existUser:existUser·p0.00      sample         0.786           ms/op
Client.existUser:existUser·p0.50      sample         3.858           ms/op
Client.existUser:existUser·p0.90      sample         5.451           ms/op
Client.existUser:existUser·p0.95      sample         9.191           ms/op
Client.existUser:existUser·p0.99      sample        14.563           ms/op
Client.existUser:existUser·p0.999     sample        15.345           ms/op
Client.existUser:existUser·p0.9999    sample        15.368           ms/op
Client.existUser:existUser·p1.00      sample        15.368           ms/op
Client.getUser                        sample  6935   4.638 ± 0.085   ms/op
Client.getUser:getUser·p0.00          sample         1.241           ms/op
Client.getUser:getUser·p0.50          sample         4.383           ms/op
Client.getUser:getUser·p0.90          sample         6.046           ms/op
Client.getUser:getUser·p0.95          sample         7.217           ms/op
Client.getUser:getUser·p0.99          sample        10.404           ms/op
Client.getUser:getUser·p0.999         sample        29.524           ms/op
Client.getUser:getUser·p0.9999        sample        29.557           ms/op
Client.getUser:getUser·p1.00          sample        29.557           ms/op
Client.listUser                       sample  1604  19.995 ± 0.302   ms/op
Client.listUser:listUser·p0.00        sample         5.104           ms/op
Client.listUser:listUser·p0.50        sample        20.349           ms/op
Client.listUser:listUser·p0.90        sample        22.544           ms/op
Client.listUser:listUser·p0.95        sample        27.230           ms/op
Client.listUser:listUser·p0.99        sample        31.708           ms/op
Client.listUser:listUser·p0.999       sample        37.460           ms/op
Client.listUser:listUser·p0.9999      sample        39.125           ms/op
Client.listUser:listUser·p1.00        sample        39.125           ms/op
