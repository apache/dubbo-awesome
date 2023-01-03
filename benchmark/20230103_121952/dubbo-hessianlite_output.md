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
# Warmup Iteration   1: 1.089 ops/ms
Iteration   1: 2.604 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.604 ops/ms


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
# Warmup Iteration   1: 2.944 ops/ms
Iteration   1: 8.103 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.103 ops/ms


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
# Warmup Iteration   1: 1.789 ops/ms
Iteration   1: 5.344 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.344 ops/ms


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
# Warmup Iteration   1: 0.952 ops/ms
Iteration   1: 1.414 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.414 ops/ms


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
# Warmup Iteration   1: 14.357 ±(99.9%) 0.193 ms/op
Iteration   1: 6.704 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.704 ms/op


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
# Warmup Iteration   1: 5.922 ±(99.9%) 0.042 ms/op
Iteration   1: 3.131 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.131 ms/op


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
# Warmup Iteration   1: 9.629 ±(99.9%) 0.111 ms/op
Iteration   1: 4.743 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.743 ms/op


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
# Warmup Iteration   1: 34.030 ±(99.9%) 0.747 ms/op
Iteration   1: 17.437 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.437 ms/op


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
# Warmup Iteration   1: 11.041 ±(99.9%) 0.382 ms/op
Iteration   1: 6.003 ±(99.9%) 0.168 ms/op
                 createUser·p0.00:   2.707 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   7.561 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   15.157 ms/op
                 createUser·p0.999:  51.315 ms/op
                 createUser·p0.9999: 56.492 ms/op
                 createUser·p1.00:   56.492 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5648
  mean =      6.003 ±(99.9%) 0.168 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3063 
    [ 5.000, 10.000) = 2372 
    [10.000, 15.000) = 156 
    [15.000, 20.000) = 25 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 10 
    [50.000, 55.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.707 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     15.157 ms/op
     p(99.9000) =     51.315 ms/op
     p(99.9900) =     56.492 ms/op
     p(99.9990) =     56.492 ms/op
     p(99.9999) =     56.492 ms/op
    p(100.0000) =     56.492 ms/op


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
# Warmup Iteration   1: 5.642 ±(99.9%) 0.194 ms/op
Iteration   1: 3.876 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   8.687 ms/op
                 existUser·p0.999:  15.663 ms/op
                 existUser·p0.9999: 15.729 ms/op
                 existUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8277
  mean =      3.876 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 318 
    [ 2.500,  3.750) = 2152 
    [ 3.750,  5.000) = 5601 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      8.687 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     15.729 ms/op
     p(99.9990) =     15.729 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


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
# Warmup Iteration   1: 8.209 ±(99.9%) 0.279 ms/op
Iteration   1: 4.608 ±(99.9%) 0.074 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.480 ms/op
                 getUser·p0.99:   13.337 ms/op
                 getUser·p0.999:  20.318 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6930
  mean =      4.608 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 299 
    [ 2.500,  5.000) = 4913 
    [ 5.000,  7.500) = 1459 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.480 ms/op
     p(99.0000) =     13.337 ms/op
     p(99.9000) =     20.318 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 30.236 ±(99.9%) 0.845 ms/op
Iteration   1: 17.648 ±(99.9%) 0.228 ms/op
                 listUser·p0.00:   2.666 ms/op
                 listUser·p0.50:   17.760 ms/op
                 listUser·p0.90:   19.792 ms/op
                 listUser·p0.95:   21.327 ms/op
                 listUser·p0.99:   27.848 ms/op
                 listUser·p0.999:  33.265 ms/op
                 listUser·p0.9999: 33.423 ms/op
                 listUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1806
  mean =     17.648 ±(99.9%) 0.228 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 614 
    [17.500, 20.000) = 761 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.666 ms/op
     p(50.0000) =     17.760 ms/op
     p(90.0000) =     19.792 ms/op
     p(95.0000) =     21.327 ms/op
     p(99.0000) =     27.848 ms/op
     p(99.9000) =     33.265 ms/op
     p(99.9900) =     33.423 ms/op
     p(99.9990) =     33.423 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.604          ops/ms
Client.existUser                       thrpt         8.103          ops/ms
Client.getUser                         thrpt         5.344          ops/ms
Client.listUser                        thrpt         1.414          ops/ms
Client.createUser                       avgt         6.704           ms/op
Client.existUser                        avgt         3.131           ms/op
Client.getUser                          avgt         4.743           ms/op
Client.listUser                         avgt        17.437           ms/op
Client.createUser                     sample  5648   6.003 ± 0.168   ms/op
Client.createUser:createUser·p0.00    sample         2.707           ms/op
Client.createUser:createUser·p0.50    sample         4.866           ms/op
Client.createUser:createUser·p0.90    sample         7.561           ms/op
Client.createUser:createUser·p0.95    sample         8.389           ms/op
Client.createUser:createUser·p0.99    sample        15.157           ms/op
Client.createUser:createUser·p0.999   sample        51.315           ms/op
Client.createUser:createUser·p0.9999  sample        56.492           ms/op
Client.createUser:createUser·p1.00    sample        56.492           ms/op
Client.existUser                      sample  8277   3.876 ± 0.041   ms/op
Client.existUser:existUser·p0.00      sample         0.648           ms/op
Client.existUser:existUser·p0.50      sample         3.912           ms/op
Client.existUser:existUser·p0.90      sample         4.166           ms/op
Client.existUser:existUser·p0.95      sample         4.407           ms/op
Client.existUser:existUser·p0.99      sample         8.687           ms/op
Client.existUser:existUser·p0.999     sample        15.663           ms/op
Client.existUser:existUser·p0.9999    sample        15.729           ms/op
Client.existUser:existUser·p1.00      sample        15.729           ms/op
Client.getUser                        sample  6930   4.608 ± 0.074   ms/op
Client.getUser:getUser·p0.00          sample         1.108           ms/op
Client.getUser:getUser·p0.50          sample         4.579           ms/op
Client.getUser:getUser·p0.90          sample         5.947           ms/op
Client.getUser:getUser·p0.95          sample         6.480           ms/op
Client.getUser:getUser·p0.99          sample        13.337           ms/op
Client.getUser:getUser·p0.999         sample        20.318           ms/op
Client.getUser:getUser·p0.9999        sample        22.348           ms/op
Client.getUser:getUser·p1.00          sample        22.348           ms/op
Client.listUser                       sample  1806  17.648 ± 0.228   ms/op
Client.listUser:listUser·p0.00        sample         2.666           ms/op
Client.listUser:listUser·p0.50        sample        17.760           ms/op
Client.listUser:listUser·p0.90        sample        19.792           ms/op
Client.listUser:listUser·p0.95        sample        21.327           ms/op
Client.listUser:listUser·p0.99        sample        27.848           ms/op
Client.listUser:listUser·p0.999       sample        33.265           ms/op
Client.listUser:listUser·p0.9999      sample        33.423           ms/op
Client.listUser:listUser·p1.00        sample        33.423           ms/op
