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
# Warmup Iteration   1: 1.074 ops/ms
Iteration   1: 2.144 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.144 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.574 ops/ms
Iteration   1: 7.150 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.150 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.241 ops/ms
Iteration   1: 4.292 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.292 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.803 ops/ms
Iteration   1: 1.191 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.191 ops/ms


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
# Warmup Iteration   1: 18.484 ±(99.9%) 0.304 ms/op
Iteration   1: 8.428 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.428 ms/op


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
# Warmup Iteration   1: 7.923 ±(99.9%) 0.087 ms/op
Iteration   1: 4.410 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.410 ms/op


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
# Warmup Iteration   1: 13.596 ±(99.9%) 0.206 ms/op
Iteration   1: 5.098 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.098 ms/op


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
# Warmup Iteration   1: 31.306 ±(99.9%) 0.377 ms/op
Iteration   1: 19.258 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.258 ms/op


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
# Warmup Iteration   1: 11.841 ±(99.9%) 0.398 ms/op
Iteration   1: 7.908 ±(99.9%) 0.111 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   7.578 ms/op
                 createUser·p0.90:   8.405 ms/op
                 createUser·p0.95:   12.934 ms/op
                 createUser·p0.99:   17.783 ms/op
                 createUser·p0.999:  20.643 ms/op
                 createUser·p0.9999: 20.677 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4031
  mean =      7.908 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 124 
    [ 5.000,  7.500) = 1651 
    [ 7.500, 10.000) = 1960 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.195 ms/op
     p(50.0000) =      7.578 ms/op
     p(90.0000) =      8.405 ms/op
     p(95.0000) =     12.934 ms/op
     p(99.0000) =     17.783 ms/op
     p(99.9000) =     20.643 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 7.520 ±(99.9%) 0.295 ms/op
Iteration   1: 5.227 ±(99.9%) 0.126 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   5.587 ms/op
                 existUser·p0.95:   7.586 ms/op
                 existUser·p0.99:   16.313 ms/op
                 existUser·p0.999:  38.994 ms/op
                 existUser·p0.9999: 39.059 ms/op
                 existUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6183
  mean =      5.227 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 371 
    [ 2.500,  5.000) = 2634 
    [ 5.000,  7.500) = 2861 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     16.313 ms/op
     p(99.9000) =     38.994 ms/op
     p(99.9900) =     39.059 ms/op
     p(99.9990) =     39.059 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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
# Warmup Iteration   1: 11.847 ±(99.9%) 0.353 ms/op
Iteration   1: 5.029 ±(99.9%) 0.068 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.292 ms/op
                 getUser·p0.95:   7.119 ms/op
                 getUser·p0.99:   14.032 ms/op
                 getUser·p0.999:  17.453 ms/op
                 getUser·p0.9999: 17.564 ms/op
                 getUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6378
  mean =      5.029 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 15 
    [ 2.500,  3.750) = 672 
    [ 3.750,  5.000) = 2881 
    [ 5.000,  6.250) = 2160 
    [ 6.250,  7.500) = 458 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.292 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =     14.032 ms/op
     p(99.9000) =     17.453 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 26.407 ±(99.9%) 1.045 ms/op
Iteration   1: 21.536 ±(99.9%) 0.736 ms/op
                 listUser·p0.00:   11.174 ms/op
                 listUser·p0.50:   19.104 ms/op
                 listUser·p0.90:   31.031 ms/op
                 listUser·p0.95:   37.257 ms/op
                 listUser·p0.99:   64.487 ms/op
                 listUser·p0.999:  85.553 ms/op
                 listUser·p0.9999: 101.319 ms/op
                 listUser·p1.00:   101.319 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1484
  mean =     21.536 ±(99.9%) 0.736 ms/op

  Histogram, ms/op:
    [ 10.000,  20.000) = 973 
    [ 20.000,  30.000) = 350 
    [ 30.000,  40.000) = 96 
    [ 40.000,  50.000) = 30 
    [ 50.000,  60.000) = 11 
    [ 60.000,  70.000) = 23 
    [ 70.000,  80.000) = 0 
    [ 80.000,  90.000) = 0 
    [ 90.000, 100.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =     11.174 ms/op
     p(50.0000) =     19.104 ms/op
     p(90.0000) =     31.031 ms/op
     p(95.0000) =     37.257 ms/op
     p(99.0000) =     64.487 ms/op
     p(99.9000) =     85.553 ms/op
     p(99.9900) =    101.319 ms/op
     p(99.9990) =    101.319 ms/op
     p(99.9999) =    101.319 ms/op
    p(100.0000) =    101.319 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt    Score   Error   Units
Client.createUser                      thrpt          2.144          ops/ms
Client.existUser                       thrpt          7.150          ops/ms
Client.getUser                         thrpt          4.292          ops/ms
Client.listUser                        thrpt          1.191          ops/ms
Client.createUser                       avgt          8.428           ms/op
Client.existUser                        avgt          4.410           ms/op
Client.getUser                          avgt          5.098           ms/op
Client.listUser                         avgt         19.258           ms/op
Client.createUser                     sample  4031    7.908 ± 0.111   ms/op
Client.createUser:createUser·p0.00    sample          2.195           ms/op
Client.createUser:createUser·p0.50    sample          7.578           ms/op
Client.createUser:createUser·p0.90    sample          8.405           ms/op
Client.createUser:createUser·p0.95    sample         12.934           ms/op
Client.createUser:createUser·p0.99    sample         17.783           ms/op
Client.createUser:createUser·p0.999   sample         20.643           ms/op
Client.createUser:createUser·p0.9999  sample         20.677           ms/op
Client.createUser:createUser·p1.00    sample         20.677           ms/op
Client.existUser                      sample  6183    5.227 ± 0.126   ms/op
Client.existUser:existUser·p0.00      sample          0.745           ms/op
Client.existUser:existUser·p0.50      sample          5.014           ms/op
Client.existUser:existUser·p0.90      sample          5.587           ms/op
Client.existUser:existUser·p0.95      sample          7.586           ms/op
Client.existUser:existUser·p0.99      sample         16.313           ms/op
Client.existUser:existUser·p0.999     sample         38.994           ms/op
Client.existUser:existUser·p0.9999    sample         39.059           ms/op
Client.existUser:existUser·p1.00      sample         39.059           ms/op
Client.getUser                        sample  6378    5.029 ± 0.068   ms/op
Client.getUser:getUser·p0.00          sample          1.029           ms/op
Client.getUser:getUser·p0.50          sample          4.833           ms/op
Client.getUser:getUser·p0.90          sample          6.292           ms/op
Client.getUser:getUser·p0.95          sample          7.119           ms/op
Client.getUser:getUser·p0.99          sample         14.032           ms/op
Client.getUser:getUser·p0.999         sample         17.453           ms/op
Client.getUser:getUser·p0.9999        sample         17.564           ms/op
Client.getUser:getUser·p1.00          sample         17.564           ms/op
Client.listUser                       sample  1484   21.536 ± 0.736   ms/op
Client.listUser:listUser·p0.00        sample         11.174           ms/op
Client.listUser:listUser·p0.50        sample         19.104           ms/op
Client.listUser:listUser·p0.90        sample         31.031           ms/op
Client.listUser:listUser·p0.95        sample         37.257           ms/op
Client.listUser:listUser·p0.99        sample         64.487           ms/op
Client.listUser:listUser·p0.999       sample         85.553           ms/op
Client.listUser:listUser·p0.9999      sample        101.319           ms/op
Client.listUser:listUser·p1.00        sample        101.319           ms/op
