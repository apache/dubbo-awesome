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
# Warmup Iteration   1: 1.131 ops/ms
Iteration   1: 2.352 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.352 ops/ms


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
# Warmup Iteration   1: 2.454 ops/ms
Iteration   1: 5.392 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.392 ops/ms


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
# Warmup Iteration   1: 1.952 ops/ms
Iteration   1: 4.624 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.624 ops/ms


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
# Warmup Iteration   1: 0.795 ops/ms
Iteration   1: 1.283 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.283 ops/ms


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
# Warmup Iteration   1: 19.748 ±(99.9%) 0.286 ms/op
Iteration   1: 9.303 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.303 ms/op


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
# Warmup Iteration   1: 8.773 ±(99.9%) 0.106 ms/op
Iteration   1: 4.094 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.094 ms/op


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
# Warmup Iteration   1: 10.509 ±(99.9%) 0.107 ms/op
Iteration   1: 5.112 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.112 ms/op


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
# Warmup Iteration   1: 25.217 ±(99.9%) 0.371 ms/op
Iteration   1: 17.781 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.781 ms/op


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
# Warmup Iteration   1: 13.164 ±(99.9%) 0.390 ms/op
Iteration   1: 6.770 ±(99.9%) 0.133 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   6.144 ms/op
                 createUser·p0.90:   9.454 ms/op
                 createUser·p0.95:   10.073 ms/op
                 createUser·p0.99:   18.072 ms/op
                 createUser·p0.999:  36.128 ms/op
                 createUser·p0.9999: 36.241 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4723
  mean =      6.770 ±(99.9%) 0.133 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 176 
    [ 5.000,  7.500) = 3847 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      9.454 ms/op
     p(95.0000) =     10.073 ms/op
     p(99.0000) =     18.072 ms/op
     p(99.9000) =     36.128 ms/op
     p(99.9900) =     36.241 ms/op
     p(99.9990) =     36.241 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 7.600 ±(99.9%) 0.294 ms/op
Iteration   1: 4.690 ±(99.9%) 0.084 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   7.714 ms/op
                 existUser·p0.99:   14.336 ms/op
                 existUser·p0.999:  17.859 ms/op
                 existUser·p0.9999: 18.317 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6948
  mean =      4.690 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 854 
    [ 2.500,  3.750) = 1182 
    [ 3.750,  5.000) = 2083 
    [ 5.000,  6.250) = 2186 
    [ 6.250,  7.500) = 267 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      7.714 ms/op
     p(99.0000) =     14.336 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 11.111 ±(99.9%) 0.405 ms/op
Iteration   1: 5.357 ±(99.9%) 0.094 ms/op
                 getUser·p0.00:   1.747 ms/op
                 getUser·p0.50:   4.702 ms/op
                 getUser·p0.90:   7.575 ms/op
                 getUser·p0.95:   8.321 ms/op
                 getUser·p0.99:   13.551 ms/op
                 getUser·p0.999:  23.038 ms/op
                 getUser·p0.9999: 23.331 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5962
  mean =      5.357 ±(99.9%) 0.094 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 3128 
    [ 5.000,  7.500) = 2145 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      7.575 ms/op
     p(95.0000) =      8.321 ms/op
     p(99.0000) =     13.551 ms/op
     p(99.9000) =     23.038 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 26.957 ±(99.9%) 0.674 ms/op
Iteration   1: 17.783 ±(99.9%) 0.290 ms/op
                 listUser·p0.00:   8.118 ms/op
                 listUser·p0.50:   17.924 ms/op
                 listUser·p0.90:   20.644 ms/op
                 listUser·p0.95:   23.691 ms/op
                 listUser·p0.99:   32.506 ms/op
                 listUser·p0.999:  38.339 ms/op
                 listUser·p0.9999: 38.863 ms/op
                 listUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1799
  mean =     17.783 ±(99.9%) 0.290 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 525 
    [17.500, 20.000) = 761 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      8.118 ms/op
     p(50.0000) =     17.924 ms/op
     p(90.0000) =     20.644 ms/op
     p(95.0000) =     23.691 ms/op
     p(99.0000) =     32.506 ms/op
     p(99.9000) =     38.339 ms/op
     p(99.9900) =     38.863 ms/op
     p(99.9990) =     38.863 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.352          ops/ms
Client.existUser                       thrpt         5.392          ops/ms
Client.getUser                         thrpt         4.624          ops/ms
Client.listUser                        thrpt         1.283          ops/ms
Client.createUser                       avgt         9.303           ms/op
Client.existUser                        avgt         4.094           ms/op
Client.getUser                          avgt         5.112           ms/op
Client.listUser                         avgt        17.781           ms/op
Client.createUser                     sample  4723   6.770 ± 0.133   ms/op
Client.createUser:createUser·p0.00    sample         1.214           ms/op
Client.createUser:createUser·p0.50    sample         6.144           ms/op
Client.createUser:createUser·p0.90    sample         9.454           ms/op
Client.createUser:createUser·p0.95    sample        10.073           ms/op
Client.createUser:createUser·p0.99    sample        18.072           ms/op
Client.createUser:createUser·p0.999   sample        36.128           ms/op
Client.createUser:createUser·p0.9999  sample        36.241           ms/op
Client.createUser:createUser·p1.00    sample        36.241           ms/op
Client.existUser                      sample  6948   4.690 ± 0.084   ms/op
Client.existUser:existUser·p0.00      sample         0.603           ms/op
Client.existUser:existUser·p0.50      sample         4.866           ms/op
Client.existUser:existUser·p0.90      sample         5.882           ms/op
Client.existUser:existUser·p0.95      sample         7.714           ms/op
Client.existUser:existUser·p0.99      sample        14.336           ms/op
Client.existUser:existUser·p0.999     sample        17.859           ms/op
Client.existUser:existUser·p0.9999    sample        18.317           ms/op
Client.existUser:existUser·p1.00      sample        18.317           ms/op
Client.getUser                        sample  5962   5.357 ± 0.094   ms/op
Client.getUser:getUser·p0.00          sample         1.747           ms/op
Client.getUser:getUser·p0.50          sample         4.702           ms/op
Client.getUser:getUser·p0.90          sample         7.575           ms/op
Client.getUser:getUser·p0.95          sample         8.321           ms/op
Client.getUser:getUser·p0.99          sample        13.551           ms/op
Client.getUser:getUser·p0.999         sample        23.038           ms/op
Client.getUser:getUser·p0.9999        sample        23.331           ms/op
Client.getUser:getUser·p1.00          sample        23.331           ms/op
Client.listUser                       sample  1799  17.783 ± 0.290   ms/op
Client.listUser:listUser·p0.00        sample         8.118           ms/op
Client.listUser:listUser·p0.50        sample        17.924           ms/op
Client.listUser:listUser·p0.90        sample        20.644           ms/op
Client.listUser:listUser·p0.95        sample        23.691           ms/op
Client.listUser:listUser·p0.99        sample        32.506           ms/op
Client.listUser:listUser·p0.999       sample        38.339           ms/op
Client.listUser:listUser·p0.9999      sample        38.863           ms/op
Client.listUser:listUser·p1.00        sample        38.863           ms/op
