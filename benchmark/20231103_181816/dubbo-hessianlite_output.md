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
# Warmup Iteration   1: 2.295 ops/ms
Iteration   1: 5.534 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.534 ops/ms


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
# Warmup Iteration   1: 7.525 ops/ms
Iteration   1: 14.713 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.713 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.016 ops/ms
Iteration   1: 9.457 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.457 ops/ms


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
# Warmup Iteration   1: 2.111 ops/ms
Iteration   1: 3.255 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.255 ops/ms


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.058 ms/op
Iteration   1: 3.088 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.088 ms/op


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
# Warmup Iteration   1: 2.734 ±(99.9%) 0.029 ms/op
Iteration   1: 1.846 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.846 ms/op


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
# Warmup Iteration   1: 4.439 ±(99.9%) 0.060 ms/op
Iteration   1: 2.914 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.914 ms/op


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
# Warmup Iteration   1: 12.948 ±(99.9%) 0.295 ms/op
Iteration   1: 8.544 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.544 ms/op


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
# Warmup Iteration   1: 5.248 ±(99.9%) 0.093 ms/op
Iteration   1: 2.859 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   2.691 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   7.072 ms/op
                 createUser·p0.999:  14.107 ms/op
                 createUser·p0.9999: 14.907 ms/op
                 createUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11186
  mean =      2.859 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 3815 
    [ 2.500,  3.750) = 6741 
    [ 3.750,  5.000) = 352 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.691 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      7.072 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     14.907 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.050 ms/op
Iteration   1: 1.914 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.557 ms/op
                 existUser·p0.99:   3.338 ms/op
                 existUser·p0.999:  5.284 ms/op
                 existUser·p0.9999: 5.624 ms/op
                 existUser·p1.00:   5.898 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16693
  mean =      1.914 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 22 
    [1.000, 1.500) = 2048 
    [1.500, 2.000) = 8492 
    [2.000, 2.500) = 5109 
    [2.500, 3.000) = 838 
    [3.000, 3.500) = 51 
    [3.500, 4.000) = 46 
    [4.000, 4.500) = 57 
    [4.500, 5.000) = 9 
    [5.000, 5.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.557 ms/op
     p(99.0000) =      3.338 ms/op
     p(99.9000) =      5.284 ms/op
     p(99.9900) =      5.624 ms/op
     p(99.9990) =      5.898 ms/op
     p(99.9999) =      5.898 ms/op
    p(100.0000) =      5.898 ms/op


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.087 ms/op
Iteration   1: 2.928 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   2.744 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  17.007 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10934
  mean =      2.928 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2967 
    [ 2.500,  3.750) = 7194 
    [ 3.750,  5.000) = 622 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      2.744 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 11.711 ±(99.9%) 0.376 ms/op
Iteration   1: 7.618 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   2.728 ms/op
                 listUser·p0.50:   7.348 ms/op
                 listUser·p0.90:   10.174 ms/op
                 listUser·p0.95:   11.316 ms/op
                 listUser·p0.99:   14.536 ms/op
                 listUser·p0.999:  19.326 ms/op
                 listUser·p0.9999: 27.001 ms/op
                 listUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4192
  mean =      7.618 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 276 
    [ 5.000,  7.500) = 1964 
    [ 7.500, 10.000) = 1500 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.728 ms/op
     p(50.0000) =      7.348 ms/op
     p(90.0000) =     10.174 ms/op
     p(95.0000) =     11.316 ms/op
     p(99.0000) =     14.536 ms/op
     p(99.9000) =     19.326 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.534          ops/ms
Client.existUser                       thrpt         14.713          ops/ms
Client.getUser                         thrpt          9.457          ops/ms
Client.listUser                        thrpt          3.255          ops/ms
Client.createUser                       avgt          3.088           ms/op
Client.existUser                        avgt          1.846           ms/op
Client.getUser                          avgt          2.914           ms/op
Client.listUser                         avgt          8.544           ms/op
Client.createUser                     sample  11186   2.859 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          0.820           ms/op
Client.createUser:createUser·p0.50    sample          2.691           ms/op
Client.createUser:createUser·p0.90    sample          3.375           ms/op
Client.createUser:createUser·p0.95    sample          3.850           ms/op
Client.createUser:createUser·p0.99    sample          7.072           ms/op
Client.createUser:createUser·p0.999   sample         14.107           ms/op
Client.createUser:createUser·p0.9999  sample         14.907           ms/op
Client.createUser:createUser·p1.00    sample         15.008           ms/op
Client.existUser                      sample  16693   1.914 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.792           ms/op
Client.existUser:existUser·p0.50      sample          1.860           ms/op
Client.existUser:existUser·p0.90      sample          2.380           ms/op
Client.existUser:existUser·p0.95      sample          2.557           ms/op
Client.existUser:existUser·p0.99      sample          3.338           ms/op
Client.existUser:existUser·p0.999     sample          5.284           ms/op
Client.existUser:existUser·p0.9999    sample          5.624           ms/op
Client.existUser:existUser·p1.00      sample          5.898           ms/op
Client.getUser                        sample  10934   2.928 ± 0.038   ms/op
Client.getUser:getUser·p0.00          sample          1.303           ms/op
Client.getUser:getUser·p0.50          sample          2.744           ms/op
Client.getUser:getUser·p0.90          sample          3.588           ms/op
Client.getUser:getUser·p0.95          sample          3.887           ms/op
Client.getUser:getUser·p0.99          sample          5.825           ms/op
Client.getUser:getUser·p0.999         sample         17.007           ms/op
Client.getUser:getUser·p0.9999        sample         17.105           ms/op
Client.getUser:getUser·p1.00          sample         17.105           ms/op
Client.listUser                       sample   4192   7.618 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample          2.728           ms/op
Client.listUser:listUser·p0.50        sample          7.348           ms/op
Client.listUser:listUser·p0.90        sample         10.174           ms/op
Client.listUser:listUser·p0.95        sample         11.316           ms/op
Client.listUser:listUser·p0.99        sample         14.536           ms/op
Client.listUser:listUser·p0.999       sample         19.326           ms/op
Client.listUser:listUser·p0.9999      sample         27.001           ms/op
Client.listUser:listUser·p1.00        sample         27.001           ms/op
