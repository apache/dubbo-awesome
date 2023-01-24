# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.801 ops/ms
Iteration   1: 1.425 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.425 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 1.946 ops/ms
Iteration   1: 5.567 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.567 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.281 ops/ms
Iteration   1: 3.417 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.417 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 0.692 ops/ms
Iteration   1: 0.955 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.955 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 27.283 ±(99.9%) 0.551 ms/op
Iteration   1: 13.210 ±(99.9%) 0.056 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  13.210 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.808 ±(99.9%) 0.214 ms/op
Iteration   1: 6.354 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.354 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.487 ±(99.9%) 0.223 ms/op
Iteration   1: 6.422 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.422 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 35.603 ±(99.9%) 0.664 ms/op
Iteration   1: 26.256 ±(99.9%) 0.244 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  26.256 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.383 ±(99.9%) 0.856 ms/op
Iteration   1: 10.634 ±(99.9%) 0.265 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   8.978 ms/op
                 createUser·p0.90:   16.209 ms/op
                 createUser·p0.95:   22.643 ms/op
                 createUser·p0.99:   27.886 ms/op
                 createUser·p0.999:  29.029 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3056
  mean =     10.634 ±(99.9%) 0.265 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 17 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 2176 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      8.978 ms/op
     p(90.0000) =     16.209 ms/op
     p(95.0000) =     22.643 ms/op
     p(99.0000) =     27.886 ms/op
     p(99.9000) =     29.029 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.923 ±(99.9%) 0.527 ms/op
Iteration   1: 6.362 ±(99.9%) 0.119 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   5.882 ms/op
                 existUser·p0.90:   7.471 ms/op
                 existUser·p0.95:   8.438 ms/op
                 existUser·p0.99:   20.746 ms/op
                 existUser·p0.999:  28.884 ms/op
                 existUser·p0.9999: 29.196 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 5088
  mean =      6.362 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 216 
    [ 5.000,  7.500) = 4304 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      5.882 ms/op
     p(90.0000) =      7.471 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     20.746 ms/op
     p(99.9000) =     28.884 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 15.605 ±(99.9%) 0.601 ms/op
Iteration   1: 6.186 ±(99.9%) 0.320 ms/op
                 getUser·p0.00:   2.101 ms/op
                 getUser·p0.50:   5.415 ms/op
                 getUser·p0.90:   6.332 ms/op
                 getUser·p0.95:   7.436 ms/op
                 getUser·p0.99:   27.830 ms/op
                 getUser·p0.999:  98.566 ms/op
                 getUser·p0.9999: 119.144 ms/op
                 getUser·p1.00:   119.144 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5270
  mean =      6.186 ±(99.9%) 0.320 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 5174 
    [ 12.500,  25.000) = 29 
    [ 25.000,  37.500) = 35 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 14 
    [ 87.500, 100.000) = 15 
    [100.000, 112.500) = 1 
    [112.500, 125.000) = 2 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.436 ms/op
     p(99.0000) =     27.830 ms/op
     p(99.9000) =     98.566 ms/op
     p(99.9900) =    119.144 ms/op
     p(99.9990) =    119.144 ms/op
     p(99.9999) =    119.144 ms/op
    p(100.0000) =    119.144 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 33.929 ±(99.9%) 1.262 ms/op
Iteration   1: 22.330 ±(99.9%) 0.460 ms/op
                 listUser·p0.00:   6.676 ms/op
                 listUser·p0.50:   20.808 ms/op
                 listUser·p0.90:   30.409 ms/op
                 listUser·p0.95:   33.325 ms/op
                 listUser·p0.99:   39.377 ms/op
                 listUser·p0.999:  49.202 ms/op
                 listUser·p0.9999: 49.938 ms/op
                 listUser·p1.00:   49.938 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1431
  mean =     22.330 ±(99.9%) 0.460 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 1 
    [10.000, 15.000) = 41 
    [15.000, 20.000) = 372 
    [20.000, 25.000) = 718 
    [25.000, 30.000) = 147 
    [30.000, 35.000) = 115 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      6.676 ms/op
     p(50.0000) =     20.808 ms/op
     p(90.0000) =     30.409 ms/op
     p(95.0000) =     33.325 ms/op
     p(99.0000) =     39.377 ms/op
     p(99.9000) =     49.202 ms/op
     p(99.9900) =     49.938 ms/op
     p(99.9990) =     49.938 ms/op
     p(99.9999) =     49.938 ms/op
    p(100.0000) =     49.938 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt    Score   Error   Units
Client.createUser                      thrpt          1.425          ops/ms
Client.existUser                       thrpt          5.567          ops/ms
Client.getUser                         thrpt          3.417          ops/ms
Client.listUser                        thrpt          0.955          ops/ms
Client.createUser                       avgt         13.210           ms/op
Client.existUser                        avgt          6.354           ms/op
Client.getUser                          avgt          6.422           ms/op
Client.listUser                         avgt         26.256           ms/op
Client.createUser                     sample  3056   10.634 ± 0.265   ms/op
Client.createUser:createUser·p0.00    sample          1.397           ms/op
Client.createUser:createUser·p0.50    sample          8.978           ms/op
Client.createUser:createUser·p0.90    sample         16.209           ms/op
Client.createUser:createUser·p0.95    sample         22.643           ms/op
Client.createUser:createUser·p0.99    sample         27.886           ms/op
Client.createUser:createUser·p0.999   sample         29.029           ms/op
Client.createUser:createUser·p0.9999  sample         29.164           ms/op
Client.createUser:createUser·p1.00    sample         29.164           ms/op
Client.existUser                      sample  5088    6.362 ± 0.119   ms/op
Client.existUser:existUser·p0.00      sample          1.149           ms/op
Client.existUser:existUser·p0.50      sample          5.882           ms/op
Client.existUser:existUser·p0.90      sample          7.471           ms/op
Client.existUser:existUser·p0.95      sample          8.438           ms/op
Client.existUser:existUser·p0.99      sample         20.746           ms/op
Client.existUser:existUser·p0.999     sample         28.884           ms/op
Client.existUser:existUser·p0.9999    sample         29.196           ms/op
Client.existUser:existUser·p1.00      sample         29.196           ms/op
Client.getUser                        sample  5270    6.186 ± 0.320   ms/op
Client.getUser:getUser·p0.00          sample          2.101           ms/op
Client.getUser:getUser·p0.50          sample          5.415           ms/op
Client.getUser:getUser·p0.90          sample          6.332           ms/op
Client.getUser:getUser·p0.95          sample          7.436           ms/op
Client.getUser:getUser·p0.99          sample         27.830           ms/op
Client.getUser:getUser·p0.999         sample         98.566           ms/op
Client.getUser:getUser·p0.9999        sample        119.144           ms/op
Client.getUser:getUser·p1.00          sample        119.144           ms/op
Client.listUser                       sample  1431   22.330 ± 0.460   ms/op
Client.listUser:listUser·p0.00        sample          6.676           ms/op
Client.listUser:listUser·p0.50        sample         20.808           ms/op
Client.listUser:listUser·p0.90        sample         30.409           ms/op
Client.listUser:listUser·p0.95        sample         33.325           ms/op
Client.listUser:listUser·p0.99        sample         39.377           ms/op
Client.listUser:listUser·p0.999       sample         49.202           ms/op
Client.listUser:listUser·p0.9999      sample         49.938           ms/op
Client.listUser:listUser·p1.00        sample         49.938           ms/op
