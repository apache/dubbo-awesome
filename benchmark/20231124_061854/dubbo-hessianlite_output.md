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
# Warmup Iteration   1: 2.353 ops/ms
Iteration   1: 5.891 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.891 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.570 ops/ms
Iteration   1: 12.023 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.023 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.781 ops/ms
Iteration   1: 8.851 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.851 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.360 ops/ms
Iteration   1: 3.858 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.858 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.072 ±(99.9%) 0.063 ms/op
Iteration   1: 2.989 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.989 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.943 ±(99.9%) 0.034 ms/op
Iteration   1: 1.787 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.787 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.247 ±(99.9%) 0.063 ms/op
Iteration   1: 3.083 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.083 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.331 ±(99.9%) 0.234 ms/op
Iteration   1: 8.260 ±(99.9%) 0.104 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.260 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.957 ±(99.9%) 0.092 ms/op
Iteration   1: 2.980 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.818 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  14.504 ms/op
                 createUser·p0.9999: 16.252 ms/op
                 createUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10738
  mean =      2.980 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 2503 
    [ 2.500,  3.750) = 7360 
    [ 3.750,  5.000) = 752 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     14.504 ms/op
     p(99.9900) =     16.252 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.972 ±(99.9%) 0.055 ms/op
Iteration   1: 1.740 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   1.640 ms/op
                 existUser·p0.90:   2.114 ms/op
                 existUser·p0.95:   2.314 ms/op
                 existUser·p0.99:   3.056 ms/op
                 existUser·p0.999:  13.396 ms/op
                 existUser·p0.9999: 14.306 ms/op
                 existUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18379
  mean =      1.740 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 530 
    [ 1.250,  2.500) = 17370 
    [ 2.500,  3.750) = 343 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      1.640 ms/op
     p(90.0000) =      2.114 ms/op
     p(95.0000) =      2.314 ms/op
     p(99.0000) =      3.056 ms/op
     p(99.9000) =     13.396 ms/op
     p(99.9900) =     14.306 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.226 ±(99.9%) 0.089 ms/op
Iteration   1: 2.682 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  13.009 ms/op
                 getUser·p0.9999: 13.713 ms/op
                 getUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12013
  mean =      2.682 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 6048 
    [ 2.500,  3.750) = 5438 
    [ 3.750,  5.000) = 358 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.207 ±(99.9%) 0.391 ms/op
Iteration   1: 8.376 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   8.012 ms/op
                 listUser·p0.90:   11.321 ms/op
                 listUser·p0.95:   12.413 ms/op
                 listUser·p0.99:   15.254 ms/op
                 listUser·p0.999:  20.077 ms/op
                 listUser·p0.9999: 26.083 ms/op
                 listUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3827
  mean =      8.376 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 109 
    [ 5.000,  7.500) = 1466 
    [ 7.500, 10.000) = 1395 
    [10.000, 12.500) = 672 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.073 ms/op
     p(50.0000) =      8.012 ms/op
     p(90.0000) =     11.321 ms/op
     p(95.0000) =     12.413 ms/op
     p(99.0000) =     15.254 ms/op
     p(99.9000) =     20.077 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.891          ops/ms
Client.existUser                       thrpt         12.023          ops/ms
Client.getUser                         thrpt          8.851          ops/ms
Client.listUser                        thrpt          3.858          ops/ms
Client.createUser                       avgt          2.989           ms/op
Client.existUser                        avgt          1.787           ms/op
Client.getUser                          avgt          3.083           ms/op
Client.listUser                         avgt          8.260           ms/op
Client.createUser                     sample  10738   2.980 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.055           ms/op
Client.createUser:createUser·p0.50    sample          2.818           ms/op
Client.createUser:createUser·p0.90    sample          3.662           ms/op
Client.createUser:createUser·p0.95    sample          3.981           ms/op
Client.createUser:createUser·p0.99    sample          5.399           ms/op
Client.createUser:createUser·p0.999   sample         14.504           ms/op
Client.createUser:createUser·p0.9999  sample         16.252           ms/op
Client.createUser:createUser·p1.00    sample         16.318           ms/op
Client.existUser                      sample  18379   1.740 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.570           ms/op
Client.existUser:existUser·p0.50      sample          1.640           ms/op
Client.existUser:existUser·p0.90      sample          2.114           ms/op
Client.existUser:existUser·p0.95      sample          2.314           ms/op
Client.existUser:existUser·p0.99      sample          3.056           ms/op
Client.existUser:existUser·p0.999     sample         13.396           ms/op
Client.existUser:existUser·p0.9999    sample         14.306           ms/op
Client.existUser:existUser·p1.00      sample         14.320           ms/op
Client.getUser                        sample  12013   2.682 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.810           ms/op
Client.getUser:getUser·p0.50          sample          2.494           ms/op
Client.getUser:getUser·p0.90          sample          3.375           ms/op
Client.getUser:getUser·p0.95          sample          3.645           ms/op
Client.getUser:getUser·p0.99          sample          5.284           ms/op
Client.getUser:getUser·p0.999         sample         13.009           ms/op
Client.getUser:getUser·p0.9999        sample         13.713           ms/op
Client.getUser:getUser·p1.00          sample         13.763           ms/op
Client.listUser                       sample   3827   8.376 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          2.073           ms/op
Client.listUser:listUser·p0.50        sample          8.012           ms/op
Client.listUser:listUser·p0.90        sample         11.321           ms/op
Client.listUser:listUser·p0.95        sample         12.413           ms/op
Client.listUser:listUser·p0.99        sample         15.254           ms/op
Client.listUser:listUser·p0.999       sample         20.077           ms/op
Client.listUser:listUser·p0.9999      sample         26.083           ms/op
Client.listUser:listUser·p1.00        sample         26.083           ms/op
