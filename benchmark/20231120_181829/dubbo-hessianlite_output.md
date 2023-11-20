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
# Warmup Iteration   1: 2.506 ops/ms
Iteration   1: 5.819 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.819 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.723 ops/ms
Iteration   1: 13.287 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.287 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.112 ops/ms
Iteration   1: 8.746 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.746 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.500 ops/ms
Iteration   1: 4.220 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.220 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.827 ±(99.9%) 0.060 ms/op
Iteration   1: 3.625 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.625 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ±(99.9%) 0.032 ms/op
Iteration   1: 1.892 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.892 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.717 ±(99.9%) 0.067 ms/op
Iteration   1: 2.792 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.792 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.607 ±(99.9%) 0.264 ms/op
Iteration   1: 7.749 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.749 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.783 ±(99.9%) 0.148 ms/op
Iteration   1: 3.031 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.839 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.259 ms/op
                 createUser·p0.99:   8.372 ms/op
                 createUser·p0.999:  13.868 ms/op
                 createUser·p0.9999: 13.942 ms/op
                 createUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10561
  mean =      3.031 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 2635 
    [ 2.500,  3.750) = 6812 
    [ 3.750,  5.000) = 775 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.259 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     13.868 ms/op
     p(99.9900) =     13.942 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.914 ±(99.9%) 0.052 ms/op
Iteration   1: 1.856 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   1.892 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   2.915 ms/op
                 existUser·p0.999:  13.136 ms/op
                 existUser·p0.9999: 14.034 ms/op
                 existUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17217
  mean =      1.856 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1939 
    [ 1.250,  2.500) = 14733 
    [ 2.500,  3.750) = 429 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      2.915 ms/op
     p(99.9000) =     13.136 ms/op
     p(99.9900) =     14.034 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.321 ±(99.9%) 0.099 ms/op
Iteration   1: 3.102 ±(99.9%) 0.125 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   6.962 ms/op
                 getUser·p0.999:  69.705 ms/op
                 getUser·p0.9999: 72.868 ms/op
                 getUser·p1.00:   72.876 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10312
  mean =      3.102 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10117 
    [ 5.000, 10.000) = 99 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 61 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 23 
    [70.000, 75.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.962 ms/op
     p(99.9000) =     69.705 ms/op
     p(99.9900) =     72.868 ms/op
     p(99.9990) =     72.876 ms/op
     p(99.9999) =     72.876 ms/op
    p(100.0000) =     72.876 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.087 ±(99.9%) 0.363 ms/op
Iteration   1: 7.988 ±(99.9%) 0.110 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   7.660 ms/op
                 listUser·p0.90:   10.879 ms/op
                 listUser·p0.95:   11.747 ms/op
                 listUser·p0.99:   13.763 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3999
  mean =      7.988 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 24 
    [ 3.750,  5.000) = 183 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 1049 
    [ 7.500,  8.750) = 918 
    [ 8.750, 10.000) = 558 
    [10.000, 11.250) = 380 
    [11.250, 12.500) = 188 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.552 ms/op
     p(50.0000) =      7.660 ms/op
     p(90.0000) =     10.879 ms/op
     p(95.0000) =     11.747 ms/op
     p(99.0000) =     13.763 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.819          ops/ms
Client.existUser                       thrpt         13.287          ops/ms
Client.getUser                         thrpt          8.746          ops/ms
Client.listUser                        thrpt          4.220          ops/ms
Client.createUser                       avgt          3.625           ms/op
Client.existUser                        avgt          1.892           ms/op
Client.getUser                          avgt          2.792           ms/op
Client.listUser                         avgt          7.749           ms/op
Client.createUser                     sample  10561   3.031 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          0.950           ms/op
Client.createUser:createUser·p0.50    sample          2.839           ms/op
Client.createUser:createUser·p0.90    sample          3.772           ms/op
Client.createUser:createUser·p0.95    sample          4.259           ms/op
Client.createUser:createUser·p0.99    sample          8.372           ms/op
Client.createUser:createUser·p0.999   sample         13.868           ms/op
Client.createUser:createUser·p0.9999  sample         13.942           ms/op
Client.createUser:createUser·p1.00    sample         13.943           ms/op
Client.existUser                      sample  17217   1.856 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.737           ms/op
Client.existUser:existUser·p0.50      sample          1.892           ms/op
Client.existUser:existUser·p0.90      sample          2.298           ms/op
Client.existUser:existUser·p0.95      sample          2.441           ms/op
Client.existUser:existUser·p0.99      sample          2.915           ms/op
Client.existUser:existUser·p0.999     sample         13.136           ms/op
Client.existUser:existUser·p0.9999    sample         14.034           ms/op
Client.existUser:existUser·p1.00      sample         14.057           ms/op
Client.getUser                        sample  10312   3.102 ± 0.125   ms/op
Client.getUser:getUser·p0.00          sample          1.108           ms/op
Client.getUser:getUser·p0.50          sample          2.597           ms/op
Client.getUser:getUser·p0.90          sample          3.678           ms/op
Client.getUser:getUser·p0.95          sample          4.125           ms/op
Client.getUser:getUser·p0.99          sample          6.962           ms/op
Client.getUser:getUser·p0.999         sample         69.705           ms/op
Client.getUser:getUser·p0.9999        sample         72.868           ms/op
Client.getUser:getUser·p1.00          sample         72.876           ms/op
Client.listUser                       sample   3999   7.988 ± 0.110   ms/op
Client.listUser:listUser·p0.00        sample          2.552           ms/op
Client.listUser:listUser·p0.50        sample          7.660           ms/op
Client.listUser:listUser·p0.90        sample         10.879           ms/op
Client.listUser:listUser·p0.95        sample         11.747           ms/op
Client.listUser:listUser·p0.99        sample         13.763           ms/op
Client.listUser:listUser·p0.999       sample         17.957           ms/op
Client.listUser:listUser·p0.9999      sample         19.628           ms/op
Client.listUser:listUser·p1.00        sample         19.628           ms/op
