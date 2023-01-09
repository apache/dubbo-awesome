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
# Warmup Iteration   1: 1.216 ops/ms
Iteration   1: 2.905 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.905 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.330 ops/ms
Iteration   1: 5.335 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.335 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.448 ops/ms
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
# Warmup Iteration   1: 0.879 ops/ms
Iteration   1: 1.421 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.421 ops/ms


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
# Warmup Iteration   1: 18.370 ±(99.9%) 0.245 ms/op
Iteration   1: 7.351 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.351 ms/op


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
# Warmup Iteration   1: 7.387 ±(99.9%) 0.068 ms/op
Iteration   1: 4.478 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.478 ms/op


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
# Warmup Iteration   1: 10.747 ±(99.9%) 0.164 ms/op
Iteration   1: 5.285 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.285 ms/op


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
# Warmup Iteration   1: 25.830 ±(99.9%) 0.301 ms/op
Iteration   1: 17.197 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.197 ms/op


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
# Warmup Iteration   1: 11.759 ±(99.9%) 0.314 ms/op
Iteration   1: 7.176 ±(99.9%) 0.164 ms/op
                 createUser·p0.00:   2.732 ms/op
                 createUser·p0.50:   6.726 ms/op
                 createUser·p0.90:   7.160 ms/op
                 createUser·p0.95:   7.545 ms/op
                 createUser·p0.99:   20.677 ms/op
                 createUser·p0.999:  45.780 ms/op
                 createUser·p0.9999: 45.941 ms/op
                 createUser·p1.00:   45.941 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4458
  mean =      7.176 ±(99.9%) 0.164 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 33 
    [ 5.000, 10.000) = 4277 
    [10.000, 15.000) = 52 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.732 ms/op
     p(50.0000) =      6.726 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      7.545 ms/op
     p(99.0000) =     20.677 ms/op
     p(99.9000) =     45.780 ms/op
     p(99.9900) =     45.941 ms/op
     p(99.9990) =     45.941 ms/op
     p(99.9999) =     45.941 ms/op
    p(100.0000) =     45.941 ms/op


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
# Warmup Iteration   1: 7.048 ±(99.9%) 0.204 ms/op
Iteration   1: 4.119 ±(99.9%) 0.074 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   8.328 ms/op
                 existUser·p0.99:   12.485 ms/op
                 existUser·p0.999:  17.334 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7841
  mean =      4.119 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1225 
    [ 2.500,  5.000) = 5913 
    [ 5.000,  7.500) = 254 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      8.328 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 12.312 ±(99.9%) 0.407 ms/op
Iteration   1: 4.859 ±(99.9%) 0.066 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   10.797 ms/op
                 getUser·p0.999:  24.459 ms/op
                 getUser·p0.9999: 24.871 ms/op
                 getUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6578
  mean =      4.859 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 4863 
    [ 5.000,  7.500) = 1539 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     24.459 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 28.065 ±(99.9%) 1.066 ms/op
Iteration   1: 19.860 ±(99.9%) 0.402 ms/op
                 listUser·p0.00:   6.111 ms/op
                 listUser·p0.50:   18.842 ms/op
                 listUser·p0.90:   21.692 ms/op
                 listUser·p0.95:   27.099 ms/op
                 listUser·p0.99:   44.785 ms/op
                 listUser·p0.999:  55.436 ms/op
                 listUser·p0.9999: 55.640 ms/op
                 listUser·p1.00:   55.640 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1623
  mean =     19.860 ±(99.9%) 0.402 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 37 
    [10.000, 15.000) = 59 
    [15.000, 20.000) = 1013 
    [20.000, 25.000) = 420 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      6.111 ms/op
     p(50.0000) =     18.842 ms/op
     p(90.0000) =     21.692 ms/op
     p(95.0000) =     27.099 ms/op
     p(99.0000) =     44.785 ms/op
     p(99.9000) =     55.436 ms/op
     p(99.9900) =     55.640 ms/op
     p(99.9990) =     55.640 ms/op
     p(99.9999) =     55.640 ms/op
    p(100.0000) =     55.640 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.905          ops/ms
Client.existUser                       thrpt         5.335          ops/ms
Client.getUser                         thrpt         4.229          ops/ms
Client.listUser                        thrpt         1.421          ops/ms
Client.createUser                       avgt         7.351           ms/op
Client.existUser                        avgt         4.478           ms/op
Client.getUser                          avgt         5.285           ms/op
Client.listUser                         avgt        17.197           ms/op
Client.createUser                     sample  4458   7.176 ± 0.164   ms/op
Client.createUser:createUser·p0.00    sample         2.732           ms/op
Client.createUser:createUser·p0.50    sample         6.726           ms/op
Client.createUser:createUser·p0.90    sample         7.160           ms/op
Client.createUser:createUser·p0.95    sample         7.545           ms/op
Client.createUser:createUser·p0.99    sample        20.677           ms/op
Client.createUser:createUser·p0.999   sample        45.780           ms/op
Client.createUser:createUser·p0.9999  sample        45.941           ms/op
Client.createUser:createUser·p1.00    sample        45.941           ms/op
Client.existUser                      sample  7841   4.119 ± 0.074   ms/op
Client.existUser:existUser·p0.00      sample         0.687           ms/op
Client.existUser:existUser·p0.50      sample         4.071           ms/op
Client.existUser:existUser·p0.90      sample         4.891           ms/op
Client.existUser:existUser·p0.95      sample         8.328           ms/op
Client.existUser:existUser·p0.99      sample        12.485           ms/op
Client.existUser:existUser·p0.999     sample        17.334           ms/op
Client.existUser:existUser·p0.9999    sample        21.234           ms/op
Client.existUser:existUser·p1.00      sample        21.234           ms/op
Client.getUser                        sample  6578   4.859 ± 0.066   ms/op
Client.getUser:getUser·p0.00          sample         1.618           ms/op
Client.getUser:getUser·p0.50          sample         4.628           ms/op
Client.getUser:getUser·p0.90          sample         5.554           ms/op
Client.getUser:getUser·p0.95          sample         6.111           ms/op
Client.getUser:getUser·p0.99          sample        10.797           ms/op
Client.getUser:getUser·p0.999         sample        24.459           ms/op
Client.getUser:getUser·p0.9999        sample        24.871           ms/op
Client.getUser:getUser·p1.00          sample        24.871           ms/op
Client.listUser                       sample  1623  19.860 ± 0.402   ms/op
Client.listUser:listUser·p0.00        sample         6.111           ms/op
Client.listUser:listUser·p0.50        sample        18.842           ms/op
Client.listUser:listUser·p0.90        sample        21.692           ms/op
Client.listUser:listUser·p0.95        sample        27.099           ms/op
Client.listUser:listUser·p0.99        sample        44.785           ms/op
Client.listUser:listUser·p0.999       sample        55.436           ms/op
Client.listUser:listUser·p0.9999      sample        55.640           ms/op
Client.listUser:listUser·p1.00        sample        55.640           ms/op
