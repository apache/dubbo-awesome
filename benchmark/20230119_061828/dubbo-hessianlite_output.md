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
# Warmup Iteration   1: 1.030 ops/ms
Iteration   1: 2.376 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.376 ops/ms


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
# Warmup Iteration   1: 2.441 ops/ms
Iteration   1: 7.607 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.607 ops/ms


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
# Warmup Iteration   1: 2.318 ops/ms
Iteration   1: 4.363 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.363 ops/ms


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
# Warmup Iteration   1: 0.884 ops/ms
Iteration   1: 1.416 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.416 ops/ms


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
# Warmup Iteration   1: 15.083 ±(99.9%) 0.270 ms/op
Iteration   1: 7.152 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.152 ms/op


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
# Warmup Iteration   1: 6.611 ±(99.9%) 0.076 ms/op
Iteration   1: 2.999 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.999 ms/op


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
# Warmup Iteration   1: 11.008 ±(99.9%) 0.173 ms/op
Iteration   1: 4.559 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.559 ms/op


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
# Warmup Iteration   1: 31.102 ±(99.9%) 0.467 ms/op
Iteration   1: 17.838 ±(99.9%) 0.114 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.838 ms/op


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
# Warmup Iteration   1: 10.203 ±(99.9%) 0.368 ms/op
Iteration   1: 6.207 ±(99.9%) 0.110 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   6.111 ms/op
                 createUser·p0.90:   6.849 ms/op
                 createUser·p0.95:   11.452 ms/op
                 createUser·p0.99:   15.827 ms/op
                 createUser·p0.999:  21.617 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5143
  mean =      6.207 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 152 
    [ 2.500,  5.000) = 616 
    [ 5.000,  7.500) = 4006 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      6.111 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =     11.452 ms/op
     p(99.0000) =     15.827 ms/op
     p(99.9000) =     21.617 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 6.741 ±(99.9%) 0.195 ms/op
Iteration   1: 4.139 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   8.954 ms/op
                 existUser·p0.999:  10.347 ms/op
                 existUser·p0.9999: 10.732 ms/op
                 existUser·p1.00:   10.732 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7725
  mean =      4.139 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 7 
    [ 1.000,  2.000) = 328 
    [ 2.000,  3.000) = 39 
    [ 3.000,  4.000) = 2858 
    [ 4.000,  5.000) = 4247 
    [ 5.000,  6.000) = 55 
    [ 6.000,  7.000) = 27 
    [ 7.000,  8.000) = 68 
    [ 8.000,  9.000) = 20 
    [ 9.000, 10.000) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      8.954 ms/op
     p(99.9000) =     10.347 ms/op
     p(99.9900) =     10.732 ms/op
     p(99.9990) =     10.732 ms/op
     p(99.9999) =     10.732 ms/op
    p(100.0000) =     10.732 ms/op


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
# Warmup Iteration   1: 11.682 ±(99.9%) 0.372 ms/op
Iteration   1: 5.015 ±(99.9%) 0.083 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   7.035 ms/op
                 getUser·p0.95:   8.503 ms/op
                 getUser·p0.99:   12.485 ms/op
                 getUser·p0.999:  19.333 ms/op
                 getUser·p0.9999: 19.595 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6301
  mean =      5.015 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 101 
    [ 2.500,  3.750) = 1392 
    [ 3.750,  5.000) = 1955 
    [ 5.000,  6.250) = 1862 
    [ 6.250,  7.500) = 489 
    [ 7.500,  8.750) = 253 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      7.035 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 27.146 ±(99.9%) 0.784 ms/op
Iteration   1: 16.680 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   12.534 ms/op
                 listUser·p0.50:   16.876 ms/op
                 listUser·p0.90:   18.055 ms/op
                 listUser·p0.95:   18.693 ms/op
                 listUser·p0.99:   21.781 ms/op
                 listUser·p0.999:  22.785 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1930
  mean =     16.680 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 116 
    [15.000, 16.250) = 687 
    [16.250, 17.500) = 394 
    [17.500, 18.750) = 622 
    [18.750, 20.000) = 31 
    [20.000, 21.250) = 32 
    [21.250, 22.500) = 24 
    [22.500, 23.750) = 6 
    [23.750, 25.000) = 0 
    [25.000, 26.250) = 0 
    [26.250, 27.500) = 0 
    [27.500, 28.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =     12.534 ms/op
     p(50.0000) =     16.876 ms/op
     p(90.0000) =     18.055 ms/op
     p(95.0000) =     18.693 ms/op
     p(99.0000) =     21.781 ms/op
     p(99.9000) =     22.785 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.376          ops/ms
Client.existUser                       thrpt         7.607          ops/ms
Client.getUser                         thrpt         4.363          ops/ms
Client.listUser                        thrpt         1.416          ops/ms
Client.createUser                       avgt         7.152           ms/op
Client.existUser                        avgt         2.999           ms/op
Client.getUser                          avgt         4.559           ms/op
Client.listUser                         avgt        17.838           ms/op
Client.createUser                     sample  5143   6.207 ± 0.110   ms/op
Client.createUser:createUser·p0.00    sample         1.053           ms/op
Client.createUser:createUser·p0.50    sample         6.111           ms/op
Client.createUser:createUser·p0.90    sample         6.849           ms/op
Client.createUser:createUser·p0.95    sample        11.452           ms/op
Client.createUser:createUser·p0.99    sample        15.827           ms/op
Client.createUser:createUser·p0.999   sample        21.617           ms/op
Client.createUser:createUser·p0.9999  sample        21.660           ms/op
Client.createUser:createUser·p1.00    sample        21.660           ms/op
Client.existUser                      sample  7725   4.139 ± 0.037   ms/op
Client.existUser:existUser·p0.00      sample         0.805           ms/op
Client.existUser:existUser·p0.50      sample         4.219           ms/op
Client.existUser:existUser·p0.90      sample         4.628           ms/op
Client.existUser:existUser·p0.95      sample         4.850           ms/op
Client.existUser:existUser·p0.99      sample         8.954           ms/op
Client.existUser:existUser·p0.999     sample        10.347           ms/op
Client.existUser:existUser·p0.9999    sample        10.732           ms/op
Client.existUser:existUser·p1.00      sample        10.732           ms/op
Client.getUser                        sample  6301   5.015 ± 0.083   ms/op
Client.getUser:getUser·p0.00          sample         1.122           ms/op
Client.getUser:getUser·p0.50          sample         4.899           ms/op
Client.getUser:getUser·p0.90          sample         7.035           ms/op
Client.getUser:getUser·p0.95          sample         8.503           ms/op
Client.getUser:getUser·p0.99          sample        12.485           ms/op
Client.getUser:getUser·p0.999         sample        19.333           ms/op
Client.getUser:getUser·p0.9999        sample        19.595           ms/op
Client.getUser:getUser·p1.00          sample        19.595           ms/op
Client.listUser                       sample  1930  16.680 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample        12.534           ms/op
Client.listUser:listUser·p0.50        sample        16.876           ms/op
Client.listUser:listUser·p0.90        sample        18.055           ms/op
Client.listUser:listUser·p0.95        sample        18.693           ms/op
Client.listUser:listUser·p0.99        sample        21.781           ms/op
Client.listUser:listUser·p0.999       sample        22.785           ms/op
Client.listUser:listUser·p0.9999      sample        22.938           ms/op
Client.listUser:listUser·p1.00        sample        22.938           ms/op
