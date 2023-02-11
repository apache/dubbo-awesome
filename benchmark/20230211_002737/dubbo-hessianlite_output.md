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
# Warmup Iteration   1: 0.774 ops/ms
Iteration   1: 1.698 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.698 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.950 ops/ms
Iteration   1: 5.225 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.225 ops/ms


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
# Warmup Iteration   1: 1.206 ops/ms
Iteration   1: 3.342 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.342 ops/ms


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
# Warmup Iteration   1: 0.735 ops/ms
Iteration   1: 0.986 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.986 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 23.644 ±(99.9%) 0.509 ms/op
Iteration   1: 10.738 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  10.738 ms/op


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
# Warmup Iteration   1: 13.016 ±(99.9%) 0.206 ms/op
Iteration   1: 6.164 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.164 ms/op


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
# Warmup Iteration   1: 15.928 ±(99.9%) 0.342 ms/op
Iteration   1: 6.323 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.323 ms/op


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
# Warmup Iteration   1: 33.597 ±(99.9%) 0.799 ms/op
Iteration   1: 24.719 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  24.719 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.734 ±(99.9%) 0.732 ms/op
Iteration   1: 9.524 ±(99.9%) 0.230 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   9.028 ms/op
                 createUser·p0.90:   10.486 ms/op
                 createUser·p0.95:   16.884 ms/op
                 createUser·p0.99:   26.935 ms/op
                 createUser·p0.999:  36.647 ms/op
                 createUser·p0.9999: 37.028 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3404
  mean =      9.524 ±(99.9%) 0.230 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 36 
    [ 5.000,  7.500) = 555 
    [ 7.500, 10.000) = 2274 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      9.028 ms/op
     p(90.0000) =     10.486 ms/op
     p(95.0000) =     16.884 ms/op
     p(99.0000) =     26.935 ms/op
     p(99.9000) =     36.647 ms/op
     p(99.9900) =     37.028 ms/op
     p(99.9990) =     37.028 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 9.888 ±(99.9%) 0.322 ms/op
Iteration   1: 5.173 ±(99.9%) 0.134 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   8.298 ms/op
                 existUser·p0.95:   10.338 ms/op
                 existUser·p0.99:   28.312 ms/op
                 existUser·p0.999:  34.981 ms/op
                 existUser·p0.9999: 36.700 ms/op
                 existUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6235
  mean =      5.173 ±(99.9%) 0.134 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 296 
    [ 2.500,  5.000) = 4665 
    [ 5.000,  7.500) = 609 
    [ 7.500, 10.000) = 324 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      8.298 ms/op
     p(95.0000) =     10.338 ms/op
     p(99.0000) =     28.312 ms/op
     p(99.9000) =     34.981 ms/op
     p(99.9900) =     36.700 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 14.780 ±(99.9%) 0.586 ms/op
Iteration   1: 5.190 ±(99.9%) 0.114 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   4.661 ms/op
                 getUser·p0.90:   6.503 ms/op
                 getUser·p0.95:   8.364 ms/op
                 getUser·p0.99:   21.030 ms/op
                 getUser·p0.999:  25.843 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6221
  mean =      5.190 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 4018 
    [ 5.000,  7.500) = 1672 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.503 ms/op
     p(95.0000) =      8.364 ms/op
     p(99.0000) =     21.030 ms/op
     p(99.9000) =     25.843 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 38.345 ±(99.9%) 1.219 ms/op
Iteration   1: 21.487 ±(99.9%) 0.522 ms/op
                 listUser·p0.00:   5.136 ms/op
                 listUser·p0.50:   19.595 ms/op
                 listUser·p0.90:   31.031 ms/op
                 listUser·p0.95:   34.931 ms/op
                 listUser·p0.99:   42.726 ms/op
                 listUser·p0.999:  50.560 ms/op
                 listUser·p0.9999: 51.315 ms/op
                 listUser·p1.00:   51.315 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1500
  mean =     21.487 ±(99.9%) 0.522 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 13 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 771 
    [20.000, 25.000) = 436 
    [25.000, 30.000) = 84 
    [30.000, 35.000) = 97 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 23 
    [45.000, 50.000) = 11 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      5.136 ms/op
     p(50.0000) =     19.595 ms/op
     p(90.0000) =     31.031 ms/op
     p(95.0000) =     34.931 ms/op
     p(99.0000) =     42.726 ms/op
     p(99.9000) =     50.560 ms/op
     p(99.9900) =     51.315 ms/op
     p(99.9990) =     51.315 ms/op
     p(99.9999) =     51.315 ms/op
    p(100.0000) =     51.315 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.698          ops/ms
Client.existUser                       thrpt         5.225          ops/ms
Client.getUser                         thrpt         3.342          ops/ms
Client.listUser                        thrpt         0.986          ops/ms
Client.createUser                       avgt        10.738           ms/op
Client.existUser                        avgt         6.164           ms/op
Client.getUser                          avgt         6.323           ms/op
Client.listUser                         avgt        24.719           ms/op
Client.createUser                     sample  3404   9.524 ± 0.230   ms/op
Client.createUser:createUser·p0.00    sample         0.857           ms/op
Client.createUser:createUser·p0.50    sample         9.028           ms/op
Client.createUser:createUser·p0.90    sample        10.486           ms/op
Client.createUser:createUser·p0.95    sample        16.884           ms/op
Client.createUser:createUser·p0.99    sample        26.935           ms/op
Client.createUser:createUser·p0.999   sample        36.647           ms/op
Client.createUser:createUser·p0.9999  sample        37.028           ms/op
Client.createUser:createUser·p1.00    sample        37.028           ms/op
Client.existUser                      sample  6235   5.173 ± 0.134   ms/op
Client.existUser:existUser·p0.00      sample         1.057           ms/op
Client.existUser:existUser·p0.50      sample         4.702           ms/op
Client.existUser:existUser·p0.90      sample         8.298           ms/op
Client.existUser:existUser·p0.95      sample        10.338           ms/op
Client.existUser:existUser·p0.99      sample        28.312           ms/op
Client.existUser:existUser·p0.999     sample        34.981           ms/op
Client.existUser:existUser·p0.9999    sample        36.700           ms/op
Client.existUser:existUser·p1.00      sample        36.700           ms/op
Client.getUser                        sample  6221   5.190 ± 0.114   ms/op
Client.getUser:getUser·p0.00          sample         1.262           ms/op
Client.getUser:getUser·p0.50          sample         4.661           ms/op
Client.getUser:getUser·p0.90          sample         6.503           ms/op
Client.getUser:getUser·p0.95          sample         8.364           ms/op
Client.getUser:getUser·p0.99          sample        21.030           ms/op
Client.getUser:getUser·p0.999         sample        25.843           ms/op
Client.getUser:getUser·p0.9999        sample        26.083           ms/op
Client.getUser:getUser·p1.00          sample        26.083           ms/op
Client.listUser                       sample  1500  21.487 ± 0.522   ms/op
Client.listUser:listUser·p0.00        sample         5.136           ms/op
Client.listUser:listUser·p0.50        sample        19.595           ms/op
Client.listUser:listUser·p0.90        sample        31.031           ms/op
Client.listUser:listUser·p0.95        sample        34.931           ms/op
Client.listUser:listUser·p0.99        sample        42.726           ms/op
Client.listUser:listUser·p0.999       sample        50.560           ms/op
Client.listUser:listUser·p0.9999      sample        51.315           ms/op
Client.listUser:listUser·p1.00        sample        51.315           ms/op
