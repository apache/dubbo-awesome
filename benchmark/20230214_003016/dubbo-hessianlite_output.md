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
# Warmup Iteration   1: 0.520 ops/ms
Iteration   1: 1.216 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.216 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 1.529 ops/ms
Iteration   1: 3.671 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.671 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.103 ops/ms
Iteration   1: 2.610 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.610 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 0.650 ops/ms
Iteration   1: 0.923 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.923 ops/ms


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
# Warmup Iteration   1: 24.854 ±(99.9%) 0.566 ms/op
Iteration   1: 14.824 ±(99.9%) 0.071 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  14.824 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 20.352 ±(99.9%) 0.317 ms/op
Iteration   1: 10.466 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.466 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 21.486 ±(99.9%) 0.377 ms/op
Iteration   1: 10.665 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.665 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 42.240 ±(99.9%) 1.431 ms/op
Iteration   1: 30.524 ±(99.9%) 0.307 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  30.524 ms/op


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
# Warmup Iteration   1: 23.730 ±(99.9%) 0.942 ms/op
Iteration   1: 8.800 ±(99.9%) 0.250 ms/op
                 createUser·p0.00:   2.879 ms/op
                 createUser·p0.50:   8.479 ms/op
                 createUser·p0.90:   13.047 ms/op
                 createUser·p0.95:   15.860 ms/op
                 createUser·p0.99:   32.418 ms/op
                 createUser·p0.999:  36.003 ms/op
                 createUser·p0.9999: 36.176 ms/op
                 createUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3636
  mean =      8.800 ±(99.9%) 0.250 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 701 
    [ 5.000,  7.500) = 760 
    [ 7.500, 10.000) = 1155 
    [10.000, 12.500) = 606 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.879 ms/op
     p(50.0000) =      8.479 ms/op
     p(90.0000) =     13.047 ms/op
     p(95.0000) =     15.860 ms/op
     p(99.0000) =     32.418 ms/op
     p(99.9000) =     36.003 ms/op
     p(99.9900) =     36.176 ms/op
     p(99.9990) =     36.176 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 11.970 ±(99.9%) 0.350 ms/op
Iteration   1: 7.694 ±(99.9%) 0.146 ms/op
                 existUser·p0.00:   1.640 ms/op
                 existUser·p0.50:   7.823 ms/op
                 existUser·p0.90:   9.486 ms/op
                 existUser·p0.95:   10.300 ms/op
                 existUser·p0.99:   16.056 ms/op
                 existUser·p0.999:  29.453 ms/op
                 existUser·p0.9999: 29.852 ms/op
                 existUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4166
  mean =      7.694 ±(99.9%) 0.146 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 472 
    [ 5.000,  7.500) = 1045 
    [ 7.500, 10.000) = 2336 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      7.823 ms/op
     p(90.0000) =      9.486 ms/op
     p(95.0000) =     10.300 ms/op
     p(99.0000) =     16.056 ms/op
     p(99.9000) =     29.453 ms/op
     p(99.9900) =     29.852 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 19.748 ±(99.9%) 0.670 ms/op
Iteration   1: 7.395 ±(99.9%) 0.131 ms/op
                 getUser·p0.00:   3.346 ms/op
                 getUser·p0.50:   6.775 ms/op
                 getUser·p0.90:   9.929 ms/op
                 getUser·p0.95:   12.159 ms/op
                 getUser·p0.99:   15.632 ms/op
                 getUser·p0.999:  26.280 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4297
  mean =      7.395 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 396 
    [ 5.000,  7.500) = 2300 
    [ 7.500, 10.000) = 1189 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      3.346 ms/op
     p(50.0000) =      6.775 ms/op
     p(90.0000) =      9.929 ms/op
     p(95.0000) =     12.159 ms/op
     p(99.0000) =     15.632 ms/op
     p(99.9000) =     26.280 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 38.038 ±(99.9%) 1.502 ms/op
Iteration   1: 24.658 ±(99.9%) 0.591 ms/op
                 listUser·p0.00:   11.158 ms/op
                 listUser·p0.50:   24.478 ms/op
                 listUser·p0.90:   32.047 ms/op
                 listUser·p0.95:   35.389 ms/op
                 listUser·p0.99:   41.743 ms/op
                 listUser·p0.999:  45.886 ms/op
                 listUser·p0.9999: 46.006 ms/op
                 listUser·p1.00:   46.006 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1304
  mean =     24.658 ±(99.9%) 0.591 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 162 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 254 
    [30.000, 32.500) = 162 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 25 
    [37.500, 40.000) = 24 
    [40.000, 42.500) = 6 
    [42.500, 45.000) = 8 
    [45.000, 47.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =     11.158 ms/op
     p(50.0000) =     24.478 ms/op
     p(90.0000) =     32.047 ms/op
     p(95.0000) =     35.389 ms/op
     p(99.0000) =     41.743 ms/op
     p(99.9000) =     45.886 ms/op
     p(99.9900) =     46.006 ms/op
     p(99.9990) =     46.006 ms/op
     p(99.9999) =     46.006 ms/op
    p(100.0000) =     46.006 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.216          ops/ms
Client.existUser                       thrpt         3.671          ops/ms
Client.getUser                         thrpt         2.610          ops/ms
Client.listUser                        thrpt         0.923          ops/ms
Client.createUser                       avgt        14.824           ms/op
Client.existUser                        avgt        10.466           ms/op
Client.getUser                          avgt        10.665           ms/op
Client.listUser                         avgt        30.524           ms/op
Client.createUser                     sample  3636   8.800 ± 0.250   ms/op
Client.createUser:createUser·p0.00    sample         2.879           ms/op
Client.createUser:createUser·p0.50    sample         8.479           ms/op
Client.createUser:createUser·p0.90    sample        13.047           ms/op
Client.createUser:createUser·p0.95    sample        15.860           ms/op
Client.createUser:createUser·p0.99    sample        32.418           ms/op
Client.createUser:createUser·p0.999   sample        36.003           ms/op
Client.createUser:createUser·p0.9999  sample        36.176           ms/op
Client.createUser:createUser·p1.00    sample        36.176           ms/op
Client.existUser                      sample  4166   7.694 ± 0.146   ms/op
Client.existUser:existUser·p0.00      sample         1.640           ms/op
Client.existUser:existUser·p0.50      sample         7.823           ms/op
Client.existUser:existUser·p0.90      sample         9.486           ms/op
Client.existUser:existUser·p0.95      sample        10.300           ms/op
Client.existUser:existUser·p0.99      sample        16.056           ms/op
Client.existUser:existUser·p0.999     sample        29.453           ms/op
Client.existUser:existUser·p0.9999    sample        29.852           ms/op
Client.existUser:existUser·p1.00      sample        29.852           ms/op
Client.getUser                        sample  4297   7.395 ± 0.131   ms/op
Client.getUser:getUser·p0.00          sample         3.346           ms/op
Client.getUser:getUser·p0.50          sample         6.775           ms/op
Client.getUser:getUser·p0.90          sample         9.929           ms/op
Client.getUser:getUser·p0.95          sample        12.159           ms/op
Client.getUser:getUser·p0.99          sample        15.632           ms/op
Client.getUser:getUser·p0.999         sample        26.280           ms/op
Client.getUser:getUser·p0.9999        sample        26.345           ms/op
Client.getUser:getUser·p1.00          sample        26.345           ms/op
Client.listUser                       sample  1304  24.658 ± 0.591   ms/op
Client.listUser:listUser·p0.00        sample        11.158           ms/op
Client.listUser:listUser·p0.50        sample        24.478           ms/op
Client.listUser:listUser·p0.90        sample        32.047           ms/op
Client.listUser:listUser·p0.95        sample        35.389           ms/op
Client.listUser:listUser·p0.99        sample        41.743           ms/op
Client.listUser:listUser·p0.999       sample        45.886           ms/op
Client.listUser:listUser·p0.9999      sample        46.006           ms/op
Client.listUser:listUser·p1.00        sample        46.006           ms/op
