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
# Warmup Iteration   1: 2.604 ops/ms
Iteration   1: 6.846 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.846 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 6.413 ops/ms
Iteration   1: 14.603 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.603 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.654 ops/ms
Iteration   1: 9.460 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.460 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.485 ops/ms
Iteration   1: 3.828 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.828 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.006 ±(99.9%) 0.065 ms/op
Iteration   1: 2.829 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.829 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.905 ±(99.9%) 0.028 ms/op
Iteration   1: 1.850 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.850 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.395 ±(99.9%) 0.045 ms/op
Iteration   1: 2.967 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.967 ms/op


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
# Warmup Iteration   1: 11.654 ±(99.9%) 0.245 ms/op
Iteration   1: 7.586 ±(99.9%) 0.104 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.586 ms/op


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
# Warmup Iteration   1: 4.986 ±(99.9%) 0.099 ms/op
Iteration   1: 2.971 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   2.740 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   4.013 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  17.465 ms/op
                 createUser·p0.9999: 19.836 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11026
  mean =      2.971 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2246 
    [ 2.500,  3.750) = 7910 
    [ 3.750,  5.000) = 690 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.013 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     19.836 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 2.898 ±(99.9%) 0.063 ms/op
Iteration   1: 1.855 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.400 ms/op
                 existUser·p0.99:   3.183 ms/op
                 existUser·p0.999:  5.028 ms/op
                 existUser·p0.9999: 5.378 ms/op
                 existUser·p1.00:   5.390 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17282
  mean =      1.855 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 76 
    [1.000, 1.500) = 2086 
    [1.500, 2.000) = 10359 
    [2.000, 2.500) = 4220 
    [2.500, 3.000) = 350 
    [3.000, 3.500) = 65 
    [3.500, 4.000) = 10 
    [4.000, 4.500) = 46 
    [4.500, 5.000) = 49 
    [5.000, 5.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      3.183 ms/op
     p(99.9000) =      5.028 ms/op
     p(99.9900) =      5.378 ms/op
     p(99.9990) =      5.390 ms/op
     p(99.9999) =      5.390 ms/op
    p(100.0000) =      5.390 ms/op


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.113 ms/op
Iteration   1: 2.809 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   2.654 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  19.386 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11386
  mean =      2.809 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 4213 
    [ 2.500,  3.750) = 6447 
    [ 3.750,  5.000) = 526 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     19.386 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 10.475 ±(99.9%) 0.356 ms/op
Iteration   1: 6.764 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   6.488 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   16.033 ms/op
                 listUser·p0.999:  25.049 ms/op
                 listUser·p0.9999: 27.296 ms/op
                 listUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4739
  mean =      6.764 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 503 
    [ 5.000,  7.500) = 3109 
    [ 7.500, 10.000) = 958 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.322 ms/op
     p(50.0000) =      6.488 ms/op
     p(90.0000) =      8.520 ms/op
     p(95.0000) =      9.503 ms/op
     p(99.0000) =     16.033 ms/op
     p(99.9000) =     25.049 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.846          ops/ms
Client.existUser                       thrpt         14.603          ops/ms
Client.getUser                         thrpt          9.460          ops/ms
Client.listUser                        thrpt          3.828          ops/ms
Client.createUser                       avgt          2.829           ms/op
Client.existUser                        avgt          1.850           ms/op
Client.getUser                          avgt          2.967           ms/op
Client.listUser                         avgt          7.586           ms/op
Client.createUser                     sample  11026   2.971 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          1.178           ms/op
Client.createUser:createUser·p0.50    sample          2.740           ms/op
Client.createUser:createUser·p0.90    sample          3.613           ms/op
Client.createUser:createUser·p0.95    sample          4.013           ms/op
Client.createUser:createUser·p0.99    sample          7.553           ms/op
Client.createUser:createUser·p0.999   sample         17.465           ms/op
Client.createUser:createUser·p0.9999  sample         19.836           ms/op
Client.createUser:createUser·p1.00    sample         19.890           ms/op
Client.existUser                      sample  17282   1.855 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.591           ms/op
Client.existUser:existUser·p0.50      sample          1.821           ms/op
Client.existUser:existUser·p0.90      sample          2.273           ms/op
Client.existUser:existUser·p0.95      sample          2.400           ms/op
Client.existUser:existUser·p0.99      sample          3.183           ms/op
Client.existUser:existUser·p0.999     sample          5.028           ms/op
Client.existUser:existUser·p0.9999    sample          5.378           ms/op
Client.existUser:existUser·p1.00      sample          5.390           ms/op
Client.getUser                        sample  11386   2.809 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          0.827           ms/op
Client.getUser:getUser·p0.50          sample          2.654           ms/op
Client.getUser:getUser·p0.90          sample          3.527           ms/op
Client.getUser:getUser·p0.95          sample          3.850           ms/op
Client.getUser:getUser·p0.99          sample          5.972           ms/op
Client.getUser:getUser·p0.999         sample         19.386           ms/op
Client.getUser:getUser·p0.9999        sample         19.497           ms/op
Client.getUser:getUser·p1.00          sample         19.497           ms/op
Client.listUser                       sample   4739   6.764 ± 0.099   ms/op
Client.listUser:listUser·p0.00        sample          2.322           ms/op
Client.listUser:listUser·p0.50        sample          6.488           ms/op
Client.listUser:listUser·p0.90        sample          8.520           ms/op
Client.listUser:listUser·p0.95        sample          9.503           ms/op
Client.listUser:listUser·p0.99        sample         16.033           ms/op
Client.listUser:listUser·p0.999       sample         25.049           ms/op
Client.listUser:listUser·p0.9999      sample         27.296           ms/op
Client.listUser:listUser·p1.00        sample         27.296           ms/op
