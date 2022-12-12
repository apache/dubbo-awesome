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
# Warmup Iteration   1: 1.022 ops/ms
Iteration   1: 3.387 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.387 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.584 ops/ms
Iteration   1: 9.680 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.680 ops/ms


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
# Warmup Iteration   1: 3.005 ops/ms
Iteration   1: 5.527 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.527 ops/ms


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
# Warmup Iteration   1: 1.034 ops/ms
Iteration   1: 1.445 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.445 ops/ms


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
# Warmup Iteration   1: 14.935 ±(99.9%) 0.250 ms/op
Iteration   1: 6.468 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.468 ms/op


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
# Warmup Iteration   1: 6.576 ±(99.9%) 0.070 ms/op
Iteration   1: 3.345 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.345 ms/op


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
# Warmup Iteration   1: 6.962 ±(99.9%) 0.082 ms/op
Iteration   1: 4.087 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.087 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 27.131 ±(99.9%) 0.459 ms/op
Iteration   1: 15.201 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.201 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.783 ±(99.9%) 0.267 ms/op
Iteration   1: 4.834 ±(99.9%) 0.089 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   4.702 ms/op
                 createUser·p0.90:   5.997 ms/op
                 createUser·p0.95:   7.329 ms/op
                 createUser·p0.99:   14.073 ms/op
                 createUser·p0.999:  24.379 ms/op
                 createUser·p0.9999: 24.543 ms/op
                 createUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6606
  mean =      4.834 ±(99.9%) 0.089 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 380 
    [ 2.500,  5.000) = 4815 
    [ 5.000,  7.500) = 1093 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      5.997 ms/op
     p(95.0000) =      7.329 ms/op
     p(99.0000) =     14.073 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     24.543 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 7.164 ±(99.9%) 0.205 ms/op
Iteration   1: 3.404 ±(99.9%) 0.065 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   6.545 ms/op
                 existUser·p0.99:   10.699 ms/op
                 existUser·p0.999:  24.150 ms/op
                 existUser·p0.9999: 24.248 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9520
  mean =      3.404 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2004 
    [ 2.500,  5.000) = 6926 
    [ 5.000,  7.500) = 227 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     24.150 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 7.304 ±(99.9%) 0.270 ms/op
Iteration   1: 4.297 ±(99.9%) 0.050 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.127 ms/op
                 getUser·p0.95:   6.259 ms/op
                 getUser·p0.99:   10.240 ms/op
                 getUser·p0.999:  14.713 ms/op
                 getUser·p0.9999: 15.188 ms/op
                 getUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7431
  mean =      4.297 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 122 
    [ 2.500,  3.750) = 2020 
    [ 3.750,  5.000) = 4458 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 189 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      5.127 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     15.188 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 22.470 ±(99.9%) 0.760 ms/op
Iteration   1: 14.780 ±(99.9%) 0.285 ms/op
                 listUser·p0.00:   6.095 ms/op
                 listUser·p0.50:   14.074 ms/op
                 listUser·p0.90:   20.578 ms/op
                 listUser·p0.95:   24.216 ms/op
                 listUser·p0.99:   29.101 ms/op
                 listUser·p0.999:  39.290 ms/op
                 listUser·p0.9999: 39.780 ms/op
                 listUser·p1.00:   39.780 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2190
  mean =     14.780 ±(99.9%) 0.285 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 1246 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      6.095 ms/op
     p(50.0000) =     14.074 ms/op
     p(90.0000) =     20.578 ms/op
     p(95.0000) =     24.216 ms/op
     p(99.0000) =     29.101 ms/op
     p(99.9000) =     39.290 ms/op
     p(99.9900) =     39.780 ms/op
     p(99.9990) =     39.780 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.387          ops/ms
Client.existUser                       thrpt         9.680          ops/ms
Client.getUser                         thrpt         5.527          ops/ms
Client.listUser                        thrpt         1.445          ops/ms
Client.createUser                       avgt         6.468           ms/op
Client.existUser                        avgt         3.345           ms/op
Client.getUser                          avgt         4.087           ms/op
Client.listUser                         avgt        15.201           ms/op
Client.createUser                     sample  6606   4.834 ± 0.089   ms/op
Client.createUser:createUser·p0.00    sample         0.872           ms/op
Client.createUser:createUser·p0.50    sample         4.702           ms/op
Client.createUser:createUser·p0.90    sample         5.997           ms/op
Client.createUser:createUser·p0.95    sample         7.329           ms/op
Client.createUser:createUser·p0.99    sample        14.073           ms/op
Client.createUser:createUser·p0.999   sample        24.379           ms/op
Client.createUser:createUser·p0.9999  sample        24.543           ms/op
Client.createUser:createUser·p1.00    sample        24.543           ms/op
Client.existUser                      sample  9520   3.404 ± 0.065   ms/op
Client.existUser:existUser·p0.00      sample         0.689           ms/op
Client.existUser:existUser·p0.50      sample         2.966           ms/op
Client.existUser:existUser·p0.90      sample         4.440           ms/op
Client.existUser:existUser·p0.95      sample         6.545           ms/op
Client.existUser:existUser·p0.99      sample        10.699           ms/op
Client.existUser:existUser·p0.999     sample        24.150           ms/op
Client.existUser:existUser·p0.9999    sample        24.248           ms/op
Client.existUser:existUser·p1.00      sample        24.248           ms/op
Client.getUser                        sample  7431   4.297 ± 0.050   ms/op
Client.getUser:getUser·p0.00          sample         1.782           ms/op
Client.getUser:getUser·p0.50          sample         4.145           ms/op
Client.getUser:getUser·p0.90          sample         5.127           ms/op
Client.getUser:getUser·p0.95          sample         6.259           ms/op
Client.getUser:getUser·p0.99          sample        10.240           ms/op
Client.getUser:getUser·p0.999         sample        14.713           ms/op
Client.getUser:getUser·p0.9999        sample        15.188           ms/op
Client.getUser:getUser·p1.00          sample        15.188           ms/op
Client.listUser                       sample  2190  14.780 ± 0.285   ms/op
Client.listUser:listUser·p0.00        sample         6.095           ms/op
Client.listUser:listUser·p0.50        sample        14.074           ms/op
Client.listUser:listUser·p0.90        sample        20.578           ms/op
Client.listUser:listUser·p0.95        sample        24.216           ms/op
Client.listUser:listUser·p0.99        sample        29.101           ms/op
Client.listUser:listUser·p0.999       sample        39.290           ms/op
Client.listUser:listUser·p0.9999      sample        39.780           ms/op
Client.listUser:listUser·p1.00        sample        39.780           ms/op
