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
# Warmup Iteration   1: 1.171 ops/ms
Iteration   1: 2.846 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.846 ops/ms


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
# Warmup Iteration   1: 2.889 ops/ms
Iteration   1: 6.577 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.577 ops/ms


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
# Warmup Iteration   1: 2.305 ops/ms
Iteration   1: 4.492 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.492 ops/ms


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
# Warmup Iteration   1: 0.953 ops/ms
Iteration   1: 1.253 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.253 ops/ms


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
# Warmup Iteration   1: 19.692 ±(99.9%) 0.319 ms/op
Iteration   1: 8.725 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.725 ms/op


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
# Warmup Iteration   1: 7.444 ±(99.9%) 0.086 ms/op
Iteration   1: 4.176 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.176 ms/op


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
# Warmup Iteration   1: 9.247 ±(99.9%) 0.151 ms/op
Iteration   1: 5.140 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.140 ms/op


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
# Warmup Iteration   1: 29.041 ±(99.9%) 0.796 ms/op
Iteration   1: 16.750 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.750 ms/op


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
# Warmup Iteration   1: 14.633 ±(99.9%) 0.526 ms/op
Iteration   1: 7.202 ±(99.9%) 0.106 ms/op
                 createUser·p0.00:   3.297 ms/op
                 createUser·p0.50:   7.381 ms/op
                 createUser·p0.90:   7.864 ms/op
                 createUser·p0.95:   8.756 ms/op
                 createUser·p0.99:   17.531 ms/op
                 createUser·p0.999:  24.813 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4485
  mean =      7.202 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 626 
    [ 5.000,  7.500) = 2334 
    [ 7.500, 10.000) = 1375 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      3.297 ms/op
     p(50.0000) =      7.381 ms/op
     p(90.0000) =      7.864 ms/op
     p(95.0000) =      8.756 ms/op
     p(99.0000) =     17.531 ms/op
     p(99.9000) =     24.813 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 6.902 ±(99.9%) 0.218 ms/op
Iteration   1: 4.757 ±(99.9%) 0.076 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   7.693 ms/op
                 existUser·p0.999:  24.904 ms/op
                 existUser·p0.9999: 28.672 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6716
  mean =      4.757 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 3946 
    [ 5.000,  7.500) = 2624 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      7.693 ms/op
     p(99.9000) =     24.904 ms/op
     p(99.9900) =     28.672 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 10.520 ±(99.9%) 0.292 ms/op
Iteration   1: 4.993 ±(99.9%) 0.067 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   4.735 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   5.883 ms/op
                 getUser·p0.99:   15.343 ms/op
                 getUser·p0.999:  25.756 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6516
  mean =      4.993 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 4667 
    [ 5.000,  7.500) = 1693 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.883 ms/op
     p(99.0000) =     15.343 ms/op
     p(99.9000) =     25.756 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 30.009 ±(99.9%) 1.067 ms/op
Iteration   1: 17.673 ±(99.9%) 0.167 ms/op
                 listUser·p0.00:   7.766 ms/op
                 listUser·p0.50:   17.236 ms/op
                 listUser·p0.90:   19.104 ms/op
                 listUser·p0.95:   21.135 ms/op
                 listUser·p0.99:   26.870 ms/op
                 listUser·p0.999:  35.036 ms/op
                 listUser·p0.9999: 36.700 ms/op
                 listUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1818
  mean =     17.673 ±(99.9%) 0.167 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 1058 
    [17.500, 20.000) = 568 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      7.766 ms/op
     p(50.0000) =     17.236 ms/op
     p(90.0000) =     19.104 ms/op
     p(95.0000) =     21.135 ms/op
     p(99.0000) =     26.870 ms/op
     p(99.9000) =     35.036 ms/op
     p(99.9900) =     36.700 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.846          ops/ms
Client.existUser                       thrpt         6.577          ops/ms
Client.getUser                         thrpt         4.492          ops/ms
Client.listUser                        thrpt         1.253          ops/ms
Client.createUser                       avgt         8.725           ms/op
Client.existUser                        avgt         4.176           ms/op
Client.getUser                          avgt         5.140           ms/op
Client.listUser                         avgt        16.750           ms/op
Client.createUser                     sample  4485   7.202 ± 0.106   ms/op
Client.createUser:createUser·p0.00    sample         3.297           ms/op
Client.createUser:createUser·p0.50    sample         7.381           ms/op
Client.createUser:createUser·p0.90    sample         7.864           ms/op
Client.createUser:createUser·p0.95    sample         8.756           ms/op
Client.createUser:createUser·p0.99    sample        17.531           ms/op
Client.createUser:createUser·p0.999   sample        24.813           ms/op
Client.createUser:createUser·p0.9999  sample        25.526           ms/op
Client.createUser:createUser·p1.00    sample        25.526           ms/op
Client.existUser                      sample  6716   4.757 ± 0.076   ms/op
Client.existUser:existUser·p0.00      sample         1.182           ms/op
Client.existUser:existUser·p0.50      sample         4.891           ms/op
Client.existUser:existUser·p0.90      sample         5.825           ms/op
Client.existUser:existUser·p0.95      sample         6.054           ms/op
Client.existUser:existUser·p0.99      sample         7.693           ms/op
Client.existUser:existUser·p0.999     sample        24.904           ms/op
Client.existUser:existUser·p0.9999    sample        28.672           ms/op
Client.existUser:existUser·p1.00      sample        28.672           ms/op
Client.getUser                        sample  6516   4.993 ± 0.067   ms/op
Client.getUser:getUser·p0.00          sample         1.661           ms/op
Client.getUser:getUser·p0.50          sample         4.735           ms/op
Client.getUser:getUser·p0.90          sample         5.439           ms/op
Client.getUser:getUser·p0.95          sample         5.883           ms/op
Client.getUser:getUser·p0.99          sample        15.343           ms/op
Client.getUser:getUser·p0.999         sample        25.756           ms/op
Client.getUser:getUser·p0.9999        sample        25.919           ms/op
Client.getUser:getUser·p1.00          sample        25.919           ms/op
Client.listUser                       sample  1818  17.673 ± 0.167   ms/op
Client.listUser:listUser·p0.00        sample         7.766           ms/op
Client.listUser:listUser·p0.50        sample        17.236           ms/op
Client.listUser:listUser·p0.90        sample        19.104           ms/op
Client.listUser:listUser·p0.95        sample        21.135           ms/op
Client.listUser:listUser·p0.99        sample        26.870           ms/op
Client.listUser:listUser·p0.999       sample        35.036           ms/op
Client.listUser:listUser·p0.9999      sample        36.700           ms/op
Client.listUser:listUser·p1.00        sample        36.700           ms/op
