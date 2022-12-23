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
# Warmup Iteration   1: 1.070 ops/ms
Iteration   1: 2.436 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.436 ops/ms


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
# Warmup Iteration   1: 3.273 ops/ms
Iteration   1: 6.283 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.283 ops/ms


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
# Warmup Iteration   1: 2.364 ops/ms
Iteration   1: 4.901 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.901 ops/ms


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
# Warmup Iteration   1: 0.757 ops/ms
Iteration   1: 1.365 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.365 ops/ms


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
# Warmup Iteration   1: 18.131 ±(99.9%) 0.266 ms/op
Iteration   1: 7.870 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.870 ms/op


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
# Warmup Iteration   1: 5.684 ±(99.9%) 0.052 ms/op
Iteration   1: 3.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.480 ms/op


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
# Warmup Iteration   1: 9.878 ±(99.9%) 0.194 ms/op
Iteration   1: 4.324 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.324 ms/op


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
# Warmup Iteration   1: 26.664 ±(99.9%) 0.860 ms/op
Iteration   1: 15.890 ±(99.9%) 0.199 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.890 ms/op


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
# Warmup Iteration   1: 11.214 ±(99.9%) 0.362 ms/op
Iteration   1: 6.903 ±(99.9%) 0.091 ms/op
                 createUser·p0.00:   2.683 ms/op
                 createUser·p0.50:   6.537 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   10.355 ms/op
                 createUser·p0.99:   15.708 ms/op
                 createUser·p0.999:  18.645 ms/op
                 createUser·p0.9999: 18.874 ms/op
                 createUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4632
  mean =      6.903 ±(99.9%) 0.091 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 19 
    [ 3.750,  5.000) = 3 
    [ 5.000,  6.250) = 1240 
    [ 6.250,  7.500) = 3034 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.683 ms/op
     p(50.0000) =      6.537 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =     10.355 ms/op
     p(99.0000) =     15.708 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 6.369 ±(99.9%) 0.210 ms/op
Iteration   1: 3.732 ±(99.9%) 0.063 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   6.431 ms/op
                 existUser·p0.99:   11.764 ms/op
                 existUser·p0.999:  15.584 ms/op
                 existUser·p0.9999: 18.579 ms/op
                 existUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8606
  mean =      3.732 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 380 
    [ 2.500,  3.750) = 4477 
    [ 3.750,  5.000) = 3113 
    [ 5.000,  6.250) = 115 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =     11.764 ms/op
     p(99.9000) =     15.584 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 8.753 ±(99.9%) 0.357 ms/op
Iteration   1: 4.384 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  16.548 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7296
  mean =      4.384 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 47 
    [ 2.500,  3.750) = 958 
    [ 3.750,  5.000) = 5350 
    [ 5.000,  6.250) = 753 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 27.056 ±(99.9%) 0.727 ms/op
Iteration   1: 15.292 ±(99.9%) 0.244 ms/op
                 listUser·p0.00:   7.201 ms/op
                 listUser·p0.50:   13.976 ms/op
                 listUser·p0.90:   19.399 ms/op
                 listUser·p0.95:   23.136 ms/op
                 listUser·p0.99:   27.427 ms/op
                 listUser·p0.999:  30.871 ms/op
                 listUser·p0.9999: 31.261 ms/op
                 listUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2092
  mean =     15.292 ±(99.9%) 0.244 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 1264 
    [15.000, 17.500) = 354 
    [17.500, 20.000) = 184 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      7.201 ms/op
     p(50.0000) =     13.976 ms/op
     p(90.0000) =     19.399 ms/op
     p(95.0000) =     23.136 ms/op
     p(99.0000) =     27.427 ms/op
     p(99.9000) =     30.871 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.436          ops/ms
Client.existUser                       thrpt         6.283          ops/ms
Client.getUser                         thrpt         4.901          ops/ms
Client.listUser                        thrpt         1.365          ops/ms
Client.createUser                       avgt         7.870           ms/op
Client.existUser                        avgt         3.480           ms/op
Client.getUser                          avgt         4.324           ms/op
Client.listUser                         avgt        15.890           ms/op
Client.createUser                     sample  4632   6.903 ± 0.091   ms/op
Client.createUser:createUser·p0.00    sample         2.683           ms/op
Client.createUser:createUser·p0.50    sample         6.537           ms/op
Client.createUser:createUser·p0.90    sample         7.012           ms/op
Client.createUser:createUser·p0.95    sample        10.355           ms/op
Client.createUser:createUser·p0.99    sample        15.708           ms/op
Client.createUser:createUser·p0.999   sample        18.645           ms/op
Client.createUser:createUser·p0.9999  sample        18.874           ms/op
Client.createUser:createUser·p1.00    sample        18.874           ms/op
Client.existUser                      sample  8606   3.732 ± 0.063   ms/op
Client.existUser:existUser·p0.00      sample         0.589           ms/op
Client.existUser:existUser·p0.50      sample         3.269           ms/op
Client.existUser:existUser·p0.90      sample         4.227           ms/op
Client.existUser:existUser·p0.95      sample         6.431           ms/op
Client.existUser:existUser·p0.99      sample        11.764           ms/op
Client.existUser:existUser·p0.999     sample        15.584           ms/op
Client.existUser:existUser·p0.9999    sample        18.579           ms/op
Client.existUser:existUser·p1.00      sample        18.579           ms/op
Client.getUser                        sample  7296   4.384 ± 0.044   ms/op
Client.getUser:getUser·p0.00          sample         1.233           ms/op
Client.getUser:getUser·p0.50          sample         4.211           ms/op
Client.getUser:getUser·p0.90          sample         5.153           ms/op
Client.getUser:getUser·p0.95          sample         5.546           ms/op
Client.getUser:getUser·p0.99          sample         8.897           ms/op
Client.getUser:getUser·p0.999         sample        16.548           ms/op
Client.getUser:getUser·p0.9999        sample        18.547           ms/op
Client.getUser:getUser·p1.00          sample        18.547           ms/op
Client.listUser                       sample  2092  15.292 ± 0.244   ms/op
Client.listUser:listUser·p0.00        sample         7.201           ms/op
Client.listUser:listUser·p0.50        sample        13.976           ms/op
Client.listUser:listUser·p0.90        sample        19.399           ms/op
Client.listUser:listUser·p0.95        sample        23.136           ms/op
Client.listUser:listUser·p0.99        sample        27.427           ms/op
Client.listUser:listUser·p0.999       sample        30.871           ms/op
Client.listUser:listUser·p0.9999      sample        31.261           ms/op
Client.listUser:listUser·p1.00        sample        31.261           ms/op
