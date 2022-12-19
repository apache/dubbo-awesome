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
# Warmup Iteration   1: 1.013 ops/ms
Iteration   1: 2.099 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.099 ops/ms


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
# Warmup Iteration   1: 2.242 ops/ms
Iteration   1: 5.190 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.190 ops/ms


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
# Warmup Iteration   1: 2.039 ops/ms
Iteration   1: 4.653 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.653 ops/ms


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
# Warmup Iteration   1: 0.826 ops/ms
Iteration   1: 1.381 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.381 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 15.705 ±(99.9%) 0.197 ms/op
Iteration   1: 7.678 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.678 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.006 ±(99.9%) 0.095 ms/op
Iteration   1: 4.542 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.542 ms/op


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
# Warmup Iteration   1: 9.853 ±(99.9%) 0.146 ms/op
Iteration   1: 4.441 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.441 ms/op


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
# Warmup Iteration   1: 29.569 ±(99.9%) 0.529 ms/op
Iteration   1: 19.274 ±(99.9%) 0.103 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.274 ms/op


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
# Warmup Iteration   1: 13.527 ±(99.9%) 0.496 ms/op
Iteration   1: 7.493 ±(99.9%) 0.130 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   7.225 ms/op
                 createUser·p0.90:   8.405 ms/op
                 createUser·p0.95:   14.302 ms/op
                 createUser·p0.99:   19.155 ms/op
                 createUser·p0.999:  21.387 ms/op
                 createUser·p0.9999: 23.265 ms/op
                 createUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4321
  mean =      7.493 ±(99.9%) 0.130 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 365 
    [ 5.000,  7.500) = 2682 
    [ 7.500, 10.000) = 965 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =      7.225 ms/op
     p(90.0000) =      8.405 ms/op
     p(95.0000) =     14.302 ms/op
     p(99.0000) =     19.155 ms/op
     p(99.9000) =     21.387 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 8.114 ±(99.9%) 0.247 ms/op
Iteration   1: 4.245 ±(99.9%) 0.103 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   8.049 ms/op
                 existUser·p0.99:   11.764 ms/op
                 existUser·p0.999:  31.752 ms/op
                 existUser·p0.9999: 31.949 ms/op
                 existUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7549
  mean =      4.245 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 800 
    [ 2.500,  5.000) = 5892 
    [ 5.000,  7.500) = 422 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      8.049 ms/op
     p(99.0000) =     11.764 ms/op
     p(99.9000) =     31.752 ms/op
     p(99.9900) =     31.949 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 14.090 ±(99.9%) 0.538 ms/op
Iteration   1: 4.843 ±(99.9%) 0.079 ms/op
                 getUser·p0.00:   1.884 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   6.443 ms/op
                 getUser·p0.99:   15.042 ms/op
                 getUser·p0.999:  26.051 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6588
  mean =      4.843 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 5136 
    [ 5.000,  7.500) = 1250 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.884 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.443 ms/op
     p(99.0000) =     15.042 ms/op
     p(99.9000) =     26.051 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 31.377 ±(99.9%) 1.057 ms/op
Iteration   1: 18.592 ±(99.9%) 0.243 ms/op
                 listUser·p0.00:   8.749 ms/op
                 listUser·p0.50:   17.859 ms/op
                 listUser·p0.90:   21.758 ms/op
                 listUser·p0.95:   25.199 ms/op
                 listUser·p0.99:   28.819 ms/op
                 listUser·p0.999:  35.237 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1724
  mean =     18.592 ±(99.9%) 0.243 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 589 
    [17.500, 20.000) = 665 
    [20.000, 22.500) = 217 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      8.749 ms/op
     p(50.0000) =     17.859 ms/op
     p(90.0000) =     21.758 ms/op
     p(95.0000) =     25.199 ms/op
     p(99.0000) =     28.819 ms/op
     p(99.9000) =     35.237 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.099          ops/ms
Client.existUser                       thrpt         5.190          ops/ms
Client.getUser                         thrpt         4.653          ops/ms
Client.listUser                        thrpt         1.381          ops/ms
Client.createUser                       avgt         7.678           ms/op
Client.existUser                        avgt         4.542           ms/op
Client.getUser                          avgt         4.441           ms/op
Client.listUser                         avgt        19.274           ms/op
Client.createUser                     sample  4321   7.493 ± 0.130   ms/op
Client.createUser:createUser·p0.00    sample         2.314           ms/op
Client.createUser:createUser·p0.50    sample         7.225           ms/op
Client.createUser:createUser·p0.90    sample         8.405           ms/op
Client.createUser:createUser·p0.95    sample        14.302           ms/op
Client.createUser:createUser·p0.99    sample        19.155           ms/op
Client.createUser:createUser·p0.999   sample        21.387           ms/op
Client.createUser:createUser·p0.9999  sample        23.265           ms/op
Client.createUser:createUser·p1.00    sample        23.265           ms/op
Client.existUser                      sample  7549   4.245 ± 0.103   ms/op
Client.existUser:existUser·p0.00      sample         0.808           ms/op
Client.existUser:existUser·p0.50      sample         3.838           ms/op
Client.existUser:existUser·p0.90      sample         5.226           ms/op
Client.existUser:existUser·p0.95      sample         8.049           ms/op
Client.existUser:existUser·p0.99      sample        11.764           ms/op
Client.existUser:existUser·p0.999     sample        31.752           ms/op
Client.existUser:existUser·p0.9999    sample        31.949           ms/op
Client.existUser:existUser·p1.00      sample        31.949           ms/op
Client.getUser                        sample  6588   4.843 ± 0.079   ms/op
Client.getUser:getUser·p0.00          sample         1.884           ms/op
Client.getUser:getUser·p0.50          sample         4.612           ms/op
Client.getUser:getUser·p0.90          sample         5.448           ms/op
Client.getUser:getUser·p0.95          sample         6.443           ms/op
Client.getUser:getUser·p0.99          sample        15.042           ms/op
Client.getUser:getUser·p0.999         sample        26.051           ms/op
Client.getUser:getUser·p0.9999        sample        26.083           ms/op
Client.getUser:getUser·p1.00          sample        26.083           ms/op
Client.listUser                       sample  1724  18.592 ± 0.243   ms/op
Client.listUser:listUser·p0.00        sample         8.749           ms/op
Client.listUser:listUser·p0.50        sample        17.859           ms/op
Client.listUser:listUser·p0.90        sample        21.758           ms/op
Client.listUser:listUser·p0.95        sample        25.199           ms/op
Client.listUser:listUser·p0.99        sample        28.819           ms/op
Client.listUser:listUser·p0.999       sample        35.237           ms/op
Client.listUser:listUser·p0.9999      sample        36.045           ms/op
Client.listUser:listUser·p1.00        sample        36.045           ms/op
